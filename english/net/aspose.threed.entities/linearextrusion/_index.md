---
title: LinearExtrusion
second_title: Aspose.3D for .NET API Reference
description: 
type: docs
weight: 430
url: /net/aspose.threed.entities/linearextrusion/
---
## LinearExtrusion class

Linear extrusion takes a 2D shape as input and extends the shape in the 3rd dimension.

```csharp
public class LinearExtrusion : Entity, IMeshConvertible
```

## Constructors

| Name | Description |
| --- | --- |
| [LinearExtrusion](linearextrusion)() | Constructor of instance [`LinearExtrusion`](../linearextrusion). |
| [LinearExtrusion](linearextrusion)(Profile, double) | Constructor of instance [`LinearExtrusion`](../linearextrusion). |

## Properties

| Name | Description |
| --- | --- |
| [Center](center) { get; set; } | If this value is false, the linear extrusion Z range is from 0 to height, otherwise the range is from -height/2 to height/2. |
| [Direction](direction) { get; set; } | The direction of extrusion, default value is (0, 0, 1) |
| [Height](height) { get; set; } | The height of the extruded geometry, default value is 1.0 |
| [Shape](shape) { get; set; } | The base shape to be extruded. |
| [Slices](slices) { get; set; } | The slices of the twisted extruded geometry, default value is 1. |
| [Twist](twist) { get; set; } | The number of degrees of through which the shape is extruded. |
| [TwistOffset](twistoffset) { get; set; } | The offset that used in twisting, default value is (0, 0, 0). |

## Methods

| Name | Description |
| --- | --- |
| [ToMesh](tomesh)() | Convert the extrusion to mesh. |

### See Also

* class [Entity](../../aspose.threed/entity)
* interface [IMeshConvertible](../imeshconvertible)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* assembly [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->