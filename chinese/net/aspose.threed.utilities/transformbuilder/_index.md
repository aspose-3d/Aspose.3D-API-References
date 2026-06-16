---
title: "类 TransformBuilder"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Utilities.TransformBuilder 类。TransformBuilder 用于通过一系列变换构建变换矩阵"
type: docs
weight: 2860
url: /zh/net/aspose.threed.utilities/transformbuilder/
---
## TransformBuilder class

`TransformBuilder` 用于通过一系列变换构建变换矩阵。

```csharp
public class TransformBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TransformBuilder](transformbuilder/#constructor)(ComposeOrder) | 构造一个具有初始单位变换矩阵和指定组合顺序的 `TransformBuilder` |
| [TransformBuilder](transformbuilder/#constructor_1)(Matrix4, ComposeOrder) | 构造一个具有初始变换矩阵和指定组合顺序的 `TransformBuilder` |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ComposeOrder](../../aspose.threed.utilities/transformbuilder/composeorder/) { get; set; } | 获取或设置链的组合顺序。 |
| [Matrix](../../aspose.threed.utilities/transformbuilder/matrix/) { get; set; } | 获取或设置当前矩阵值 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Append](../../aspose.threed.utilities/transformbuilder/append/)(Matrix4) | 将新的变换矩阵追加到变换链中。 |
| [Compose](../../aspose.threed.utilities/transformbuilder/compose/)(Matrix4) | 将参数追加或前置到内部矩阵。 |
| [Prepend](../../aspose.threed.utilities/transformbuilder/prepend/)(Matrix4) | 将新的变换矩阵前置到变换链中。 |
| [Rearrange](../../aspose.threed.utilities/transformbuilder/rearrange/)(Axis, Axis, Axis) | 重新排列轴的布局。 |
| [Reset](../../aspose.threed.utilities/transformbuilder/reset/)() | 将变换重置为单位矩阵 |
| [Rotate](../../aspose.threed.utilities/transformbuilder/rotate/)(Quaternion) | 通过四元数进行旋转链式操作 |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree)(double, Vector3) | 以度数进行旋转变换链式操作 |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree_1)(Vector3, RotationOrder) | 以指定顺序追加旋转。 |
| [RotateEulerDegree](../../aspose.threed.utilities/transformbuilder/rotateeulerdegree/)(double, double, double) | 通过欧拉角（度）进行旋转链式操作 |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian)(Vector3) | 通过欧拉角（弧度）进行旋转链式操作 |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian_1)(double, double, double) | 通过欧拉角（弧度）进行旋转链式操作 |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian)(double, Vector3) | 以弧度进行旋转变换链式操作 |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian_1)(Vector3, RotationOrder) | 以指定顺序追加旋转。 |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_1)(double) | 将缩放变换矩阵与按 s 缩放的组件链接 |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale)(Vector3) | 链接缩放变换 |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_2)(double, double, double) | 链接缩放变换矩阵 |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate)(Vector3) | 链接平移变换 |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate_1)(double, double, double) | 链接平移变换 |

## 示例

以下代码展示了如何通过一组操作创建矩阵

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(10, 20, 0);
tb.Scale(10, 10, 10);
tb.RotateEulerDegree(90, 0, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


