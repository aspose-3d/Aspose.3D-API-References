---
title: Ellipse
second_title: .NET API संदर्भ के लिए Aspose.3D
description: एकEllipse./ellipse/बंदु के एक सेट क परभषत करत है ज दर्घवृत्त क आकर बनत है
type: docs
weight: 330
url: /hi/net/aspose.threed.entities/ellipse/
---
## Ellipse class

एक`Ellipse`बिंदु के एक सेट को परिभाषित करता है जो दीर्घवृत्त का आकार बनाता है।

```csharp
public class Ellipse : Curve
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Ellipse](ellipse/#constructor)() | का निर्माता`Ellipse` |
| [Ellipse](ellipse/#constructor_1)(double, double) | का निर्माता`Ellipse` |

## गुण

| नाम | विवरण |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | रेखा का रंग प्राप्त या सेट करता है, डिफ़ॉल्ट मान सफेद है (1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | हो जाता है या सेट करता है कि निर्यात के दौरान इस इकाई को बाहर करना है या नहीं। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम प्राप्त या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहले पैरेंट नोड को प्राप्त या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह इकाई अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, ज्यामिति इंस्टेंसिंग के लिए एक इकाई को कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी संपत्तियों का संग्रह प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | दृश्य प्राप्त करता है कि यह वस्तु से संबंधित है |
| [SemiAxis1](../../aspose.threed.entities/ellipse/semiaxis1/) { get; set; } | X-अक्ष पर त्रिज्या |
| [SemiAxis2](../../aspose.threed.entities/ellipse/semiaxis2/) { get; set; } | वाई-अक्ष पर त्रिज्या |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | संपत्ति ढूँढता है। यह एक गतिशील संपत्ति हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल संपत्ति (इसके नाम से पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | अपने ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में वर्तमान इकाई का बाउंडिंग बॉक्स प्राप्त करता है। |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | रेंडरर में पंजीकृत इकाई रेंडरर की कुंजी प्राप्त करता है |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट संपत्ति का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक गतिशील संपत्ति को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट संपत्ति को हटाएं |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट संपत्ति का मान सेट करता है |

### यह सभी देखें

* class [Curve](../curve/)
* नाम स्थान [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* सभा [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
