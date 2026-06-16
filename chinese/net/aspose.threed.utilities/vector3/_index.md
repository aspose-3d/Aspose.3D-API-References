---
title: "结构体 Vector3"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Utilities.Vector3 结构体。一个具有三个分量的向量。"
type: docs
weight: 2880
url: /zh/net/aspose.threed.utilities/vector3/
---
## Vector3 structure

一个具有三个分量的向量。

```csharp
public struct Vector3 : IComparable<Vector3>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Vector3](vector3/#constructor_2)(double) | 初始化 `Vector3` 结构体的新实例。 |
| [Vector3](vector3/#constructor)(FVector3) | 初始化 `Vector3` 结构体的新实例。 |
| [Vector3](vector3/#constructor_1)(Vector4) | 初始化 `Vector3` 结构体的新实例。 |
| [Vector3](vector3/#constructor_3)(double, double, double) | 初始化 `Vector3` 结构体的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [One](../../aspose.threed.utilities/vector3/one/) { get; } | 获取单位向量 (1, 1, 1) |
| static [UnitX](../../aspose.threed.utilities/vector3/unitx/) { get; } | 获取单位向量 (1, 0, 0) |
| static [UnitY](../../aspose.threed.utilities/vector3/unity/) { get; } | 获取单位向量 (0, 1, 0) |
| static [UnitZ](../../aspose.threed.utilities/vector3/unitz/) { get; } | 获取单位向量 (0, 0, 1) |
| static [Zero](../../aspose.threed.utilities/vector3/zero/) { get; } | 获取单位向量 (0, 0, 0) |
| [Item](../../aspose.threed.utilities/vector3/item/) { get; set; } |  |
| [Length](../../aspose.threed.utilities/vector3/length/) { get; } | 获取此向量的长度。 |
| [Length2](../../aspose.threed.utilities/vector3/length2/) { get; } | 获取长度的平方。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AngleBetween](../../aspose.threed.utilities/vector3/anglebetween/#anglebetween)(Vector3) | 计算两个方向之间的内角 两个方向可以是未归一化的向量 |
| [AngleBetween](../../aspose.threed.utilities/vector3/anglebetween/#anglebetween_1)(Vector3, Vector3) | 计算两个方向之间的内角 两个方向可以是未归一化的向量 |
| [CompareTo](../../aspose.threed.utilities/vector3/compareto/)(Vector3) | 将当前向量与另一个实例进行比较。 |
| [Cos](../../aspose.threed.utilities/vector3/cos/)() | 对每个分量计算余弦 |
| [Cross](../../aspose.threed.utilities/vector3/cross/)(Vector3) | 两个向量的叉积 |
| [Dot](../../aspose.threed.utilities/vector3/dot/)(Vector3) | 获取两个向量的点积 |
| override [Equals](../../aspose.threed.utilities/vector3/equals/)(object) | 检查两个 vector3 是否相等 |
| override [GetHashCode](../../aspose.threed.utilities/vector3/gethashcode/)() | 获取 Vector3 的哈希码 |
| [Normalize](../../aspose.threed.utilities/vector3/normalize/)() | 对该实例进行归一化。 |
| [Set](../../aspose.threed.utilities/vector3/set/)(double, double, double) | 一次调用设置 x/y/z 分量。 |
| [Sin](../../aspose.threed.utilities/vector3/sin/)() | 对每个分量计算正弦 |
| override [ToString](../../aspose.threed.utilities/vector3/tostring/)() | 返回表示当前 `Vector3` 的字符串。 |
| [operator +](../../aspose.threed.utilities/vector3/op_addition/) | 运算符重载 + |
| [operator /](../../aspose.threed.utilities/vector3/op_division/#op_division_1) | 运算符重载 /（2 个运算符） |
| [operator ==](../../aspose.threed.utilities/vector3/op_equality/) | Vector3 的等于运算符 |
| [explicit operator](../../aspose.threed.utilities/vector3/op_explicit/) |  |
| [operator !=](../../aspose.threed.utilities/vector3/op_inequality/) | Vector3 的不等于运算符 |
| [operator *](../../aspose.threed.utilities/vector3/op_multiply/#op_multiply) | 运算符重载 *（3 个运算符） |
| [operator -](../../aspose.threed.utilities/vector3/op_subtraction/) | 运算符重载 -（2 个运算符） |

## 字段

| 名称 | 描述 |
| --- | --- |
| [X](../../aspose.threed.utilities/vector3/x/) | x 分量。 |
| [Y](../../aspose.threed.utilities/vector3/y/) | y 分量。 |
| [Z](../../aspose.threed.utilities/vector3/z/) | z 分量。 |

### 另请参见

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


