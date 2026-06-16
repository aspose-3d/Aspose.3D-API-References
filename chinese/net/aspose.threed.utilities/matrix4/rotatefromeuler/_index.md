---
title: "Matrix4.RotateFromEuler"
second_title: "Aspose.3D for .NET API 参考"
description: "Matrix4 方法。创建一个基于欧拉角的旋转矩阵"
type: docs
weight: 40
url: /zh/net/aspose.threed.utilities/matrix4/rotatefromeuler/
---
## RotateFromEuler(Vector3) {#rotatefromeuler}

从欧拉角创建旋转矩阵

```csharp
public static Matrix4 RotateFromEuler(Vector3 eul)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| eul | Vector3 | 以弧度表示的旋转 |

## 示例

以下代码展示了如何创建用于旋转操作的矩阵。

```csharp
var t = Matrix4.RotateFromEuler(new Vector3(0, Math.PI, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### 另请参见

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## RotateFromEuler(double, double, double) {#rotatefromeuler_1}

从欧拉角创建旋转矩阵

```csharp
public static Matrix4 RotateFromEuler(double rx, double ry, double rz)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rx | Double | 绕 x 轴的弧度旋转 |
| ry | Double | 绕 y 轴的弧度旋转 |
| rz | Double | 绕 z 轴的弧度旋转 |

## 示例

以下代码展示了如何创建用于旋转操作的矩阵。

```csharp
var t = Matrix4.RotateFromEuler(0, Math.PI, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### 另请参见

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


