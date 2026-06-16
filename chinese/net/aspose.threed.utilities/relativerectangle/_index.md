---
title: "结构体 RelativeRectangle"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Utilities.RelativeRectangle 结构体。相对矩形。相对组件到绝对值的公式为 Scale * Reference Width + offset。因此如果我们想让它表示绝对值，则将所有 scale 字段设为零，改用 offset 字段。"
type: docs
weight: 2830
url: /zh/net/aspose.threed.utilities/relativerectangle/
---
## RelativeRectangle structure

相对矩形。相对组件到绝对值的公式为：Scale * (Reference Width) + offset。因此，如果我们想让它表示绝对值，请将所有 scale 字段设为零，并改用 offset 字段。

```csharp
public struct RelativeRectangle
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RelativeRectangle](relativerectangle/)(int, int, int, int) | 构造一个 `RelativeRectangle` |

## 属性

| 名称 | 描述 |
| --- | --- |
| [OffsetHeight](../../aspose.threed.utilities/relativerectangle/offsetheight/) { get; set; } | 获取或设置高度的偏移量 |
| [OffsetWidth](../../aspose.threed.utilities/relativerectangle/offsetwidth/) { get; set; } | 获取或设置宽度的偏移量 |
| [OffsetX](../../aspose.threed.utilities/relativerectangle/offsetx/) { get; set; } | 获取或设置坐标 X 的偏移量 |
| [OffsetY](../../aspose.threed.utilities/relativerectangle/offsety/) { get; set; } | 获取或设置坐标 Y 的偏移量 |
| [ScaleHeight](../../aspose.threed.utilities/relativerectangle/scaleheight/) { get; set; } | 相对高度 |
| [ScaleWidth](../../aspose.threed.utilities/relativerectangle/scalewidth/) { get; set; } | 相对宽度 |
| [ScaleX](../../aspose.threed.utilities/relativerectangle/scalex/) { get; set; } | 相对坐标 X |
| [ScaleY](../../aspose.threed.utilities/relativerectangle/scaley/) { get; set; } | 相对坐标 Y |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromScale](../../aspose.threed.utilities/relativerectangle/fromscale/)(float, float, float, float) | 使用所有偏移字段为零且缩放字段来自给定参数的方式构造一个 `RelativeRectangle`。 |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute/)(int, int, int, int) | 将相对矩形转换为绝对矩形 |
| override [ToString](../../aspose.threed.utilities/relativerectangle/tostring/)() | 将此实例的值转换为字符串。 |

### 另请参见

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


