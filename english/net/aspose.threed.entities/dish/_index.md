---
title: Class Dish
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Entities.Dish class. Parameterized dish
type: docs
weight: 350
url: /net/aspose.threed.entities/dish/
---
## Dish class

Parameterized dish.

```csharp
public class Dish : Primitive
```

## Constructors

| Name | Description |
| --- | --- |
| [Dish](dish/#constructor)() | Create a new dish instance with default radius(10) and default height(5) |
| [Dish](dish/#constructor_1)(double, double) | Create a new dish instance with specified radius and height |
| [Dish](dish/#constructor_2)(string, double, double, int, int) | Create a new dish instance with specified radius and height |

## Properties

| Name | Description |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Gets or sets whether this geometry can cast shadow |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Gets or sets whether to exclude this entity during exporting. |
| [Height](../../aspose.threed.entities/dish/height/) { get; set; } | Height of the dish |
| [HeightSegments](../../aspose.threed.entities/dish/heightsegments/) { get; set; } | Gets or sets the height segments |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Gets or sets the name. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Gets or sets the first parent node, if set the first parent node, this entity will be detached from other parent nodes. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Gets all parent nodes, an entity can be attached to multiple parent nodes for geometry instancing |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gets the collection of all properties. |
| [Radius](../../aspose.threed.entities/dish/radius/) { get; set; } | Radius of the dish |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Gets or sets whether this geometry can receive shadow. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Gets the scene that this object belongs to |
| [WidthSegments](../../aspose.threed.entities/dish/widthsegments/) { get; set; } | Gets or sets the width segments |

## Methods

| Name | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Finds the property. It can be a dynamic property (Created by CreateDynamicProperty/SetProperty) or native property(Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Gets the bounding box of current entity in its object space coordinate system. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Gets the key of the entity renderer registered in the renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Get the value of specified property |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Removes a dynamic property. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Remove the specified property identified by name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Sets the value of specified property |
| override [ToMesh](../../aspose.threed.entities/dish/tomesh/)() | Convert current object to mesh |

### See Also

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


