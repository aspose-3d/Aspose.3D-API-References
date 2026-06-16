---
title: "TransformBuilder.RotateEulerRadian"
second_title: "Aspose.3D for .NET API 参考"
description: "TransformBuilder 方法。链式欧拉角（弧度）旋转"
type: docs
weight: 120
url: /zh/net/aspose.threed.utilities/transformbuilder/rotateeulerradian/
---
## RotateEulerRadian(double, double, double) {#rotateeulerradian_1}

通过欧拉角（弧度）进行旋转链式操作

```csharp
public TransformBuilder RotateEulerRadian(double x, double y, double z)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double |  |
| y | Double |  |
| z | Double |  |

## 示例

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(0, Math.PI, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateEulerRadian(Vector3) {#rotateeulerradian}

通过欧拉角（弧度）进行旋转链式操作

```csharp
public TransformBuilder RotateEulerRadian(Vector3 r)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r | Vector3 |  |

## 示例

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(new Vector3(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


