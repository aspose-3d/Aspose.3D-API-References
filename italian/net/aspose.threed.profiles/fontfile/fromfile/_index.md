---
title: "FontFile.FromFile"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Metodo FontFile. Carica FontFile dal nome del file"
type: docs
weight: 10
url: /it/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

Carica FontFile dal nome file

```csharp
public static FontFile FromFile(string fileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Percorso al file font |

### Valore di ritorno

istanza FontFile

### Eccezioni

| eccezione | condizione |
| --- | --- |
| IOException | Generato quando non è riuscito a leggere dal file. |

## Esempi

Il codice seguente mostra come creare una mesh 3D dal testo usando il file font specificato.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### Vedi anche

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


