---
title: "Énum BlendFactor"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Render.BlendFactor enum. Le facteur de mélange spécifie l'arithmétique des pixels"
type: docs
weight: 1890
url: /fr/net/aspose.threed.render/blendfactor/
---
## BlendFactor enumeration

Le facteur de mélange spécifie l'arithmétique des pixels.

```csharp
public enum BlendFactor
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Zero | `0` | Le facteur de mélange est vec4(0) |
| One | `1` | Le facteur de mélange est vec4(1) |
| SrcColor | `2` | Le facteur de mélange est src.rgba |
| OneMinusSrcColor | `3` | Le facteur de mélange est vec4(1) - src.rgba |
| DstColor | `4` | Le facteur de mélange est dst.rgba |
| OneMinusDstColor | `5` | Le facteur de mélange est vec4(1) - dst.rgba |
| SrcAlpha | `6` | Le facteur de mélange est vec4(src.a) |
| OneMinusSrcAlpha | `7` | Le facteur de mélange est vec4(1 - src.a) |
| DstAlpha | `8` | Le facteur de mélange est vec4(dst.a) |
| OneMinusDstAlpha | `9` | Le facteur de mélange est vec4(1 - dst.a) |
| ConstantColor | `10` | Le facteur de mélange est c où c est spécifié dans [`BlendColor`](../renderstate/blendcolor/) |
| OneMinusConstantColor | `11` | Le facteur de mélange est vec4(1) - c où c est spécifié dans [`BlendColor`](../renderstate/blendcolor/) |
| ConstantAlpha | `12` | Le facteur de mélange est vec4(c.a) où c est spécifié dans [`BlendColor`](../renderstate/blendcolor/) |
| OneMinusConstantAlpha | `13` | Le facteur de mélange est vec4(1 - c.a) où c est spécifié dans [`BlendColor`](../renderstate/blendcolor/) |
| SrcAlphaSaturate | `14` | Le facteur de mélange est min(src.a, 1 - dst.a) |

### Voir aussi

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


