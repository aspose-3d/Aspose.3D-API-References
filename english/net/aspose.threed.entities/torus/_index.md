---
title: Class Torus
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Entities.Torus class. Parameterized torus
type: docs
weight: 740
url: /net/aspose.threed.entities/torus/
---
## Torus class

Parameterized torus.

```csharp
public class Torus : Primitive
```

## Constructors

| Name | Description |
| --- | --- |
| [Torus](torus/#constructor)() | Initializes a new instance of the `Torus` class. |
| [Torus](torus/#constructor_1)(double, double) | Initializes a new instance of the `Torus` class. |
| [Torus](torus/#constructor_2)(double, double, double) | Initializes a new instance of the `Torus` class. |
| [Torus](torus/#constructor_3)(string, double, double, int, int, double) | Initializes a new instance of the `Torus` class. |

## Properties

| Name | Description |
| --- | --- |
| [Arc](../../aspose.threed.entities/torus/arc/) { get; set; } | Gets or sets the arc. |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Gets or sets whether this geometry can cast shadow |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Gets or sets whether to exclude this entity during exporting. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Gets or sets the name. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Gets or sets the first parent node, if set the first parent node, this entity will be detached from other parent nodes. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Gets all parent nodes, an entity can be attached to multiple parent nodes for geometry instancing |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gets the collection of all properties. |
| [RadialSegments](../../aspose.threed.entities/torus/radialsegments/) { get; set; } | Gets or sets the radial segments. |
| [Radius](../../aspose.threed.entities/torus/radius/) { get; set; } | Gets or sets the radius of the torus. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Gets or sets whether this geometry can receive shadow. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Gets the scene that this object belongs to |
| [Tube](../../aspose.threed.entities/torus/tube/) { get; set; } | Gets or sets the radius of the tube. |
| [TubularSegments](../../aspose.threed.entities/torus/tubularsegments/) { get; set; } | Gets or sets the tubular segments. |

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
| override [ToMesh](../../aspose.threed.entities/torus/tomesh/)() | Convert current object to mesh |

### See Also

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


