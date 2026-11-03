---
title: "क्लास Renderer"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Render.Renderer क्लास। रेंडरर के बारे में संदर्भ"
type: docs
weight: 2340
url: /hi/net/aspose.threed.render/renderer/
---
## Renderer class

रेंडरर के बारे में संदर्भ।

```csharp
public abstract class Renderer : IDisposable
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AssetDirectories](../../aspose.threed.render/renderer/assetdirectories/) { get; } | बाहरी एसेट्स संग्रहीत करने वाली डायरेक्टरीज़ |
| [EnableShadows](../../aspose.threed.render/renderer/enableshadows/) { get; set; } | छायाओं को सक्षम करने के लिए प्राप्त या सेट करता है। |
| [FallbackEntityRenderer](../../aspose.threed.render/renderer/fallbackentityrenderer/) { get; set; } | जब इकाई के लिए कोई विशेष रेंडरर परिभाषित नहीं हो, तो फॉलबैक एंटिटी रेंडरर को प्राप्त या सेट करता है। |
| virtual [Frustum](../../aspose.threed.render/renderer/frustum/) { get; set; } | व्यू मैट्रिक्स प्रदान करने के लिए उपयोग किए जाने वाले फ्रस्टम को प्राप्त या सेट करता है। |
| virtual [Material](../../aspose.threed.render/renderer/material/) { get; set; } | शेडर द्वारा उपयोग की जाने वाली सामग्री जानकारी प्रदान करने वाले मैटेरियल को प्राप्त या सेट करता है। |
| [Node](../../aspose.threed.render/renderer/node/) { get; set; } | वर्ल्ड ट्रांसफ़ॉर्म मैट्रिक्स प्रदान करने के लिए उपयोग किए जाने वाले [`Node`](./node/) इंस्टेंस को प्राप्त या सेट करता है। |
| [PostProcessings](../../aspose.threed.render/renderer/postprocessings/) { get; } | सक्रिय पोस्ट-प्रोसेसिंग चेन |
| [PresetShaders](../../aspose.threed.render/renderer/presetshaders/) { get; set; } | पूर्वनिर्धारित शेडर सेट को प्राप्त या सेट करता है |
| abstract [RenderFactory](../../aspose.threed.render/renderer/renderfactory/) { get; } | रेंडर-संबंधित ऑब्जेक्ट्स बनाने के लिए फ़ैक्टरी को प्राप्त करता है। |
| [RenderStage](../../aspose.threed.render/renderer/renderstage/) { get; } | वर्तमान रेंडर स्टेज को प्राप्त करता है। |
| [RenderTarget](../../aspose.threed.render/renderer/rendertarget/) { get; } | उस रेंडर टार्गेट को निर्दिष्ट करें जिस पर आगे की रेंडर ऑपरेशन्स की जाएँगी। |
| [Shader](../../aspose.threed.render/renderer/shader/) { get; set; } | ज्यामिति को रेंडर करने के लिए उपयोग किए जाने वाले शेडर इंस्टेंस को प्राप्त या सेट करता है। |
| [ShaderSet](../../aspose.threed.render/renderer/shaderset/) { get; set; } | सीन को रेंडर करने के लिए उपयोग किए जाने वाले शेडर सेट को प्राप्त या सेट करता है। |
| [Variables](../../aspose.threed.render/renderer/variables/) { get; } | रेंडरिंग के लिए उपयोग किए जाने वाले आंतरिक वेरिएबल्स तक पहुँच |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [CreateRenderer](../../aspose.threed.render/renderer/createrenderer/)() | डिफ़ॉल्ट प्रोफ़ाइल के साथ नया `Renderer` बनाता है। |
| virtual [ClearCache](../../aspose.threed.render/renderer/clearcache/)() | कैश को मैन्युअल रूप से साफ़ करें। Aspose.3D कुछ ऑब्जेक्ट्स जैसे मैटेरियल्स/ज्यामितियों को रेंडर पाइपलाइन के अनुकूल आंतरिक प्रकारों में कैश करता है। जब सीन में बड़े बदलाव हों तो इसे मैन्युअल रूप से कॉल किया जाना चाहिए। |
| [Dispose](../../aspose.threed.render/renderer/dispose/)() | `Renderer` और सभी संबंधित संसाधनों को नष्ट करें |
| abstract [Execute](../../aspose.threed.render/renderer/execute/)(PostProcessing, IRenderTarget) | निर्दिष्ट रेंडर टार्गेट पर पोस्ट-प्रोसेसिंग निष्पादित करें |
| [GetPostProcessing](../../aspose.threed.render/renderer/getpostprocessing/)(string) | रेंडरर द्वारा समर्थित बिल्ट-इन पोस्ट-प्रोसेसर को प्राप्त करता है। |
| virtual [RegisterEntityRenderer](../../aspose.threed.render/renderer/registerentityrenderer/)(EntityRenderer) | निर्दिष्ट इकाई के लिए एंटिटी रेंडरर को रजिस्टर करें |
| virtual [Render](../../aspose.threed.render/renderer/render/)(IRenderTarget) | निर्दिष्ट टार्गेट को रेंडर करें |

### देखें भी

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


