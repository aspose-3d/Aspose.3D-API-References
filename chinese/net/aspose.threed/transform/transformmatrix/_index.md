---
title: "Transform.TransformMatrix"
second_title: "Aspose.3D for .NET API 参考"
description: "Transform 属性。获取或设置变换矩阵。"
type: docs
weight: 130
url: /zh/net/aspose.threed/transform/transformmatrix/
---
## Transform.TransformMatrix property

获取或设置变换矩阵。

```csharp
public Matrix4 TransformMatrix { get; set; }
```

## 备注

对其进行赋值将重置[`Translation`](../translation/)、[`Scaling`](../scaling/)和[`Rotation`](../rotation/)，而[`GeometricRotation`](../geometricrotation/)、[`GeometricScaling`](../geometricscaling/)和[`GeometricTranslation`](../geometrictranslation/)不会受到影响。

## 示例

```csharp
Node node = new Node();
node.Transform.TransformMatrix = Matrix4.Identity;
```

### 另请参见

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


