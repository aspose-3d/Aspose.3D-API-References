---
title: "क्लास LambertMaterial"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Shading.LambertMaterial क्लास। लैम्बर्ट शेडिंग मॉडल के लिए मैटेरियल"
type: docs
weight: 2530
url: /hi/net/aspose.threed.shading/lambertmaterial/
---
## LambertMaterial class

लैम्बर्ट शेडिंग मॉडल के लिए मैटेरियल

```csharp
public class LambertMaterial : Material
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LambertMaterial](lambertmaterial/#constructor)() | `LambertMaterial` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LambertMaterial](lambertmaterial/#constructor_1)(string) | `LambertMaterial` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor/) { get; set; } | एम्बिएंट रंग प्राप्त करता है या सेट करता है |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor/) { get; set; } | डिफ्यूज़ रंग प्राप्त करता है या सेट करता है |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor/) { get; set; } | एमिसिव रंग प्राप्त करता है या सेट करता है |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency/) { get; set; } | ट्रांसपेरेंसी फैक्टर प्राप्त करता है या सेट करता है। फैक्टर 0 (0%, पूरी तरह अपारदर्शी) से 1 (100%, पूरी तरह पारदर्शी) के बीच होना चाहिए। कोई भी अमान्य फैक्टर वैल्यू को क्लैंप किया जाएगा। |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor/) { get; set; } | ट्रांसपेरेंट रंग प्राप्त करता है या सेट करता है। |

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

### देखें भी

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


