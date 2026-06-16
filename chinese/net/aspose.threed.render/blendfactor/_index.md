---
title: "枚举 BlendFactor"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.BlendFactor 枚举。混合因子指定像素算术"
type: docs
weight: 1890
url: /zh/net/aspose.threed.render/blendfactor/
---
## BlendFactor enumeration

混合因子指定像素算术运算。

```csharp
public enum BlendFactor
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Zero | `0` | 混合因子为 vec4(0) |
| One | `1` | 混合因子为 vec4(1) |
| SrcColor | `2` | 混合因子为 src.rgba |
| OneMinusSrcColor | `3` | 混合因子为 vec4(1) - src.rgba |
| DstColor | `4` | 混合因子为 dst.rgba |
| OneMinusDstColor | `5` | 混合因子为 vec4(1) - dst.rgba |
| SrcAlpha | `6` | 混合因子为 vec4(src.a) |
| OneMinusSrcAlpha | `7` | 混合因子为 vec4(1 - src.a) |
| DstAlpha | `8` | 混合因子为 vec4(dst.a) |
| OneMinusDstAlpha | `9` | 混合因子为 vec4(1 - dst.a) |
| ConstantColor | `10` | 混合因子为 c，其中 c 在 [`BlendColor`](../renderstate/blendcolor/) 中指定 |
| OneMinusConstantColor | `11` | 混合因子为 vec4(1) - c，其中 c 在 [`BlendColor`](../renderstate/blendcolor/) 中指定 |
| ConstantAlpha | `12` | 混合因子为 vec4(c.a)，其中 c 在 [`BlendColor`](../renderstate/blendcolor/) 中指定 |
| OneMinusConstantAlpha | `13` | 混合因子为 vec4(1 - c.a)，其中 c 在 [`BlendColor`](../renderstate/blendcolor/) 中指定 |
| SrcAlphaSaturate | `14` | 混合因子为 min(src.a, 1 - dst.a) |

### 另请参见

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


