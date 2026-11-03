---
title: "क्लास Texture"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Shading.Texture क्लास। यह क्लास बाहरी फ़ाइल से टेक्सचर को परिभाषित करती है"
type: docs
weight: 2600
url: /hi/net/aspose.threed.shading/texture/
---
## Texture class

यह क्लास बाहरी फ़ाइल से टेक्सचर को परिभाषित करती है।

```csharp
public class Texture : TextureBase
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Texture](texture/#constructor)() | `Texture` क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [Texture](texture/#constructor_1)(string) | `Texture` क्लास का नया इंस्टेंस प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha/) { get; set; } | टेक्सचर का डिफ़ॉल्ट अल्फा मान प्राप्त करता है या सेट करता है। यह तब मान्य होता है जब [`AlphaSource`](../texturebase/alphasource/) PixelAlpha हो। डिफ़ॉल्ट मान 1.0 है, मान्य मान सीमा 0 से 1 के बीच है। |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource/) { get; set; } | टेक्सचर अल्फा चैनल को परिभाषित करता है या नहीं, इसे प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान None है। |
| [Content](../../aspose.threed.shading/texture/content/) { get; set; } | टेक्सचर की बाइनरी सामग्री को प्राप्त करता है या सेट करता है। एम्बेडेड टेक्सचर सामग्री वैकल्पिक है, यदि यह अनुपलब्ध है तो उपयोगकर्ता को टेक्सचर को बाहरी फ़ाइल से लोड करना चाहिए। |
| [EnableMipMap](../../aspose.threed.shading/texture/enablemipmap/) { get; set; } | इस टेक्सचर के लिए मिपमैप सक्षम है या नहीं, इसे प्राप्त करता है या सेट करता है। |
| [FileName](../../aspose.threed.shading/texture/filename/) { get; set; } | संबंधित टेक्सचर फ़ाइल को प्राप्त करता है या सेट करता है। |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter/) { get; set; } | वृद्धि के लिए फ़िल्टर को प्राप्त करता है या सेट करता है। |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter/) { get; set; } | मिनिफिकेशन के लिए फ़िल्टर प्राप्त करता है या सेट करता है। |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter/) { get; set; } | मिप-लेवल सैंपलिंग के लिए फ़िल्टर प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation/) { get; set; } | टेक्सचर का घूर्णन प्राप्त करता है या सेट करता है। |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale/) { get; set; } | UV स्केल प्राप्त करता है या सेट करता है। |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation/) { get; set; } | UV ट्रांसलेशन प्राप्त करता है या सेट करता है। |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu/) { get; set; } | U में टेक्सचर रैप मोड्स प्राप्त करता है या सेट करता है। |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev/) { get; set; } | V में टेक्सचर रैप मोड्स प्राप्त करता है या सेट करता है। |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew/) { get; set; } | W में टेक्सचर रैप मोड्स प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation/)(double, double) | UV घूर्णन सेट करता है। |
| [SetScale](../../aspose.threed.shading/texturebase/setscale/)(double, double) | UV स्केल सेट करता है। |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation/)(double, double) | UV ट्रांसलेशन सेट करता है। |

### देखें भी

* class [TextureBase](../texturebase/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


