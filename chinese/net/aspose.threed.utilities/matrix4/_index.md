---
title: "Matrix4 结构体"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Utilities.Matrix4 结构体。4x4 矩阵实现"
type: docs
weight: 2790
url: /zh/net/aspose.threed.utilities/matrix4/
---
## Matrix4 structure

4x4 矩阵实现。

```csharp
public struct Matrix4
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Matrix4](matrix4/#constructor_3)(double[]) | 初始化 `Matrix4` 结构体的新实例。 |
| [Matrix4](matrix4/#constructor)(FMatrix4) | 从 [`FMatrix4`](../fmatrix4/) 实例构造 `Matrix4` |
| [Matrix4](matrix4/#constructor_1)(Vector4, Vector4, Vector4, Vector4) | 从 4 行构造矩阵。 |
| [Matrix4](matrix4/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | 初始化 `Matrix4` 结构体的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Identity](../../aspose.threed.utilities/matrix4/identity/) { get; } | 获取单位矩阵。 |
| [Determinant](../../aspose.threed.utilities/matrix4/determinant/) { get; } | 获取矩阵的行列式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate)(Quaternion) | 从四元数创建旋转矩阵 |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate_1)(double, Vector3) | 通过旋转角度和轴创建旋转矩阵 |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler)(Vector3) | 从欧拉角创建旋转矩阵 |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler_1)(double, double, double) | 从欧拉角创建旋转矩阵 |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_1)(double) | 创建一个在 x 轴、y 轴和 z 轴上缩放的矩阵。 |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale)(Vector3) | 创建一个在 x 轴、y 轴和 z 轴上缩放的矩阵。 |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_2)(double, double, double) | 创建一个在 x 轴、y 轴和 z 轴上缩放的矩阵。 |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate)(Vector3) | 创建一个在 x 轴、y 轴和 z 轴上平移的矩阵 |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate_1)(double, double, double) | 创建一个在 x 轴、y 轴和 z 轴上平移的矩阵 |
| [Concatenate](../../aspose.threed.utilities/matrix4/concatenate/)(Matrix4) | 连接两个矩阵 |
| [Decompose](../../aspose.threed.utilities/matrix4/decompose/)(out Vector3, out Vector3, out Quaternion) |  |
| [Inverse](../../aspose.threed.utilities/matrix4/inverse/)() | 对该实例求逆。 |
| [Normalize](../../aspose.threed.utilities/matrix4/normalize/)() | 对该实例进行归一化。 |
| [SetTRS](../../aspose.threed.utilities/matrix4/settrs/)(Vector3, Vector3, Vector3) | 使用平移/旋转/缩放初始化矩阵 |
| [ToArray](../../aspose.threed.utilities/matrix4/toarray/)() | 将矩阵转换为数组。 |
| override [ToString](../../aspose.threed.utilities/matrix4/tostring/)() | 返回表示当前 `Matrix4` 的字符串。 |
| [Transpose](../../aspose.threed.utilities/matrix4/transpose/)() | 转置此实例。 |
| [operator *](../../aspose.threed.utilities/matrix4/op_multiply/#op_multiply) | 乘以两个矩阵（4 个运算符） |

## 字段

| 名称 | 描述 |
| --- | --- |
| [m00](../../aspose.threed.utilities/matrix4/m00/) | m00。 |
| [m01](../../aspose.threed.utilities/matrix4/m01/) | m01。 |
| [m02](../../aspose.threed.utilities/matrix4/m02/) | m02。 |
| [m03](../../aspose.threed.utilities/matrix4/m03/) | m03。 |
| [m10](../../aspose.threed.utilities/matrix4/m10/) | m10。 |
| [m11](../../aspose.threed.utilities/matrix4/m11/) | m11。 |
| [m12](../../aspose.threed.utilities/matrix4/m12/) | m12。 |
| [m13](../../aspose.threed.utilities/matrix4/m13/) | m13。 |
| [m20](../../aspose.threed.utilities/matrix4/m20/) | m20。 |
| [m21](../../aspose.threed.utilities/matrix4/m21/) | m21。 |
| [m22](../../aspose.threed.utilities/matrix4/m22/) | m22。 |
| [m23](../../aspose.threed.utilities/matrix4/m23/) | m23。 |
| [m30](../../aspose.threed.utilities/matrix4/m30/) | m30。 |
| [m31](../../aspose.threed.utilities/matrix4/m31/) | m31。 |
| [m32](../../aspose.threed.utilities/matrix4/m32/) | m32。 |
| [m33](../../aspose.threed.utilities/matrix4/m33/) | m33。 |

## 示例

```csharp
Matrix4 mat = Matrix4.RotateFromEuler(90, 0, 0);
Matrix4 mat2 = Matrix4.Translate(0, 10, -50);
Matrix4 transform = mat2 * mat;
Vector4 pos = new Vector4(10, 9, 0, 1);
Vector4 transformed = transform * pos;

```

### 另请参见

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


