---
title: "क्लास Plane"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.Plane क्लास। पैरामीटरयुक्त प्लेन"
type: docs
weight: 590
url: /hi/net/aspose.threed.entities/plane/
---
## Plane class

पैरामीटरयुक्त तल।

```csharp
public class Plane : Primitive
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Plane](plane/#constructor)() | `Plane` का नया उदाहरण डिफ़ॉल्ट आकार 1x1 के साथ प्रारंभ करता है। |
| [Plane](plane/#constructor_1)(double, double) | `Plane` का नया उदाहरण प्रारंभ करता है। |
| [Plane](plane/#constructor_2)(string, double, double, int, int) | `Plane` का नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह ज्योमेट्री शैडो कास्ट कर सकती है या नहीं |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| [Length](../../aspose.threed.entities/plane/length/) { get; set; } | प्लेन की लंबाई प्राप्त करता है या सेट करता है। |
| [LengthSegments](../../aspose.threed.entities/plane/lengthsegments/) { get; set; } | लंबाई सेगमेंट प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [Up](../../aspose.threed.entities/plane/up/) { get; set; } | प्लेन का अप वेक्टर प्राप्त करता है या सेट करता है, डिफ़ॉल्ट मान (0, 1, 0) है, यह प्लेन के निर्माण को प्रभावित करता है |
| [Width](../../aspose.threed.entities/plane/width/) { get; set; } | प्लेन की चौड़ाई प्राप्त करता है या सेट करता है। |
| [WidthSegments](../../aspose.threed.entities/plane/widthsegments/) { get; set; } | चौड़ाई सेगमेंट प्राप्त करता है या सेट करता है। |

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
| override [ToMesh](../../aspose.threed.entities/plane/tomesh/)() | वर्तमान ऑब्जेक्ट को मेष में परिवर्तित करें |

### देखें भी

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


