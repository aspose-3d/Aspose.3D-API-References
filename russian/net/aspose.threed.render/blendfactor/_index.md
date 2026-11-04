---
title: "Перечисление BlendFactor"
second_title: "Справочник API Aspose.3D для .NET"
description: "Перечисление Aspose.ThreeD.Render.BlendFactor. Коэффициент смешивания задаёт арифметику пикселей"
type: docs
weight: 1890
url: /ru/net/aspose.threed.render/blendfactor/
---
## BlendFactor enumeration

Коэффициент смешивания определяет арифметику пикселей.

```csharp
public enum BlendFactor
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Zero | `0` | Коэффициент смешивания равен vec4(0) |
| One | `1` | Коэффициент смешивания равен vec4(1) |
| SrcColor | `2` | Коэффициент смешивания равен src.rgba |
| OneMinusSrcColor | `3` | Коэффициент смешивания равен vec4(1) - src.rgba |
| DstColor | `4` | Коэффициент смешивания равен dst.rgba |
| OneMinusDstColor | `5` | Коэффициент смешивания равен vec4(1) - dst.rgba |
| SrcAlpha | `6` | Коэффициент смешивания равен vec4(src.a) |
| OneMinusSrcAlpha | `7` | Коэффициент смешивания равен vec4(1 - src.a) |
| DstAlpha | `8` | Коэффициент смешивания равен vec4(dst.a) |
| OneMinusDstAlpha | `9` | Коэффициент смешивания равен vec4(1 - dst.a) |
| ConstantColor | `10` | Коэффициент смешивания равен c, где c задаётся в [`BlendColor`](../renderstate/blendcolor/) |
| OneMinusConstantColor | `11` | Коэффициент смешивания равен vec4(1) - c, где c задаётся в [`BlendColor`](../renderstate/blendcolor/) |
| ConstantAlpha | `12` | Коэффициент смешивания равен vec4(c.a), где c задаётся в [`BlendColor`](../renderstate/blendcolor/) |
| OneMinusConstantAlpha | `13` | Коэффициент смешивания равен vec4(1 - c.a), где c задаётся в [`BlendColor`](../renderstate/blendcolor/) |
| SrcAlphaSaturate | `14` | Коэффициент смешивания равен min(src.a, 1 - dst.a) |

### См. также

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


