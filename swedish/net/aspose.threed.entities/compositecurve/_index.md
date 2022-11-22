---
title: CompositeCurve
second_title: Aspose.3D för .NET API-referens
description: ACompositeCurve./compositecurve består av flera kurvsegment.
type: docs
weight: 270
url: /sv/net/aspose.threed.entities/compositecurve/
---
## CompositeCurve class

A[`CompositeCurve`](../compositecurve) består av flera kurvsegment.

```csharp
public class CompositeCurve : Curve
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [CompositeCurve](compositecurve)() | Konstruktör av[`CompositeCurve`](../compositecurve) |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color) { get; set; } | Hämtar eller ställer in färgen på linjen, standardvärdet är vit(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Hämtar eller ställer in om den här entiteten ska exkluderas under export. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Hämtar eller ställer in namnet. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Hämtar eller ställer in den första överordnade noden, om den första överordnade noden ställs in, kommer denna enhet att frikopplas från andra överordnade noder. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Hämtar alla överordnade noder, en enhet kan kopplas till flera överordnade noder för geometriinstansering |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Hämtar samlingen av alla egenskaper. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Hämtar scenen som detta objekt tillhör |
| [Segments](../../aspose.threed.entities/compositecurve/segments) { get; } | Kurvans segment. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddSegment](../../aspose.threed.entities/compositecurve/addsegment)(Curve, bool) |  |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Hittar egenskapen. Det kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller inbyggd egenskap (identifierad med dess namn) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Hämtar begränsningsrutan för nuvarande entitet i dess objektrymds koordinatsystem. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey)() | Hämtar nyckeln till entitetsrenderaren registrerad i renderaren |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Få värdet av specificerad egenskap |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Tar bort en dynamisk egenskap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Ta bort den angivna egenskapen identifierad av name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Anger värdet för specificerad egenskap |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [Segment](compositecurve.segment) |  |

### Se även

* class [Curve](../curve)
* namnutrymme [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->