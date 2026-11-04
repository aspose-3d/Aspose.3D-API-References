---
title: "Classe FontFile"
second_title: "Riferimento API Aspose.3D per .NET"
description: "classe Aspose.ThreeD.Profiles.FontFile. Il file font contiene definizioni per i glifi, è usato per creare il profilo di testo"
type: docs
weight: 1720
url: /it/net/aspose.threed.profiles/fontfile/
---
## FontFile class

Il file font contiene definizioni per i glifi, è usato per creare il profilo di testo.

```csharp
public abstract class FontFile : A3DObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Ottiene o imposta il nome. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Ottiene la collezione di tutte le proprietà. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | Carica FontFile dal nome file |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | Analizza FontFile da byte |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trova la proprietà. Può essere una proprietà dinamica (creata da CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata dal suo nome) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Ottieni il valore della proprietà specificata |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Rimuove una proprietà dinamica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Rimuove la proprietà specificata identificata per nome |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Imposta il valore della proprietà specificata |

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

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


