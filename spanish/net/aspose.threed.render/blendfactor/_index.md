---
title: BlendFactor
second_title: Referencia de API de Aspose.3D para .NET
description: Factor de fusión especificar aritmética de píxeles.
type: docs
weight: 1700
url: /es/net/aspose.threed.render/blendfactor/
---
## BlendFactor enumeration

Factor de fusión especificar aritmética de píxeles.

```csharp
public enum BlendFactor
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Zero | `0` | El factor de mezcla es vec4(0) |
| One | `1` | El factor de mezcla es vec4(1) |
| SrcColor | `2` | El factor de mezcla es src.rgba |
| OneMinusSrcColor | `3` | El factor de mezcla es vec4(1) - src.rgba |
| DstColor | `4` | El factor de combinación es dst.rgba |
| OneMinusDstColor | `5` | El factor de mezcla es vec4(1) - dst.rgba |
| SrcAlpha | `6` | El factor de combinación es vec4(src.a) |
| OneMinusSrcAlpha | `7` | El factor de mezcla es vec4(1 - src.a) |
| DstAlpha | `8` | El factor de mezcla es vec4(dst.a) |
| OneMinusDstAlpha | `9` | El factor de mezcla es vec4(1 - dst.a) |
| ConstantColor | `10` | El factor de mezcla es c donde c se especifica en[`BlendColor`](../renderstate/blendcolor) |
| OneMinusConstantColor | `11` | El factor de mezcla es vec4(1) - c donde c se especifica en[`BlendColor`](../renderstate/blendcolor) |
| ConstantAlpha | `12` | El factor de mezcla es vec4(ca) donde c se especifica en[`BlendColor`](../renderstate/blendcolor) |
| OneMinusConstantAlpha | `13` | El factor de mezcla es vec4(1 - ca) donde c se especifica en[`BlendColor`](../renderstate/blendcolor) |
| SrcAlphaSaturate | `14` | El factor de mezcla es min(src.a, 1 - dst.a) |

### Ver también

* espacio de nombres [Aspose.ThreeD.Render](../../aspose.threed.render)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
