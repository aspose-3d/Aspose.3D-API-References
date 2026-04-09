---
title: 类 BooleanOperand
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Entities.BooleanOperand 类。此类将转换后的网格封装为布尔运算的操作数
type: docs
weight: 260
url: /zh/net/aspose.threed.entities/booleanoperand/
---
## BooleanOperand class

此类将变换后的网格封装为布尔运算的操作数。

```csharp
public class BooleanOperand
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Operand](../../aspose.threed.entities/booleanoperand/operand/) { get; } | 获取操作数，它可以是 [`HalfSpace`](../halfspace/)、[`IMeshConvertible`](../imeshconvertible/) 或 [`Node`](../../aspose.threed/node/) 的实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Of](../../aspose.threed.entities/booleanoperand/of/#of)(Entity) | 从裸 [`IMeshConvertible`](../imeshconvertible/) 实例构造 `BooleanOperand` 实例。 |
| static [Of](../../aspose.threed.entities/booleanoperand/of/#of_2)(Node) | 从节点构造 `BooleanOperand` 实例，需要一个实现了 [`IMeshConvertible`](../imeshconvertible/) 的有效实体。 |
| static [Of](../../aspose.threed.entities/booleanoperand/of/#of_1)(Entity, Matrix4?) |  |
| override [ToString](../../aspose.threed.entities/booleanoperand/tostring/)() | 获取 `BooleanOperand` 的字符串表示形式 |

### 另请参见

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


