---
title: "Class BooleanOperator"
second_title: "Aspose.3D för .NET API‑referens"
description: "Aspose.ThreeD.Entities.BooleanOperator-klass. Booleskt operatör låter dig tillämpa boolesk operation på två IMeshConvertible-instans"
type: docs
weight: 280
url: /sv/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

Booleskt operatör låter dig tillämpa boolesk operation på två [`IMeshConvertible`](../imeshconvertible/) instanser.

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | Konstruktor för `BooleanOperator` |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | Skapar en ny instans av `BooleanOperator` med två operander |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Hämtar eller anger om detta objekt ska exkluderas vid export. |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | Den första operanden för den booleska operatören |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Hämtar eller anger namnet. |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | Den booleska operatören som används i operationen för att skapa resultatmesh. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Hämtar eller anger den första föräldranoden, om den första föräldranoden anges kommer detta objekt att frikopplas från andra föräldranoder. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Hämtar alla föräldranoder, ett objekt kan fästas vid flera föräldranoder för geometrisk instansering |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Hämtar samlingen av alla egenskaper. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Hämtar scenen som detta objekt tillhör |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | Den andra operanden för den booleska operatören |

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
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | Utför den booleska operationen på två operander |

### Se även

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


