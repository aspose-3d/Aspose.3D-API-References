---
title: "Enum BlendFactor"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Render.BlendFactor Enum. Der Blend-Faktor gibt die Pixelarithmetik an."
type: docs
weight: 1890
url: /de/net/aspose.threed.render/blendfactor/
---
## BlendFactor enumeration

Der Blend-Faktor gibt die Pixelarithmetik an.

```csharp
public enum BlendFactor
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Zero | `0` | Der Blend-Faktor ist vec4(0) |
| One | `1` | Der Blend-Faktor ist vec4(1) |
| SrcColor | `2` | Der Blend-Faktor ist src.rgba |
| OneMinusSrcColor | `3` | Der Blend-Faktor ist vec4(1) - src.rgba |
| DstColor | `4` | Der Blend-Faktor ist dst.rgba |
| OneMinusDstColor | `5` | Der Blend-Faktor ist vec4(1) - dst.rgba |
| SrcAlpha | `6` | Der Blend-Faktor ist vec4(src.a) |
| OneMinusSrcAlpha | `7` | Der Blend-Faktor ist vec4(1 - src.a) |
| DstAlpha | `8` | Der Blend-Faktor ist vec4(dst.a) |
| OneMinusDstAlpha | `9` | Der Blend-Faktor ist vec4(1 - dst.a) |
| ConstantColor | `10` | Der Mischfaktor ist c, wobei c in [`BlendColor`](../renderstate/blendcolor/) angegeben ist. |
| OneMinusConstantColor | `11` | Der Mischfaktor ist vec4(1) - c, wobei c in [`BlendColor`](../renderstate/blendcolor/) angegeben ist. |
| ConstantAlpha | `12` | Der Mischfaktor ist vec4(c.a), wobei c in [`BlendColor`](../renderstate/blendcolor/) angegeben ist. |
| OneMinusConstantAlpha | `13` | Der Mischfaktor ist vec4(1 - c.a), wobei c in [`BlendColor`](../renderstate/blendcolor/) angegeben ist. |
| SrcAlphaSaturate | `14` | Der Mischfaktor ist min(src.a, 1 - dst.a) |

### Siehe auch

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


