---
title: Circle
second_title: Aspose.3D för .NET API-referens
description: ACircle./circle kurvan består av en uppsättning punkter i kanten av cirkelformen.
type: docs
weight: 260
url: /sv/net/aspose.threed.entities/circle/
---
## Circle class

A[`Circle`](../circle) kurvan består av en uppsättning punkter i kanten av cirkelformen.

```csharp
public class Circle : Curve
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Circle](circle#constructor)() | Konstruktör av[`Circle`](../circle) |
| [Circle](circle#constructor_1)(double) | Konstruktör av[`Circle`](../circle) |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color) { get; set; } | Hämtar eller ställer in färgen på linjen, standardvärdet är vit(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Hämtar eller ställer in om den här entiteten ska exkluderas under export. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Hämtar eller ställer in namnet. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Hämtar eller ställer in den första överordnade noden, om den första överordnade noden ställs in, kommer denna enhet att frikopplas från andra överordnade noder. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Hämtar alla överordnade noder, en enhet kan kopplas till flera överordnade noder för geometriinstansering |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Hämtar samlingen av alla egenskaper. |
| [Radius](../../aspose.threed.entities/circle/radius) { get; set; } | Cirkelkurvans radie, standardvärdet är 10 |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Hämtar scenen som detta objekt tillhör |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Hittar egenskapen. Det kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller inbyggd egenskap (identifierad med dess namn) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Hämtar begränsningsrutan för nuvarande entitet i dess objektrymds koordinatsystem. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey)() | Hämtar nyckeln till entitetsrenderaren registrerad i renderaren |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Få värdet av specificerad egenskap |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Tar bort en dynamisk egenskap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Ta bort den angivna egenskapen identifierad av name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Anger värdet för specificerad egenskap |

### Se även

* class [Curve](../curve)
* namnutrymme [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->