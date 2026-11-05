---
title: "Klass HalfSpace"
second_title: "Aspose.3D för .NET API‑referens"
description: "Aspose.ThreeD.Entities.HalfSpace-klass. HalfSpace representerar ett oändligt utrymme som delas av ett plan, detta kan användas med BooleanOperator"
type: docs
weight: 420
url: /sv/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` representerar ett oändligt utrymme som delas av ett plan, detta kan användas med [`BooleanOperator`](../booleanoperator/)

```csharp
public class HalfSpace : Entity
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | Skapar en ny instans av `HalfSpace` |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | Skapar en ny instans av `HalfSpace` med given normalvektor och en position på skärplanet; |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Hämtar eller anger om detta objekt ska exkluderas vid export. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Hämtar eller anger namnet. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | Normalen för delningsplanet, planet definieras som N * P + D = 0 där N är normal och P är någon punkt på planet. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Hämtar eller anger den första föräldranoden, om den första föräldranoden anges kommer detta objekt att frikopplas från andra föräldranoder. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Hämtar alla föräldranoder, ett objekt kan fästas vid flera föräldranoder för geometrisk instansering |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | Den valfria punkten på delningsplanet, planet definieras som N * P + D = 0 där N är Normal och P är en valfri punkt på planet. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Hämtar samlingen av alla egenskaper. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Hämtar scenen som detta objekt tillhör |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Hittar egenskapen. Den kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad med dess namn) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Hämtar den omgivande lådan för den aktuella enheten i dess objektrumskoordinatsystem. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Hämta värdet för den angivna egenskapen |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Tar bort en dynamisk egenskap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Ta bort den angivna egenskapen identifierad med namn |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Sätter värdet för den angivna egenskapen |

### Se även

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


