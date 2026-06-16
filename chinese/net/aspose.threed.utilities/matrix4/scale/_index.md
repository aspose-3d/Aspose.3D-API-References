---
title: "Matrix4.Scale"
second_title: "Aspose.3D for .NET API 参考"
description: "Matrix4 方法。创建一个矩阵，使其沿 x 轴、y 轴和 z 轴进行缩放"
type: docs
weight: 50
url: /zh/net/aspose.threed.utilities/matrix4/scale/
---
## Scale(Vector3) {#scale}

创建一个在 x 轴、y 轴和 z 轴上缩放的矩阵。

```csharp
public static Matrix4 Scale(Vector3 s)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | Vector3 | 缩放工厂适用于 x 轴、y 轴和 z 轴 |

## 示例

以下代码展示了如何创建用于缩放操作的矩阵。

```csharp
var t = Matrix4.Scale(new Vector3(10, 10, 10));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### 另请参见

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double) {#scale_1}

创建一个在 x 轴、y 轴和 z 轴上缩放的矩阵。

```csharp
public static Matrix4 Scale(double s)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | Double | 缩放工厂适用于所有轴 |

## 示例

以下代码展示了如何创建用于缩放操作的矩阵。

```csharp
var t = Matrix4.Scale(10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### 另请参见

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

创建一个在 x 轴、y 轴和 z 轴上缩放的矩阵。

```csharp
public static Matrix4 Scale(double sx, double sy, double sz)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | Double | 缩放因子适用于 x 轴 |
| sy | Double | 缩放因子适用于 y 轴 |
| sz | Double | 缩放因子适用于 z 轴 |

## 示例

以下代码展示了如何创建用于缩放操作的矩阵。

```csharp
var t = Matrix4.Scale(10, 20, 10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### 另请参见

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


