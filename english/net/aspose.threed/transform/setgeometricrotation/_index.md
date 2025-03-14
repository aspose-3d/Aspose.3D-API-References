---
title: Transform.SetGeometricRotation
second_title: Aspose.3D for .NET API Reference
description: Transform method. Sets the geometric Euler rotationmeasured in degree. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it
type: docs
weight: 160
url: /net/aspose.threed/transform/setgeometricrotation/
---
## Transform.SetGeometricRotation method

Sets the geometric Euler rotation(measured in degree). Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it.

```csharp
public Transform SetGeometricRotation(double rx, double ry, double rz)
```

## Examples

```csharp
Node node = new Node();
node.Transform.SetGeometricRotation(90, 0, 0);
```

### See Also

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


