---
title: "क्लास TransformedCurve"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.TransformedCurve क्लास। एक TransformedCurve एक ट्रांसफ़ॉर्मेशन मैट्रिक्स का उपयोग करके एक कर्व को प्लेसमेंट देता है। यह TrimmedCurve या CompositeCurve के भीतर ट्रांसफ़ॉर्मेशन करने की अनुमति देता है।"
type: docs
weight: 780
url: /hi/net/aspose.threed.entities/transformedcurve/
---
## TransformedCurve class

एक `TransformedCurve` ट्रांसफ़ॉर्मेशन मैट्रिक्स का उपयोग करके एक कर्व को प्लेसमेंट देता है। यह [`TrimmedCurve`](../trimmedcurve/) या [`CompositeCurve`](../compositecurve/) के भीतर ट्रांसफ़ॉर्मेशन करने की अनुमति देता है।

```csharp
public class TransformedCurve : Curve
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TransformedCurve](transformedcurve/#constructor)() | `TransformedCurve` का कंस्ट्रक्टर |
| [TransformedCurve](transformedcurve/#constructor_1)(Curve, Matrix4) | `TransformedCurve` का कंस्ट्रक्टर |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/transformedcurve/basiscurve/) { get; set; } | बेसिस कर्व। |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | लाइन का रंग प्राप्त या सेट करता है, डिफ़ॉल्ट मान सफेद (1, 1, 1) है। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [TransformMatrix](../../aspose.threed.entities/transformedcurve/transformmatrix/) { get; set; } | परिवर्तन मैट्रिक्स। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
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


