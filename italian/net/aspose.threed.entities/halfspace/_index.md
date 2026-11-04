---
title: "Classe HalfSpace"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Classe Aspose.ThreeD.Entities.HalfSpace. HalfSpace rappresenta uno spazio infinito che è diviso da un piano; può essere usato con BooleanOperator"
type: docs
weight: 420
url: /it/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` rappresenta uno spazio infinito che è diviso da un piano, può essere usato con [`BooleanOperator`](../booleanoperator/)

```csharp
public class HalfSpace : Entity
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | Costruisce una nuova istanza di `HalfSpace` |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | Costruisce una nuova istanza di `HalfSpace` con il vettore normale fornito e una posizione sul piano di taglio; |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Ottiene o imposta se escludere questa entità durante l'esportazione. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Ottiene o imposta il nome. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | La normale del piano di divisione, il piano è definito come N * P + D = 0 dove N è la Normale e P è qualsiasi punto sul piano. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Ottiene o imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Ottiene tutti i nodi genitori, un'entità può essere collegata a più nodi genitori per l'instanziamento della geometria |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | Qualsiasi punto sul piano diviso, il piano è definito come N * P + D = 0 dove N è la Normale e P è qualsiasi punto sul piano. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Ottiene la collezione di tutte le proprietà. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Ottiene la scena a cui appartiene questo oggetto |

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

### Vedi anche

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


