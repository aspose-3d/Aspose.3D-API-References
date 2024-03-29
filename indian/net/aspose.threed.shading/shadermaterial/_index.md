---
title: ShaderMaterial
second_title: .NET API संदर्भ के लिए Aspose.3D
description: एक शेडर समग्र बहर रेंडरंग इंजन य शेडर भष द्वर समग्र क वर्णन करने क अनुमत देत है ShaderMaterial./shadermaterial/ उपयगShaderTechnique./shadertechnique/ ठस प्रतपदन ववरण क वर्णन करने के लए और अंतम प्रतपदन मंच के अनुसर सबसे उपयुक्त क उपयग कय जएग उदहरण के लए आपकShaderMaterial./shadermaterial/ उदहरण में द तकनकें ह सकत हैं एक एचएलएसएल द्वर परभषत है और दूसर जएलएसएल द्वर परभषत है गैरवंड प्लेटफर्म के तहत एचएलएसएल के बजय जएलएसएल क उपयग कय जन चहए
type: docs
weight: 2330
url: /hi/net/aspose.threed.shading/shadermaterial/
---
## ShaderMaterial class

एक शेडर सामग्री बाहरी रेंडरिंग इंजन या शेडर भाषा द्वारा सामग्री का वर्णन करने की अनुमति देती है। `ShaderMaterial` उपयोग[`ShaderTechnique`](../shadertechnique/) ठोस प्रतिपादन विवरण का वर्णन करने के लिए, और अंतिम प्रतिपादन मंच के अनुसार सबसे उपयुक्त का उपयोग किया जाएगा। उदाहरण के लिए, आपका`ShaderMaterial` उदाहरण में दो तकनीकें हो सकती हैं, एक एचएलएसएल द्वारा परिभाषित है, और दूसरी जीएलएसएल द्वारा परिभाषित है गैर-विंडो प्लेटफॉर्म के तहत एचएलएसएल के बजाय जीएलएसएल का उपयोग किया जाना चाहिए

```csharp
public class ShaderMaterial : Material
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ShaderMaterial](shadermaterial/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`ShaderMaterial` वर्ग. |
| [ShaderMaterial](shadermaterial/#constructor_1)(string) | का एक नया उदाहरण प्रारंभ करता है`ShaderMaterial` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम प्राप्त या सेट करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी संपत्तियों का संग्रह प्राप्त करता है। |
| [Techniques](../../aspose.threed.shading/shadermaterial/techniques/) { get; } | इस सामग्री में परिभाषित सभी उपलब्ध तकनीकों को प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | संपत्ति ढूँढता है। यह एक गतिशील संपत्ति हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल संपत्ति (इसके नाम से पहचानी गई) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | गणनाकर्ता को आंतरिक बनावट स्लॉट की गणना करने के लिए मिलता है। |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट संपत्ति का मान प्राप्त करें |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | निर्दिष्ट स्लॉट से बनावट प्राप्त करता है, यह सामग्री की संपत्ति का नाम या शेडर का पैरामीटर नाम हो सकता है |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक गतिशील संपत्ति को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट संपत्ति को हटाएं |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट संपत्ति का मान सेट करता है |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | बनावट को निर्दिष्ट स्लॉट पर सेट करता है |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | ऑब्जेक्ट को string पर स्वरूपित करता है |

### यह सभी देखें

* class [Material](../material/)
* नाम स्थान [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* सभा [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
