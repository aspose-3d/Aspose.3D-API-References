---
title: Cylinder
second_title: Aspose.3D for .NET API Reference
description: 
type: docs
weight: 310
url: /net/aspose.threed.entities/cylinder/
---
## Cylinder class

Parameterized Cylinder. It can also be used to represent the cone when one of radiusTop/radiusBottom is zero.

```csharp
public class Cylinder : Primitive
```

## Constructors

| Name | Description |
| --- | --- |
| [Cylinder](cylinder)() | Initializes a new instance of the [`Cylinder`](../cylinder) class. |
| [Cylinder](cylinder)(double, double) | Initializes a new instance of the [`Cylinder`](../cylinder) class. |
| [Cylinder](cylinder)(double, double, double) | Initializes a new instance of the [`Cylinder`](../cylinder) class. |
| [Cylinder](cylinder)(double, double, double, int, int, bool) | Initializes a new instance of the [`Cylinder`](../cylinder) class. |
| [Cylinder](cylinder)(string, double, double, double, int, int, bool, double, double) | Initializes a new instance of the [`Cylinder`](../cylinder) class. |

## Properties

| Name | Description |
| --- | --- |
| [GenerateFanCylinder](generatefancylinder) { get; set; } | Gets or sets whether to generate the fan-style cylinder when the ThetaLength is less than 2*PI, otherwise the model will not be cut. |
| [Height](height) { get; set; } | Gets or sets the height of the cylinder. |
| [HeightSegments](heightsegments) { get; set; } | Gets or sets the height segments. |
| [OffsetBottom](offsetbottom) { get; set; } | Gets or sets the vertices transformation offset of the bottom side. |
| [OffsetTop](offsettop) { get; set; } | Gets or sets the vertices transformation offset of the top side. |
| [OpenEnded](openended) { get; set; } | Gets or sets a value indicating whether this [`Cylinder`](../cylinder) open ended. The default value is false. |
| [RadialSegments](radialsegments) { get; set; } | Gets or sets the radial segments. |
| [RadiusBottom](radiusbottom) { get; set; } | Gets or sets the radius of cylinder's bottom cap. |
| [RadiusTop](radiustop) { get; set; } | Gets or sets the radius of cylinder's top cap. |
| [ShearBottom](shearbottom) { get; set; } | Gets or sets of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0) |
| [ShearTop](sheartop) { get; set; } | Gets or sets of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0) |
| [ThetaLength](thetalength) { get; set; } | Gets or sets the length of the theta. The default value is 2π. |
| [ThetaStart](thetastart) { get; set; } | Gets or sets the theta start. The default value is 0. |

## Methods

| Name | Description |
| --- | --- |
| override [ToMesh](tomesh)() | Convert current object to mesh |

### See Also

* class [Primitive](../primitive)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* assembly [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->