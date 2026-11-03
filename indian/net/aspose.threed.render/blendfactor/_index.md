---
title: "एनम BlendFactor"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Render.BlendFactor enum. ब्लेंड फ़ैक्टर पिक्सेल अंकगणित को निर्दिष्ट करता है"
type: docs
weight: 1890
url: /hi/net/aspose.threed.render/blendfactor/
---
## BlendFactor enumeration

ब्लेंड फैक्टर पिक्सेल अंकगणित को निर्दिष्ट करता है।

```csharp
public enum BlendFactor
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Zero | `0` | ब्लेंड फ़ैक्टर vec4(0) है |
| One | `1` | ब्लेंड फ़ैक्टर vec4(1) है |
| SrcColor | `2` | ब्लेंड फ़ैक्टर src.rgba है |
| OneMinusSrcColor | `3` | ब्लेंड फ़ैक्टर vec4(1) - src.rgba है |
| DstColor | `4` | ब्लेंड फ़ैक्टर dst.rgba है |
| OneMinusDstColor | `5` | ब्लेंड फ़ैक्टर vec4(1) - dst.rgba है |
| SrcAlpha | `6` | ब्लेंड फ़ैक्टर vec4(src.a) है |
| OneMinusSrcAlpha | `7` | ब्लेंड फ़ैक्टर vec4(1 - src.a) है |
| DstAlpha | `8` | ब्लेंड फ़ैक्टर vec4(dst.a) है |
| OneMinusDstAlpha | `9` | ब्लेंड फ़ैक्टर vec4(1 - dst.a) है |
| ConstantColor | `10` | ब्लेंड फ़ैक्टर c है जहाँ c को [`BlendColor`](../renderstate/blendcolor/) में निर्दिष्ट किया गया है |
| OneMinusConstantColor | `11` | ब्लेंड फ़ैक्टर vec4(1) - c है जहाँ c को [`BlendColor`](../renderstate/blendcolor/) में निर्दिष्ट किया गया है |
| ConstantAlpha | `12` | ब्लेंड फ़ैक्टर vec4(c.a) है जहाँ c को [`BlendColor`](../renderstate/blendcolor/) में निर्दिष्ट किया गया है |
| OneMinusConstantAlpha | `13` | ब्लेंड फ़ैक्टर vec4(1 - c.a) है जहाँ c को [`BlendColor`](../renderstate/blendcolor/) में निर्दिष्ट किया गया है |
| SrcAlphaSaturate | `14` | ब्लेंड फ़ैक्टर min(src.a, 1 - dst.a) है |

### देखें भी

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


