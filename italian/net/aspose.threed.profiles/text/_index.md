---
title: "Classe Text"
second_title: "Riferimento API Aspose.3D per .NET"
description: "classe Aspose.ThreeD.Profiles.Text. Profilo di testo, questo profilo descrive i contorni usando caratteri e testo"
type: docs
weight: 1820
url: /it/net/aspose.threed.profiles/text/
---
## Text class

Profilo di testo, questo profilo descrive i contorni usando caratteri e testo.

```csharp
public class Text : Profile
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Text](text/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Content](../../aspose.threed.profiles/text/content/) { get; set; } | Contenuto del testo |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Ottiene o imposta se escludere questa entità durante l'esportazione. |
| [Font](../../aspose.threed.profiles/text/font/) { get; set; } | Il font del testo. |
| [FontSize](../../aspose.threed.profiles/text/fontsize/) { get; set; } | Scala della dimensione del font. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Ottiene o imposta il nome. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Ottiene o imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Ottiene tutti i nodi genitori, un'entità può essere collegata a più nodi genitori per l'instanziamento della geometria |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Ottiene la collezione di tutte le proprietà. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Ottiene la scena a cui appartiene questo oggetto |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trova la proprietà. Può essere una proprietà dinamica (creata da CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata dal suo nome) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Ottiene la chiave del renderer dell'entità registrata nel renderer |
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

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


