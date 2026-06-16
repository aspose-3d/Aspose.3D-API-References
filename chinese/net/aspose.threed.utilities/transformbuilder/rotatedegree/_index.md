---
title: "TransformBuilder.RotateDegree"
second_title: "Aspose.3D for .NET API 参考"
description: "TransformBuilder 方法。以度数链式旋转变换"
type: docs
weight: 100
url: /zh/net/aspose.threed.utilities/transformbuilder/rotatedegree/
---
## RotateDegree(double, Vector3) {#rotatedegree}

以度数进行旋转变换链式操作

```csharp
public TransformBuilder RotateDegree(double angle, Vector3 axis)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | Double | 旋转的角度（单位：度） |
| 轴 | Vector3 | 旋转轴 |

## 示例

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateDegree(90, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateDegree(Vector3, RotationOrder) {#rotatedegree_1}

以指定顺序追加旋转。

```csharp
public void RotateDegree(Vector3 rot, RotationOrder order)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rot | Vector3 | 旋转（度） |
| order | RotationOrder |  |

### 另请参见

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


