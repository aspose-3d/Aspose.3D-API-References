---
title: "结构体 Quaternion"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Utilities.Quaternion 结构体。四元数通常用于在计算机图形学中执行旋转"
type: docs
weight: 2810
url: /zh/net/aspose.threed.utilities/quaternion/
---
## Quaternion structure

四元数通常用于在计算机图形学中执行旋转。

```csharp
public struct Quaternion
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Quaternion](quaternion/)(double, double, double, double) | 初始化 `Quaternion` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Length](../../aspose.threed.utilities/quaternion/length/) { get; } | 获取四元数的长度 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromAngleAxis](../../aspose.threed.utilities/quaternion/fromangleaxis/)(double, Vector3) | 围绕给定轴创建四元数并顺时针旋转 |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle)(Vector3) | 从给定的欧拉角创建四元数 |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle_1)(double, double, double) | 从给定的欧拉角创建四元数 |
| static [FromRotation](../../aspose.threed.utilities/quaternion/fromrotation/)(Vector3, Vector3) | 创建一个从原始方向旋转到目标方向的四元数 |
| static [Interpolate](../../aspose.threed.utilities/quaternion/interpolate/)(float, Quaternion, Quaternion) | 使用在给定四元数参数之间、t 在 from 与 to 之间的插值结果填充此四元数。 |
| static [Slerp](../../aspose.threed.utilities/quaternion/slerp/)(double, Quaternion, Quaternion) | 在两个值之间执行球面线性插值 |
| [Concat](../../aspose.threed.utilities/quaternion/concat/)(Quaternion) | 连接两个四元数 |
| [Conjugate](../../aspose.threed.utilities/quaternion/conjugate/)() | 返回当前四元数的共轭四元数 |
| [Dot](../../aspose.threed.utilities/quaternion/dot/)(Quaternion) | 点积 |
| override [Equals](../../aspose.threed.utilities/quaternion/equals/)(object) | 检查两个四元数是否相等 |
| [EulerAngles](../../aspose.threed.utilities/quaternion/eulerangles/)() | 将四元数转换为欧拉角表示的旋转，所有分量均为弧度 |
| override [GetHashCode](../../aspose.threed.utilities/quaternion/gethashcode/)() | 获取四元数的哈希码 |
| [Inverse](../../aspose.threed.utilities/quaternion/inverse/)() | 返回当前四元数的逆四元数 |
| [Normalize](../../aspose.threed.utilities/quaternion/normalize/)() | 归一化四元数 |
| [ToAngleAxis](../../aspose.threed.utilities/quaternion/toangleaxis/)(out double, out Vector3) |  |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix)() | 将四元数表示的旋转转换为变换矩阵。 |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix_1)(Vector3) | 将四元数表示的旋转转换为变换矩阵。 |
| override [ToString](../../aspose.threed.utilities/quaternion/tostring/)() | 获取四元数的字符串表示 |
| [operator +](../../aspose.threed.utilities/quaternion/op_addition/) | 运算符重载 + |
| [operator /](../../aspose.threed.utilities/quaternion/op_division/) | 对 / 的运算符重载 |
| [operator ==](../../aspose.threed.utilities/quaternion/op_equality/) | 四元数的等于运算符 |
| [operator !=](../../aspose.threed.utilities/quaternion/op_inequality/) | 四元数的不等于运算符 |
| [operator *](../../aspose.threed.utilities/quaternion/op_multiply/#op_multiply_1) | 对 * 的运算符重载（5 个运算符） |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [Identity](../../aspose.threed.utilities/quaternion/identity/) | 单位四元数。 |
| [W](../../aspose.threed.utilities/quaternion/w/) | w 分量。 |
| [X](../../aspose.threed.utilities/quaternion/x/) | x 分量。 |
| [Y](../../aspose.threed.utilities/quaternion/y/) | y 分量。 |
| [Z](../../aspose.threed.utilities/quaternion/z/) | z 分量。 |

### 另请参见

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


