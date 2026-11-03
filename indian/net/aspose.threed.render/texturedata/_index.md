---
title: "क्लास TextureData"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Render.TextureData क्लास। यह क्लास टेक्सचर का कच्चा डेटा और फ़ॉर्मेट परिभाषा रखती है"
type: docs
weight: 2460
url: /hi/net/aspose.threed.render/texturedata/
---
## TextureData class

यह क्लास टेक्सचर का कच्चा डेटा और प्रारूप परिभाषा रखती है।

```csharp
public class TextureData : A3DObject
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TextureData](texturedata/#constructor)() | `TextureData` का कंस्ट्रक्टर |
| [TextureData](texturedata/#constructor_1)(int, int, PixelFormat) | एक नया `TextureData` बनाता है और पिक्सेल डेटा आवंटित करता है। |
| [TextureData](texturedata/#constructor_2)(int, int, int, int, PixelFormat, byte[]) | `TextureData` का कंस्ट्रक्टर |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BytesPerPixel](../../aspose.threed.render/texturedata/bytesperpixel/) { get; } | एक पिक्सेल के बाइट्स की संख्या |
| [Data](../../aspose.threed.render/texturedata/data/) { get; } | पिक्सेल डेटा के कच्चे बाइट्स |
| [Height](../../aspose.threed.render/texturedata/height/) { get; } | ऊर्ध्वाधर पिक्सेल की संख्या |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [PixelFormat](../../aspose.threed.render/texturedata/pixelformat/) { get; } | पिक्सेल का फ़ॉर्मेट |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Stride](../../aspose.threed.render/texturedata/stride/) { get; } | एक स्कैनलाइन के बाइट्स की संख्या। |
| [Width](../../aspose.threed.render/texturedata/width/) { get; } | क्षैतिज पिक्सेल की संख्या |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromFile](../../aspose.threed.render/texturedata/fromfile/)(string) | फ़ाइल से टेक्सचर लोड करें |
| static [FromStream](../../aspose.threed.render/texturedata/fromstream/)(Stream) | स्ट्रीम से टेक्सचर लोड करें |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels)(PixelMapMode) | पढ़ने/लिखने के लिए सभी पिक्सेल को मैप करें |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_1)(PixelMapMode, PixelFormat) | दिए गए पिक्सेल फ़ॉर्मेट में पढ़ने/लिखने के लिए सभी पिक्सेल को मैप करें |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_2)(Rect, PixelMapMode, PixelFormat) | दिए गए पिक्सेल फ़ॉर्मेट में पढ़ने/लिखने के लिए रेक्ट द्वारा निर्दिष्ट पिक्सेल को मैप करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [Save](../../aspose.threed.render/texturedata/save/#save_1)(string) | टेक्सचर डेटा को इमेज फ़ाइल में सहेजें |
| [Save](../../aspose.threed.render/texturedata/save/#save)(Stream, string) | टेक्सचर डेटा को निर्दिष्ट इमेज फ़ॉर्मेट में सहेजें |
| [Save](../../aspose.threed.render/texturedata/save/#save_2)(string, string) | टेक्सचर डेटा को इमेज फ़ाइल में सहेजें |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [TransformPixelFormat](../../aspose.threed.render/texturedata/transformpixelformat/)(PixelFormat) | पिक्सेल के लेआउट को नए पिक्सेल फ़ॉर्मेट में बदलें। |

### देखें भी

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


