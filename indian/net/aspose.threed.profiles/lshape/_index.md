---
title: LShape
second_title: .NET API संदर्भ के लिए Aspose.3D
description: IFC संगत Lआकर प्रफ़इल ज पैरमटर द्वर परभषत है
type: docs
weight: 1580
url: /hi/net/aspose.threed.profiles/lshape/
---
## LShape class

IFC संगत L-आकार प्रोफ़ाइल जो पैरामीटर द्वारा परिभाषित है।

```csharp
public class LShape : ParameterizedProfile
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LShape](lshape/)() | का निर्माता`LShape` |

## गुण

| नाम | विवरण |
| --- | --- |
| [Depth](../../aspose.threed.profiles/lshape/depth/) { get; set; } | प्रोफाइल की गहराई प्राप्त या सेट करता है। |
| [EdgeRadius](../../aspose.threed.profiles/lshape/edgeradius/) { get; set; } | किनारे की त्रिज्या प्राप्त या सेट करता है। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | हो जाता है या सेट करता है कि निर्यात के दौरान इस इकाई को बाहर करना है या नहीं। |
| [FilletRadius](../../aspose.threed.profiles/lshape/filletradius/) { get; set; } | पट्टिका की त्रिज्या प्राप्त या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम प्राप्त या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहले पैरेंट नोड को प्राप्त या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह इकाई अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, ज्यामिति इंस्टेंसिंग के लिए एक इकाई को कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी संपत्तियों का संग्रह प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | दृश्य प्राप्त करता है कि यह वस्तु से संबंधित है |
| [Thickness](../../aspose.threed.profiles/lshape/thickness/) { get; set; } | स्थिर दीवार की मोटाई प्राप्त या सेट करता है। |
| [Width](../../aspose.threed.profiles/lshape/width/) { get; set; } | प्रोफाइल की चौड़ाई प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | संपत्ति ढूँढता है। यह एक गतिशील संपत्ति हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल संपत्ति (इसके नाम से पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | अपने ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में वर्तमान इकाई का बाउंडिंग बॉक्स प्राप्त करता है। |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | रेंडरर में पंजीकृत इकाई रेंडरर की कुंजी प्राप्त करता है |
| override [GetExtent](../../aspose.threed.profiles/lshape/getextent/)() | एक्स और वाई आयाम में सीमा प्राप्त करता है। |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट संपत्ति का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक गतिशील संपत्ति को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट संपत्ति को हटाएं |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट संपत्ति का मान सेट करता है |

### यह सभी देखें

* class [ParameterizedProfile](../parameterizedprofile/)
* नाम स्थान [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* सभा [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->