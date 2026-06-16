---
title: "Matrix4.Rotate"
second_title: "Aspose.3D for .NET API 参考"
description: "Matrix4 方法。通过旋转角度和轴创建旋转矩阵"
type: docs
weight: 30
url: /zh/net/aspose.threed.utilities/matrix4/rotate/
---
## Rotate(double, Vector3) {#rotate_1}

通过旋转角度和轴创建旋转矩阵

```csharp
public static Matrix4 Rotate(double angle, Vector3 axis)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | Double | 以弧度表示的旋转角度 |
| 轴 | Vector3 | 旋转轴 |

## 示例

以下代码展示了如何创建用于旋转操作的矩阵。

```csharp
var t = Matrix4.Rotate(Math.PI, new Vector3(0, 1, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### 另请参见

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Rotate(Quaternion) {#rotate}

从四元数创建旋转矩阵

```csharp
public static Matrix4 Rotate(Quaternion q)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| q | 四元数 | 旋转四元数 |

## 示例

以下代码展示了如何创建用于旋转操作的矩阵。

```csharp
var t = Matrix4.Rotate(Quaternion.FromAngleAxis(Math.PI, Vector3.YAxis));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### 另请参见

* struct [Quaternion](../../quaternion/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


