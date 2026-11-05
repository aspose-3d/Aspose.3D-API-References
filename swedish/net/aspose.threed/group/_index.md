---
title: "Klass Group"
second_title: "Aspose.3D för .NET API‑referens"
description: "Aspose.ThreeD.Group klass. En Group representerar de logiska relationerna för Node"
type: docs
weight: 1570
url: /sv/net/aspose.threed/group/
---
## Group class

En `Group` representerar de logiska relationerna för [`Node`](../node/).

```csharp
public class Group : A3DObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Group](group/)(string) | Skapa en ny instans av `Group` |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Groups](../../aspose.threed/group/groups/) { get; } | Undergrupper |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Hämtar eller anger namnet. |
| [Nodes](../../aspose.threed/group/nodes/) { get; } | Noderna i denna grupp |
| [Parent](../../aspose.threed/group/parent/) { get; } | Föräldragrupp för aktuell grupp |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Hämtar samlingen av alla egenskaper. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Hittar egenskapen. Den kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad med dess namn) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Hämta värdet för den angivna egenskapen |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Tar bort en dynamisk egenskap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Ta bort den angivna egenskapen identifierad med namn |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Sätter värdet för den angivna egenskapen |
| override [ToString](../../aspose.threed/group/tostring/)() | Hämtar strängrepresentationen av `Group` |

### Se även

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


