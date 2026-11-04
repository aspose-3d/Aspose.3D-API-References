---
title: "Klasse Group"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Aspose.ThreeD.Group class. Een Group vertegenwoordigt de logische relaties van Node"
type: docs
weight: 1570
url: /nl/net/aspose.threed/group/
---
## Group class

Een `Group` vertegenwoordigt de logische relaties van [`Node`](../node/).

```csharp
public class Group : A3DObject
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Group](group/)(string) | Construeer een nieuw exemplaar van `Group` |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Groups](../../aspose.threed/group/groups/) { get; } | Subgroepen |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Haalt op of stelt de naam in. |
| [Nodes](../../aspose.threed/group/nodes/) { get; } | De nodes in deze groep |
| [Parent](../../aspose.threed/group/parent/) { get; } | Bovenliggende groep van de huidige groep |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Haalt de verzameling van alle eigenschappen op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of een native‑eigenschap (geïdentificeerd aan de hand van de naam). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Haalt de waarde van de opgegeven eigenschap op |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Verwijdert een dynamische eigenschap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Verwijder de opgegeven eigenschap die wordt geïdentificeerd op naam |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Stelt de waarde van de opgegeven eigenschap in |
| override [ToString](../../aspose.threed/group/tostring/)() | Haalt de stringrepresentatie op van `Group` |

### Zie ook

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


