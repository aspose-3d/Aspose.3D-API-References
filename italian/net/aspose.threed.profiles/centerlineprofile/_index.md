---
title: "Classe CenterLineProfile"
second_title: "Riferimento API Aspose.3D per .NET"
description: "classe Aspose.ThreeD.Profiles.CenterLineProfile. Profilo di linea centrale compatibile con IFC"
type: docs
weight: 1690
url: /it/net/aspose.threed.profiles/centerlineprofile/
---
## CenterLineProfile class

Profilo di linea centrale compatibile con IFC

```csharp
public class CenterLineProfile : Profile
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CenterLineProfile](centerlineprofile/)(Curve, double) | Crea un nuovo `CenterLineProfile` con la curva specificata come linea centrale. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Curve](../../aspose.threed.profiles/centerlineprofile/curve/) { get; set; } | La curva della linea centrale del profilo |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Ottiene o imposta se escludere questa entità durante l'esportazione. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Ottiene o imposta il nome. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Ottiene o imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Ottiene tutti i nodi genitori, un'entità può essere collegata a più nodi genitori per l'instanziamento della geometria |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Ottiene la collezione di tutte le proprietà. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Ottiene la scena a cui appartiene questo oggetto |
| [Thickness](../../aspose.threed.profiles/centerlineprofile/thickness/) { get; set; } | Spessore applicato lungo la linea centrale |

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

### Vedi anche

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


