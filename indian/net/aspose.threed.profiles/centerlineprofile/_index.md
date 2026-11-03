---
title: "क्लास CenterLineProfile"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Profiles.CenterLineProfile क्लास। IFC संगत सेंटर लाइन प्रोफ़ाइल"
type: docs
weight: 1690
url: /hi/net/aspose.threed.profiles/centerlineprofile/
---
## CenterLineProfile class

IFC संगत सेंटर लाइन प्रोफ़ाइल

```csharp
public class CenterLineProfile : Profile
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [CenterLineProfile](centerlineprofile/)(Curve, double) | निर्दिष्ट कर्व को सेंटर लाइन के रूप में उपयोग करके नया `CenterLineProfile` बनाता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Curve](../../aspose.threed.profiles/centerlineprofile/curve/) { get; set; } | प्रोफ़ाइल की सेंटर लाइन कर्व |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [Thickness](../../aspose.threed.profiles/centerlineprofile/thickness/) { get; set; } | सेंटर लाइन के साथ लागू मोटाई |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

### देखें भी

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


