---
title: "TransformBuilder.RotateRadian"
second_title: "Aspose.3D for .NET API 参考"
description: "TransformBuilder 方法. 按弧度链式添加旋转变换"
type: docs
weight: 130
url: /zh/net/aspose.threed.utilities/transformbuilder/rotateradian/
---
## RotateRadian(double, Vector3) {#rotateradian}

以弧度进行旋转变换链式操作

```csharp
public TransformBuilder RotateRadian(double angle, Vector3 axis)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | Double | 以弧度表示的旋转角度 |
| 轴 | Vector3 | 旋转轴 |

## 示例

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(Math.PI, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateRadian(Vector3, RotationOrder) {#rotateradian_1}

以指定顺序追加旋转。

```csharp
public void RotateRadian(Vector3 rot, RotationOrder order)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rot | Vector3 | 以弧度表示的旋转 |
| order | RotationOrder |  |

## 示例

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(new Vector3(0.3, 0.4, 0.1), RotationOrder.YZX);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


