---
title: "क्लास Material"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Shading.Material क्लास। सामग्री जियोमेट्री की दृश्य उपस्थिति के लिए आवश्यक पैरामीटर निर्धारित करती है। Aspose.3D लैम्बर्टमैटेरियल, PhongMaterial और ShaderMaterial के लिए शेडिंग मॉडल प्रदान करता है।"
type: docs
weight: 2540
url: /hi/net/aspose.threed.shading/material/
---
## Material class

सामग्री जियोमेट्री की दृश्य उपस्थिति के लिए आवश्यक पैरामीटर निर्धारित करती है। Aspose.3D [`LambertMaterial`](../lambertmaterial/), [`PhongMaterial`](../phongmaterial/) और [`ShaderMaterial`](../shadermaterial/) के लिए शेडिंग मॉडल प्रदान करता है।

```csharp
public abstract class Material : A3DObject, IEnumerable<TextureSlot>
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |

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
| const [MapAmbient](../../aspose.threed.shading/material/mapambient/) | [`SetTexture`](./settexture/) में उपयोग किया जाता है ताकि एक एम्बिएंट टेक्सचर मैपिंग असाइन की जा सके। |
| const [MapDiffuse](../../aspose.threed.shading/material/mapdiffuse/) | [`SetTexture`](./settexture/) में उपयोग किया जाता है ताकि एक डिफ्यूज़ टेक्सचर मैपिंग असाइन किया जा सके। |
| const [MapEmissive](../../aspose.threed.shading/material/mapemissive/) | [`SetTexture`](./settexture/) में उपयोग किया जाता है ताकि एक इमिसिव टेक्सचर मैपिंग असाइन किया जा सके। |
| const [MapNormal](../../aspose.threed.shading/material/mapnormal/) | [`SetTexture`](./settexture/) में उपयोग किया जाता है ताकि एक नॉर्मल टेक्सचर मैपिंग असाइन किया जा सके। |
| const [MapSpecular](../../aspose.threed.shading/material/mapspecular/) | [`SetTexture`](./settexture/) में उपयोग किया जाता है ताकि एक स्पेक्यूलर टेक्सचर मैपिंग असाइन किया जा सके। |

## उदाहरण

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
foreach(var slot in mat)
{
    Console.WriteLine($"Texture slot {slot.SlotName} = {slot.Texture}");
}
```

### देखें भी

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [TextureSlot](../textureslot/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


