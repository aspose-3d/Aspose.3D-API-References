---
title: BlendFactor
second_title: Aspose.3D لمرجع .NET API
description: عامل المزج يحدد حساب البكسل .
type: docs
weight: 1700
url: /ar/net/aspose.threed.render/blendfactor/
---
## BlendFactor enumeration

عامل المزج يحدد حساب البكسل .

```csharp
public enum BlendFactor
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Zero | `0` | عامل المزج هو vec4 (0) |
| One | `1` | عامل المزج هو vec4 (1) |
| SrcColor | `2` | عامل المزج هو src.rgba |
| OneMinusSrcColor | `3` | عامل المزج هو vec4 (1) - src.rgba |
| DstColor | `4` | عامل المزج هو dst.rgba |
| OneMinusDstColor | `5` | عامل المزج هو vec4 (1) - dst.rgba |
| SrcAlpha | `6` | عامل المزج هو vec4 (src.a) |
| OneMinusSrcAlpha | `7` | عامل المزج هو vec4 (1 - src.a) |
| DstAlpha | `8` | عامل المزج هو vec4 (dst.a) |
| OneMinusDstAlpha | `9` | عامل المزج هو vec4 (1 - dst.a) |
| ConstantColor | `10` | عامل المزج هو c حيث تم تحديد c في[`BlendColor`](../renderstate/blendcolor) |
| OneMinusConstantColor | `11` | عامل المزج هو vec4 (1) - c حيث تم تحديد c في[`BlendColor`](../renderstate/blendcolor) |
| ConstantAlpha | `12` | عامل المزج هو vec4 (ca) حيث تم تحديد c في[`BlendColor`](../renderstate/blendcolor) |
| OneMinusConstantAlpha | `13` | عامل المزج هو vec4 (1 - ca) حيث تم تحديد c في[`BlendColor`](../renderstate/blendcolor) |
| SrcAlphaSaturate | `14` | عامل المزج هو min (src.a، 1 - dst.a) |

### أنظر أيضا

* مساحة الاسم [Aspose.ThreeD.Render](../../aspose.threed.render)
* المجسم [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
