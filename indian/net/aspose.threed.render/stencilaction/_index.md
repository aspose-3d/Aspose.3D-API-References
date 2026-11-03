---
title: "एन्यूम StencilAction"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Render.StencilAction enum. स्टेंसिल परीक्षण क्रियाएँ"
type: docs
weight: 2430
url: /hi/net/aspose.threed.render/stencilaction/
---
## StencilAction enumeration

स्टेंसिल परीक्षण क्रियाएँ

```csharp
public enum StencilAction
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Keep | `0` | वर्तमान मान को रखें |
| Zero | `1` | स्टेंसिल बफ़र मान को 0 पर सेट करता है |
| Replace | `2` | स्टेंसिल बफ़र को रेफ़रेंस पर सेट करता है जहाँ यह [`StencilReference`](../renderstate/stencilreference/) में परिभाषित है |
| Increment | `3` | वर्तमान स्टेंसिल बफ़र मान को बढ़ाता है, अधिकतम मान तक सीमित करता है। |
| IncrementWrap | `4` | वर्तमान स्टेंसिल बफ़र मान को बढ़ाता है और जब यह अधिकतम मान तक पहुँचता है तो इसे शून्य पर लपेटता है। |
| Decrement | `5` | वर्तमान स्टेंसिल बफ़र मान को बढ़ाता है, 0 तक सीमित करता है। |
| DecrementWrap | `6` | वर्तमान स्टेंसिल बफ़र मान को घटाता है और जब यह शून्य तक पहुँचता है तो इसे अधिकतम मान पर लपेटता है। |
| Invert | `7` | बिट-वार वर्तमान स्टेंसिल बफ़र मान को उलटता है। |

### देखें भी

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


