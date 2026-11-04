---
title: "Classe BooleanOperator"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Classe **Aspose.ThreeD.Entities.BooleanOperator**. L'operatore booleano consente di applicare un'operazione booleana su due istanze di **IMeshConvertible**"
type: docs
weight: 280
url: /it/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

L'operatore booleano consente di applicare un'operazione booleana su due istanze di [`IMeshConvertible`](../imeshconvertible/).

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | Costruttore di `BooleanOperator` |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | Costruisce una nuova istanza di `BooleanOperator` con due operandi |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Ottiene o imposta se escludere questa entità durante l'esportazione. |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | Il primo operando dell'operatore booleano |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Ottiene o imposta il nome. |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | L'operatore booleano usato nell'operazione per creare la mesh risultato. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Ottiene o imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Ottiene tutti i nodi genitori, un'entità può essere collegata a più nodi genitori per l'instanziamento della geometria |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Ottiene la collezione di tutte le proprietà. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Ottiene la scena a cui appartiene questo oggetto |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | Il secondo operando dell'operatore booleano |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trova la proprietà. Può essere una proprietà dinamica (creata da CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata dal suo nome) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Ottiene la chiave del renderer dell'entità registrata nel renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Ottieni il valore della proprietà specificata |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Rimuove una proprietà dinamica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Rimuove la proprietà specificata identificata per nome |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Imposta il valore della proprietà specificata |
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | Esegui l'operazione booleana su due operandi |

### Vedi anche

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


