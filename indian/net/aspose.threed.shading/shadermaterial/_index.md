---
title: "क्लास ShaderMaterial"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Shading.ShaderMaterial क्लास। एक शेडर मैटेरियल बाहरी रेंडरिंग इंजन या शेडर भाषा द्वारा सामग्री का वर्णन करने की अनुमति देता है। ShaderMaterial ShaderTechnique का उपयोग करके ठोस रेंडरिंग विवरण वर्णित करता है और सबसे उपयुक्त को अंतिम रेंडरिंग प्लेटफ़ॉर्म के अनुसार उपयोग किया जाएगा। उदाहरण के लिए, आपका ShaderMaterial इंस्टेंस दो तकनीकों रख सकता है, एक HLSL द्वारा परिभाषित और दूसरा GLSL द्वारा परिभाषित। गैर-विंडो प्लेटफ़ॉर्म पर GLSL को HLSL के बजाय उपयोग किया जाना चाहिए।"
type: docs
weight: 2580
url: /hi/net/aspose.threed.shading/shadermaterial/
---
## ShaderMaterial class

एक शेडर मैटेरियल बाहरी रेंडरिंग इंजन या शेडर भाषा द्वारा सामग्री का वर्णन करने की अनुमति देता है। `ShaderMaterial` [`ShaderTechnique`](../shadertechnique/) का उपयोग करके ठोस रेंडरिंग विवरण वर्णित करता है, और सबसे उपयुक्त को अंतिम रेंडरिंग प्लेटफ़ॉर्म के अनुसार उपयोग किया जाएगा। उदाहरण के लिए, आपका `ShaderMaterial` इंस्टेंस दो तकनीकों रख सकता है, एक HLSL द्वारा परिभाषित और दूसरा GLSL द्वारा परिभाषित। गैर-विंडो प्लेटफ़ॉर्म पर GLSL को HLSL के बजाय उपयोग किया जाना चाहिए।

```csharp
public class ShaderMaterial : Material
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ShaderMaterial](shadermaterial/#constructor)() | `ShaderMaterial` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [ShaderMaterial](shadermaterial/#constructor_1)(string) | `ShaderMaterial` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Techniques](../../aspose.threed.shading/shadermaterial/techniques/) { get; } | इस सामग्री में परिभाषित सभी उपलब्ध तकनीकों को प्राप्त करता है। |

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


