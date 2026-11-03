---
title: "क्लास LShape"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Profiles.LShape क्लास। पैरामीटर द्वारा परिभाषित IFC संगत Lshape प्रोफ़ाइल"
type: docs
weight: 1760
url: /hi/net/aspose.threed.profiles/lshape/
---
## LShape class

IFC संगत L-आकार प्रोफ़ाइल जो पैरामीटरों द्वारा परिभाषित है।

```csharp
public class LShape : ParameterizedProfile
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LShape](lshape/)() | `LShape` का कन्स्ट्रक्टर |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Depth](../../aspose.threed.profiles/lshape/depth/) { get; set; } | प्रोफ़ाइल की गहराई को प्राप्त करता है या सेट करता है। |
| [EdgeRadius](../../aspose.threed.profiles/lshape/edgeradius/) { get; set; } | एज की त्रिज्या प्राप्त करता है या सेट करता है। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| [FilletRadius](../../aspose.threed.profiles/lshape/filletradius/) { get; set; } | फ़िलेट की त्रिज्या प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [Thickness](../../aspose.threed.profiles/lshape/thickness/) { get; set; } | स्थिर दीवार की मोटाई प्राप्त करता है या सेट करता है। |
| [Width](../../aspose.threed.profiles/lshape/width/) { get; set; } | प्रोफ़ाइल की चौड़ाई को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| override [GetExtent](../../aspose.threed.profiles/lshape/getextent/)() | x और y आयाम में विस्तार प्राप्त करता है। |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

### देखें भी

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


