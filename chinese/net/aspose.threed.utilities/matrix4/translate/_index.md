---
title: "Matrix4.Translate"
second_title: "Aspose.3D for .NET API 参考"
description: "Matrix4 方法。创建一个矩阵，使其沿 x 轴、y 轴和 z 轴平移"
type: docs
weight: 60
url: /zh/net/aspose.threed.utilities/matrix4/translate/
---
## Translate(Vector3) {#translate}

创建一个在 x 轴、y 轴和 z 轴上平移的矩阵

```csharp
public static Matrix4 Translate(Vector3 t)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| t | Vector3 | 平移偏移 |

## 示例

以下代码演示如何创建用于平移操作的矩阵。

```csharp
var t = Matrix4.Translate(new Vector3(10, 0, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### 另请参见

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Translate(double, double, double) {#translate_1}

创建一个在 x 轴、y 轴和 z 轴上平移的矩阵

```csharp
public static Matrix4 Translate(double tx, double ty, double tz)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tx | Double | X 坐标偏移 |
| ty | Double | Y 坐标偏移 |
| tz | Double | Z 坐标偏移 |

## 示例

以下代码演示如何创建用于平移操作的矩阵。

```csharp
var t = Matrix4.Translate(10, 0, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### 另请参见

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


