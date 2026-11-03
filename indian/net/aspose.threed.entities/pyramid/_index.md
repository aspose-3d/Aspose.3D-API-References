---
title: "क्लास Pyramid"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.Pyramid क्लास। पैरामीटरयुक्त पिरामिड"
type: docs
weight: 650
url: /hi/net/aspose.threed.entities/pyramid/
---
## Pyramid class

पैरामीटरयुक्त पिरामिड।

```csharp
public class Pyramid : Primitive
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Pyramid](pyramid/#constructor)() | डिफ़ॉल्ट नीचे के क्षेत्र (10, 10) और डिफ़ॉल्ट ऊँचाई (5) के साथ एक नया पिरामिड इंस्टेंस बनाएं |
| [Pyramid](pyramid/#constructor_1)(double, double, double) | निर्दिष्ट नीचे के क्षेत्र के साथ एक नया पिरामिड इंस्टेंस बनाएं |
| [Pyramid](pyramid/#constructor_2)(double, double, double, double, double) | निर्दिष्ट नीचे के क्षेत्र, ऊपर के क्षेत्र और ऊँचाई के साथ एक नया पिरामिड इंस्टेंस बनाएं। |
| [Pyramid](pyramid/#constructor_3)(string, double, double, double, double, double) | निर्दिष्ट नीचे के क्षेत्र, ऊपर के क्षेत्र और ऊँचाई के साथ एक नया पिरामिड इंस्टेंस बनाएं। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BottomArea](../../aspose.threed.entities/pyramid/bottomarea/) { get; set; } | नीचे के कैप का क्षेत्रफल |
| [BottomOffset](../../aspose.threed.entities/pyramid/bottomoffset/) { get; set; } | नीचे के वर्टिसेज के लिए ऑफ़सेट |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह ज्योमेट्री शैडो कास्ट कर सकती है या नहीं |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| [Height](../../aspose.threed.entities/pyramid/height/) { get; set; } | पिरामिड की ऊँचाई |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [TopArea](../../aspose.threed.entities/pyramid/toparea/) { get; set; } | ऊपर के कैप का क्षेत्रफल |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| override [ToMesh](../../aspose.threed.entities/pyramid/tomesh/)() | वर्तमान ऑब्जेक्ट को मेष में परिवर्तित करें |

### देखें भी

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


