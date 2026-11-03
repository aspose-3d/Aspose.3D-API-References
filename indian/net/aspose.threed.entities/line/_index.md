---
title: "क्लास Line"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.Line क्लास। एक पॉलीलाइन बिंदुओं के सेट के साथ ControlPoints द्वारा परिभाषित पाथ है और Segments द्वारा जुड़ा होता है, जिसका अर्थ है कि यह जुड़े हुए लाइन सेगमेंट्स का सेट भी हो सकता है। लाइन आमतौर पर एक रैखिक वस्तु होती है, जिसका अर्थ है कि इसे कर्व प्रतिनिधित्व करने के लिए उपयोग नहीं किया जा सकता; कर्व को प्रतिनिधित्व करने के लिए NurbsCurve का उपयोग किया जाता है।"
type: docs
weight: 480
url: /hi/net/aspose.threed.entities/line/
---
## Line class

एक पॉलीलाइन बिंदुओं के सेट के साथ [`ControlPoints`](../geometry/controlpoints/) द्वारा परिभाषित पाथ है, और [`Segments`](./segments/) द्वारा जुड़ी होती है, जिसका अर्थ है कि यह जुड़े हुए लाइन सेगमेंट्स का सेट भी हो सकता है। लाइन आमतौर पर एक रैखिक वस्तु होती है, जिसका अर्थ है कि इसे कर्व प्रतिनिधित्व करने के लिए उपयोग नहीं किया जा सकता; कर्व को प्रतिनिधित्व करने के लिए [`NurbsCurve`](../nurbscurve/) का उपयोग किया जाता है।

```csharp
public class Line : Curve
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Line](line/#constructor)() | `Line` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Line](line/#constructor_1)(string) | `Line` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | लाइन का रंग प्राप्त या सेट करता है, डिफ़ॉल्ट मान सफेद (1, 1, 1) है। |
| [ControlPoints](../../aspose.threed.entities/line/controlpoints/) { get; } | सभी कंट्रोल पॉइंट प्राप्त करता है |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [Segments](../../aspose.threed.entities/line/segments/) { get; } | लाइन के सेगमेंट्स को प्राप्त करता है। |
| [Visible](../../aspose.threed.entities/line/visible/) { get; set; } | प्राप्त करता है या सेट करता है कि जियोमेट्री दृश्यमान है या नहीं |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromPoints](../../aspose.threed.entities/line/frompoints/)(params Vector3[]) | एक सेट बिंदुओं से `Line` इंस्टेंस बनाएं। |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [MakeDefaultIndices](../../aspose.threed.entities/line/makedefaultindices/)() | क्रम 0,1,2,3....[`ControlPoints`](../geometry/controlpoints/).Length-1 से [`Segments`](./segments/) तक उत्पन्न करें ताकि ControlPoints को एकल रेखा के रूप में उपयोग किया जा सके। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

### देखें भी

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


