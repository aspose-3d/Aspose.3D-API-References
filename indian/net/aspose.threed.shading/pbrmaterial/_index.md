---
title: "क्लास PbrMaterial"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Shading.PbrMaterial क्लास। अल्बीडो रंग/धातुता/रफ़नेस पर आधारित फिज़िकली बेस्ड रेंडरिंग के लिए सामग्री।"
type: docs
weight: 2550
url: /hi/net/aspose.threed.shading/pbrmaterial/
---
## PbrMaterial class

अल्बीडो रंग/धातु/रफ़नेस पर आधारित फिज़िकली बेस्ड रेंडरिंग के लिए मैटेरियल

```csharp
public class PbrMaterial : Material
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PbrMaterial](pbrmaterial/#constructor)() | डिफ़ॉल्ट PBR सामग्री इंस्टेंस बनाएं |
| [PbrMaterial](pbrmaterial/#constructor_1)(Vector3) | निर्दिष्ट अल्बीडो रंग मान के साथ डिफ़ॉल्ट PBR सामग्री बनाएं। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Albedo](../../aspose.threed.shading/pbrmaterial/albedo/) { get; set; } | सामग्री का बेस रंग प्राप्त करता है या सेट करता है |
| [AlbedoTexture](../../aspose.threed.shading/pbrmaterial/albedotexture/) { get; set; } | अल्बीडो के लिए टेक्सचर प्राप्त करता है या सेट करता है |
| [EmissiveColor](../../aspose.threed.shading/pbrmaterial/emissivecolor/) { get; set; } | एमिसिव रंग प्राप्त करता है या सेट करता है |
| [EmissiveTexture](../../aspose.threed.shading/pbrmaterial/emissivetexture/) { get; set; } | एमिसिव के लिए टेक्सचर प्राप्त करता है या सेट करता है |
| [MetallicFactor](../../aspose.threed.shading/pbrmaterial/metallicfactor/) { get; set; } | सामग्री की धातुता प्राप्त करता है या सेट करता है, 1 का मान मतलब सामग्री धातु है और 0 का मान मतलब सामग्री डाइइलेक्ट्रिक है। |
| [MetallicRoughness](../../aspose.threed.shading/pbrmaterial/metallicroughness/) { get; set; } | धातुता (R चैनल में) और रफ़नेस (G चैनल में) के लिए टेक्सचर प्राप्त करता है या सेट करता है |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [NormalTexture](../../aspose.threed.shading/pbrmaterial/normaltexture/) { get; set; } | नॉर्मल मैपिंग का टेक्सचर प्राप्त करता है या सेट करता है |
| [OcclusionFactor](../../aspose.threed.shading/pbrmaterial/occlusionfactor/) { get; set; } | ऐम्बिएंट ऑक्लूज़न का फैक्टर प्राप्त करता है या सेट करता है |
| [OcclusionTexture](../../aspose.threed.shading/pbrmaterial/occlusiontexture/) { get; set; } | ऐम्बिएंट ऑक्लूज़न के लिए टेक्सचर प्राप्त करता है या सेट करता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [RoughnessFactor](../../aspose.threed.shading/pbrmaterial/roughnessfactor/) { get; set; } | सामग्री की रफ़नेस प्राप्त करता है या सेट करता है, 1 का मान मतलब सामग्री पूरी तरह रफ़ है और 0 का मान मतलब सामग्री पूरी तरह स्मूद है। |
| [SpecularTexture](../../aspose.threed.shading/pbrmaterial/speculartexture/) { get; set; } | स्पेक्यूलर रंग के लिए टेक्सचर प्राप्त करता है या सेट करता है |
| [Transparency](../../aspose.threed.shading/pbrmaterial/transparency/) { get; set; } | ट्रांसपेरेंसी फैक्टर प्राप्त करता है या सेट करता है। फैक्टर 0 (0%, पूरी तरह अपारदर्शी) से 1 (100%, पूरी तरह पारदर्शी) के बीच होना चाहिए। कोई भी अमान्य फैक्टर वैल्यू को क्लैंप किया जाएगा। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromMaterial](../../aspose.threed.shading/pbrmaterial/frommaterial/)(Material) | अन्य सामग्री को PbrMaterial में परिवर्तित करने की अनुमति दें |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | आंतरिक टेक्सचर स्लॉट्स को सूचीबद्ध करने के लिए एनेमरेटर प्राप्त करता है। |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | निर्दिष्ट स्लॉट से टेक्सचर प्राप्त करता है, यह मैटेरियल की प्रॉपर्टी नाम या शेडर के पैरामीटर नाम हो सकता है |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | टेक्सचर को निर्दिष्ट स्लॉट में सेट करता है |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | ऑब्जेक्ट को स्ट्रिंग में फॉर्मेट करता है |

### देखें भी

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


