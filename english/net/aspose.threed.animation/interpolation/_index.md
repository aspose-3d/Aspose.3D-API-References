---
title: Enum Interpolation
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Animation.Interpolation enum. The key frames interpolation type
type: docs
weight: 80
url: /net/aspose.threed.animation/interpolation/
---
## Interpolation enumeration

The key frame's interpolation type.

```csharp
public enum Interpolation
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Constant | `0` | The value will remains constant to the value of the first point until the next segment. |
| Linear | `1` | Linear interpolation is a straight line between two points. |
| Bezier | `2` | A bezier or Hermite spline. |
| BSpline | `3` | Basis splines are defined by a series of control points, for which the curve is guaranteed only to go through the first and the last point. |
| CardinalSpline | `4` | A cardinal spline is a cubic Hermite spline whose tangents are defined by the endpoints and a tension parameter. |
| TCBSpline | `5` | Also called Kochanek-Bartels spline, the behavior of tangent is defined by tension/bias/continuity |

### See Also

* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


