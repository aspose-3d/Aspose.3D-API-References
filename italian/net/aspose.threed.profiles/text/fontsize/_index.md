---
title: "Text.FontSize"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Proprietà Text. Scala della dimensione del carattere"
type: docs
weight: 40
url: /it/net/aspose.threed.profiles/text/fontsize/
---
## Text.FontSize property

Scala della dimensione del font.

```csharp
public float FontSize { get; set; }
```

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

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


