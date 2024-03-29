---
title: Line
second_title: Aspose.3D för .NET API-referens
description: En polylinje är en bana som definieras av en uppsättning punkter medControlPoints./geometry/controlpoints  och ansluten avSegments./line/segments  vilket betyder att det också kan vara en uppsättning anslutna linjesegment. Linjen är vanligtvis ett linjärt objekt vilket betyder att den inte kan användas för att representera en kurva för att representera en kurva använderNurbsCurve./nurbscurve .
type: docs
weight: 420
url: /sv/net/aspose.threed.entities/line/
---
## Line class

En polylinje är en bana som definieras av en uppsättning punkter med[`ControlPoints`](../geometry/controlpoints) , och ansluten av[`Segments`](./segments) , vilket betyder att det också kan vara en uppsättning anslutna linjesegment. Linjen är vanligtvis ett linjärt objekt, vilket betyder att den inte kan användas för att representera en kurva, för att representera en kurva, använder[`NurbsCurve`](../nurbscurve) .

```csharp
public class Line : Curve
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Line](line#constructor)() | Initierar en ny instans av[`Line`](../line) class. |
| [Line](line#constructor_1)(string) | Initierar en ny instans av[`Line`](../line) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color) { get; set; } | Hämtar eller ställer in färgen på linjen, standardvärdet är vit(1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/line/controlpoints) { get; } | Får alla kontrollpunkter |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Hämtar eller ställer in om den här entiteten ska exkluderas under export. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Hämtar eller ställer in namnet. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Hämtar eller ställer in den första överordnade noden, om den första överordnade noden ställs in, kommer denna enhet att frikopplas från andra överordnade noder. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Hämtar alla överordnade noder, en enhet kan kopplas till flera överordnade noder för geometriinstansering |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Hämtar samlingen av alla egenskaper. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Hämtar scenen som detta objekt tillhör |
| [Segments](../../aspose.threed.entities/line/segments) { get; } | Hämtar segmenten av linjen |
| [Visible](../../aspose.threed.entities/line/visible) { get; set; } | Hämtar eller ställer in om geometrin är synlig |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromPoints](../../aspose.threed.entities/line/frompoints)(params Vector3[]) | Konstruera en[`Line`](../line) instans från en uppsättning punkter. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Hittar egenskapen. Det kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller inbyggd egenskap (identifierad med dess namn) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Hämtar begränsningsrutan för nuvarande entitet i dess objektrymds koordinatsystem. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey)() | Hämtar nyckeln till entitetsrenderaren registrerad i renderaren |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Få värdet av specificerad egenskap |
| [MakeDefaultIndices](../../aspose.threed.entities/line/makedefaultindices)() | Generera sekvensen 0,1,2,3....[`ControlPoints`](../geometry/controlpoints) .Längd-1 till[`Segments`](./segments) så att kontrollpunkterna kan användas som en enda rad |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Tar bort en dynamisk egenskap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Ta bort den angivna egenskapen identifierad av name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Anger värdet för specificerad egenskap |

### Se även

* class [Curve](../curve)
* namnutrymme [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
