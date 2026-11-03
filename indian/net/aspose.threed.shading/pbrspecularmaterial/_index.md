---
title: "क्लास PbrSpecularMaterial"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Shading.PbrSpecularMaterial class. डिफ्यूज़ रंग/स्पेक्यूलर/ग्लॉसिनेस पर आधारित फिज़िकली बेस्ड रेंडरिंग के लिए सामग्री"
type: docs
weight: 2560
url: /hi/net/aspose.threed.shading/pbrspecularmaterial/
---
## PbrSpecularMaterial class

डिफ्यूज़ रंग/स्पेक्यूलर/ग्लॉसिनेस पर आधारित फिज़िकली बेस्ड रेंडरिंग के लिए मैटेरियल

```csharp
public class PbrSpecularMaterial : Material
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PbrSpecularMaterial](pbrspecularmaterial/)() | `PbrSpecularMaterial` का कंस्ट्रक्टर |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Diffuse](../../aspose.threed.shading/pbrspecularmaterial/diffuse/) { get; set; } | सामग्री का डिफ्यूज़ रंग प्राप्त करता है या सेट करता है, डिफ़ॉल्ट मान (1, 1, 1) है। |
| [DiffuseTexture](../../aspose.threed.shading/pbrspecularmaterial/diffusetexture/) { get; set; } | डिफ्यूज़ के लिए टेक्सचर प्राप्त करता है या सेट करता है |
| [EmissiveColor](../../aspose.threed.shading/pbrspecularmaterial/emissivecolor/) { get; set; } | एमिसिव रंग प्राप्त करता है या सेट करता है, डिफ़ॉल्ट मान (0, 0, 0) है |
| [EmissiveTexture](../../aspose.threed.shading/pbrspecularmaterial/emissivetexture/) { get; set; } | एमिसिव के लिए टेक्सचर प्राप्त करता है या सेट करता है |
| [GlossinessFactor](../../aspose.threed.shading/pbrspecularmaterial/glossinessfactor/) { get; set; } | सामग्री की चमक (स्मूदनेस) प्राप्त करता है या सेट करता है, 1 का मतलब पूरी तरह स्मूद और 0 का मतलब पूरी तरह रफ़ है, डिफ़ॉल्ट मान 1 है, सीमा [0, 1] है |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [NormalTexture](../../aspose.threed.shading/pbrspecularmaterial/normaltexture/) { get; set; } | नॉर्मल मैपिंग का टेक्सचर प्राप्त करता है या सेट करता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Specular](../../aspose.threed.shading/pbrspecularmaterial/specular/) { get; set; } | सामग्री के स्पेक्युलर रंग को प्राप्त करता है या सेट करता है, डिफ़ॉल्ट मान (1, 1, 1) है। |
| [SpecularGlossinessTexture](../../aspose.threed.shading/pbrspecularmaterial/specularglossinesstexture/) { get; set; } | स्पेक्युलर रंग के लिए टेक्सचर प्राप्त करता है या सेट करता है, चैनल RGB स्पेक्युलर रंग संग्रहीत करता है और चैनल A चमक (ग्लॉसिनेस) संग्रहीत करता है। |
| [Transparency](../../aspose.threed.shading/pbrspecularmaterial/transparency/) { get; set; } | ट्रांसपेरेंसी फैक्टर प्राप्त करता है या सेट करता है। फैक्टर 0 (0%, पूरी तरह अपारदर्शी) से 1 (100%, पूरी तरह पारदर्शी) के बीच होना चाहिए। कोई भी अमान्य फैक्टर वैल्यू को क्लैंप किया जाएगा। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | आंतरिक टेक्सचर स्लॉट्स को सूचीबद्ध करने के लिए एनेमरेटर प्राप्त करता है। |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | निर्दिष्ट स्लॉट से टेक्सचर प्राप्त करता है, यह मैटेरियल की प्रॉपर्टी नाम या शेडर के पैरामीटर नाम हो सकता है |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | टेक्सचर को निर्दिष्ट स्लॉट में सेट करता है |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | ऑब्जेक्ट को स्ट्रिंग में फॉर्मेट करता है |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [MapSpecularGlossiness](../../aspose.threed.shading/pbrspecularmaterial/mapspecularglossiness/) | स्पेक्युलर चमक के लिए टेक्सचर मैप |

### देखें भी

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


