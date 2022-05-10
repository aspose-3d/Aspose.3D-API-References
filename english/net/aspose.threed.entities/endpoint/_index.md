---
title: EndPoint
second_title: Aspose.3D for .NET API Reference
description: 
type: docs
weight: 340
url: /net/aspose.threed.entities/endpoint/
---
## EndPoint structure

The end point to trim the curve, can be a parameter value or a Cartesian point.

```csharp
public struct EndPoint
```

## Constructors

| Name | Description |
| --- | --- |
| [EndPoint](endpoint)(double) | Construct a [`EndPoint`](../endpoint) from a real parameter. |
| [EndPoint](endpoint)(Vector3) | Construct a [`EndPoint`](../endpoint) from a Cartesian point. |

## Properties

| Name | Description |
| --- | --- |
| [AsPoint](aspoint) { get; } | Gets the end point as Cartesian point, or thrown an exception. |
| [AsValue](asvalue) { get; } | Gets the end point as a real parameter, or throw an exception. |
| [IsCartesianPoint](iscartesianpoint) { get; } | Is the end point a Cartesian point? |

## Methods

| Name | Description |
| --- | --- |
| static [FromDegree](fromdegree)(double) | Create an end point measured in degree. |
| static [FromRadian](fromradian)(double) | Create an end point measured in radian. |
| override [ToString](tostring)() | Returns a string representation of the current end point. |

### See Also

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* assembly [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->