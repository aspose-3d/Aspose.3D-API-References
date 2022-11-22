---
title: Dish
second_title: Aspose.3D för .NET API-referens
description: Parameteriserad skål.
type: docs
weight: 320
url: /sv/net/aspose.threed.entities/dish/
---
## Dish class

Parameteriserad skål.

```csharp
public class Dish : Primitive
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Dish](dish#constructor)() | Skapa en ny maträttsinstans med standardradie(10) och standardhöjd(5) |
| [Dish](dish#constructor_1)(double, double) | Skapa en ny maträttsinstans med specificerad radie och height |
| [Dish](dish#constructor_2)(string, double, double, int, int) | Skapa en ny maträttsinstans med specificerad radie och height |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows) { get; set; } | Hämtar eller ställer in om denna geometri kan kasta skugga |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Hämtar eller ställer in om den här entiteten ska exkluderas under export. |
| [Height](../../aspose.threed.entities/dish/height) { get; set; } | Skålens höjd |
| [HeightSegments](../../aspose.threed.entities/dish/heightsegments) { get; set; } | Hämtar eller ställer in höjdsegmenten |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Hämtar eller ställer in namnet. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Hämtar eller ställer in den första överordnade noden, om den första överordnade noden ställs in, kommer denna enhet att frikopplas från andra överordnade noder. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Hämtar alla överordnade noder, en enhet kan kopplas till flera överordnade noder för geometriinstansering |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Hämtar samlingen av alla egenskaper. |
| [Radius](../../aspose.threed.entities/dish/radius) { get; set; } | Skålens radie |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows) { get; set; } | Hämtar eller ställer in om denna geometri kan ta emot skugga. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Hämtar scenen som detta objekt tillhör |
| [WidthSegments](../../aspose.threed.entities/dish/widthsegments) { get; set; } | Hämtar eller ställer in breddsegmenten |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Hittar egenskapen. Det kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller inbyggd egenskap (identifierad med dess namn) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Hämtar begränsningsrutan för nuvarande entitet i dess objektrymds koordinatsystem. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey)() | Hämtar nyckeln till entitetsrenderaren registrerad i renderaren |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Få värdet av specificerad egenskap |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Tar bort en dynamisk egenskap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Ta bort den angivna egenskapen identifierad av name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Anger värdet för specificerad egenskap |
| override [ToMesh](../../aspose.threed.entities/dish/tomesh)() | Konvertera aktuellt objekt till mesh |

### Se även

* class [Primitive](../primitive)
* namnutrymme [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->