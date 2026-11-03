---
title: "क्लास NurbsCurve"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.NurbsCurve क्लास। NURBS कर्व एक कर्व है जो NURBSNonuniform रैशनल बेसिस स्प्लाइन द्वारा दर्शाया जाता है। एक NURBS कर्व को उसके ऑर्डर, भारित कंट्रोल पॉइंट्स का सेट और एक नॉट वेक्टर द्वारा परिभाषित किया जाता है। कंट्रोल पॉइंट में w घटक को कंट्रोल पॉइंट का वजन के रूप में उपयोग किया जाता है, चाहे वह दो‑आयामी हो या तीन‑आयामी।"
type: docs
weight: 520
url: /hi/net/aspose.threed.entities/nurbscurve/
---
## NurbsCurve class

[NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [`Order`](./order/), a set of weighted [`ControlPoints`](../geometry/controlpoints/) and a [`KnotVectors`](./knotvectors/) The w component in control point is used as control point's weight, whatever it is a TwoDimensional or ThreeDimensional

```csharp
public class NurbsCurve : Curve
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [NurbsCurve](nurbscurve/#constructor)() | `NurbsCurve` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [NurbsCurve](nurbscurve/#constructor_1)(string) | `NurbsCurve` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | लाइन का रंग प्राप्त या सेट करता है, डिफ़ॉल्ट मान सफेद (1, 1, 1) है। |
| [ControlPoints](../../aspose.threed.entities/nurbscurve/controlpoints/) { get; } | सभी कंट्रोल पॉइंट प्राप्त करता है |
| [CurveType](../../aspose.threed.entities/nurbscurve/curvetype/) { get; set; } | कर्व का प्रकार प्राप्त या सेट करता है। |
| [Degree](../../aspose.threed.entities/nurbscurve/degree/) { get; set; } | NURBS वक्र की डिग्री प्राप्त करता है या सेट करता है, डिग्री को Order - 1 के रूप में परिभाषित किया जाता है |
| [Dimension](../../aspose.threed.entities/nurbscurve/dimension/) { get; set; } | वक्र का आयाम प्राप्त करता है या सेट करता है। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| [KnotVectors](../../aspose.threed.entities/nurbscurve/knotvectors/) { get; } | नॉट वेक्टर प्राप्त करता है, यह पैरामीटर मानों की एक श्रृंखला है जो निर्धारित करती है कि नियंत्रण बिंदु NURBS वक्र को कहाँ और कैसे प्रभावित करते हैं। |
| [Multiplicity](../../aspose.threed.entities/nurbscurve/multiplicity/) { get; } | मल्टिप्लिसिटी प्राप्त करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Order](../../aspose.threed.entities/nurbscurve/order/) { get; set; } | NURBS वक्र का क्रम प्राप्त करता है या सेट करता है, यह वक्र पर किसी भी बिंदु को प्रभावित करने वाले निकटवर्ती नियंत्रण बिंदुओं की संख्या को परिभाषित करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Rational](../../aspose.threed.entities/nurbscurve/rational/) { get; set; } | यह निर्धारित करता है या सेट करता है कि यह रैशनल है या नहीं, यह मान दर्शाता है कि यह `NurbsCurve` रैशनल स्प्लाइन है या नॉन-रैशनल स्प्लाइन। नॉन-रैशनल B-स्प्लाइन रैशनल B-स्प्लाइनों का एक विशेष मामला है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Evaluate](../../aspose.threed.entities/nurbscurve/evaluate/)(int) | NURBS वक्र का मूल्यांकन करें |
| [EvaluateAt](../../aspose.threed.entities/nurbscurve/evaluateat/)(double) | निर्दिष्ट स्थिति पर वक्र के बिंदु का मूल्यांकन करें |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

### देखें भी

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


