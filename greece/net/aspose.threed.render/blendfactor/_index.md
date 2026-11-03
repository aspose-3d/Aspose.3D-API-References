---
title: "Απαρίθμηση BlendFactor"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Render.BlendFactor enum. Ο παράγοντας ανάμειξης καθορίζει την αριθμητική των εικονοστοιχείων"
type: docs
weight: 1890
url: /el/net/aspose.threed.render/blendfactor/
---
## BlendFactor enumeration

Ο συντελεστής ανάμειξης καθορίζει την αριθμητική των pixel.

```csharp
public enum BlendFactor
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Zero | `0` | Ο παράγοντας ανάμειξης είναι vec4(0) |
| One | `1` | Ο παράγοντας ανάμειξης είναι vec4(1) |
| SrcColor | `2` | Ο παράγοντας ανάμειξης είναι src.rgba |
| OneMinusSrcColor | `3` | Ο παράγοντας ανάμειξης είναι vec4(1) - src.rgba |
| DstColor | `4` | Ο παράγοντας ανάμειξης είναι dst.rgba |
| OneMinusDstColor | `5` | Ο παράγοντας ανάμειξης είναι vec4(1) - dst.rgba |
| SrcAlpha | `6` | Ο παράγοντας ανάμειξης είναι vec4(src.a) |
| OneMinusSrcAlpha | `7` | Ο παράγοντας ανάμειξης είναι vec4(1 - src.a) |
| DstAlpha | `8` | Ο παράγοντας ανάμειξης είναι vec4(dst.a) |
| OneMinusDstAlpha | `9` | Ο παράγοντας ανάμειξης είναι vec4(1 - dst.a) |
| ConstantColor | `10` | Ο παράγοντας ανάμειξης είναι c όπου το c καθορίζεται στο [`BlendColor`](../renderstate/blendcolor/) |
| OneMinusConstantColor | `11` | Ο παράγοντας ανάμειξης είναι vec4(1) - c όπου το c καθορίζεται στο [`BlendColor`](../renderstate/blendcolor/) |
| ConstantAlpha | `12` | Ο παράγοντας ανάμειξης είναι vec4(c.a) όπου το c καθορίζεται στο [`BlendColor`](../renderstate/blendcolor/) |
| OneMinusConstantAlpha | `13` | Ο παράγοντας ανάμειξης είναι vec4(1 - c.a) όπου το c καθορίζεται στο [`BlendColor`](../renderstate/blendcolor/) |
| SrcAlphaSaturate | `14` | Ο παράγοντας ανάμειξης είναι min(src.a, 1 - dst.a) |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


