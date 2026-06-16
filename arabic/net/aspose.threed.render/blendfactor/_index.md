---
title: "تعداد BlendFactor"
second_title: "مرجع Aspose.3D for .NET API"
description: "تعداد Aspose.ThreeD.Render.BlendFactor. يحدد عامل المزج حسابات البكسل"
type: docs
weight: 1890
url: /ar/net/aspose.threed.render/blendfactor/
---
## BlendFactor enumeration

عامل الدمج يحدد حسابات البكسل.

```csharp
public enum BlendFactor
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Zero | `0` | عامل المزج هو vec4(0) |
| One | `1` | عامل المزج هو vec4(1) |
| SrcColor | `2` | عامل المزج هو src.rgba |
| OneMinusSrcColor | `3` | عامل المزج هو vec4(1) - src.rgba |
| DstColor | `4` | عامل المزج هو dst.rgba |
| OneMinusDstColor | `5` | عامل المزج هو vec4(1) - dst.rgba |
| SrcAlpha | `6` | عامل المزج هو vec4(src.a) |
| OneMinusSrcAlpha | `7` | عامل المزج هو vec4(1 - src.a) |
| DstAlpha | `8` | عامل المزج هو vec4(dst.a) |
| OneMinusDstAlpha | `9` | عامل المزج هو vec4(1 - dst.a) |
| ConstantColor | `10` | عامل المزج هو c حيث يتم تحديد c في [`BlendColor`](../renderstate/blendcolor/) |
| OneMinusConstantColor | `11` | عامل المزج هو vec4(1) - c حيث يتم تحديد c في [`BlendColor`](../renderstate/blendcolor/) |
| ConstantAlpha | `12` | عامل المزج هو vec4(c.a) حيث يتم تحديد c في [`BlendColor`](../renderstate/blendcolor/) |
| OneMinusConstantAlpha | `13` | عامل المزج هو vec4(1 - c.a) حيث يتم تحديد c في [`BlendColor`](../renderstate/blendcolor/) |
| SrcAlphaSaturate | `14` | عامل المزج هو min(src.a, 1 - dst.a) |

### انظر أيضًا

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


