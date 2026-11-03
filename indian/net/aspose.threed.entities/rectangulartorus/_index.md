---
title: "क्लास RectangularTorus"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.RectangularTorus क्लास। पैरामीटरयुक्त आयताकार टॉरस"
type: docs
weight: 660
url: /hi/net/aspose.threed.entities/rectangulartorus/
---
## RectangularTorus class

पैरामीटरयुक्त आयताकार टॉरस।

```csharp
public class RectangularTorus : Primitive
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [RectangularTorus](rectangulartorus/#constructor)() | `RectangularTorus` का कंस्ट्रक्टर |
| [RectangularTorus](rectangulartorus/#constructor_1)(string) | `RectangularTorus` का कंस्ट्रक्टर |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AngleStart](../../aspose.threed.entities/rectangulartorus/anglestart/) { get; set; } | आर्क का प्रारंभिक कोण, रेडियन में मापा गया। डिफ़ॉल्ट मान 0 है। |
| [Arc](../../aspose.threed.entities/rectangulartorus/arc/) { get; set; } | आर्क का कुल कोण, रेडियन में मापा गया। डिफ़ॉल्ट मान PI है। |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह ज्योमेट्री शैडो कास्ट कर सकती है या नहीं |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| [Height](../../aspose.threed.entities/rectangulartorus/height/) { get; set; } | आयताकार टॉरस की ऊँचाई। डिफ़ॉल्ट मान 20 है। |
| [InnerRadius](../../aspose.threed.entities/rectangulartorus/innerradius/) { get; set; } | आयताकार टॉरस का आंतरिक त्रिज्या। डिफ़ॉल्ट मान 17 है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [OuterRadius](../../aspose.threed.entities/rectangulartorus/outerradius/) { get; set; } | आयताकार टॉरस का बाहरी त्रिज्या। डिफ़ॉल्ट मान 20 है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [RadialSegments](../../aspose.threed.entities/rectangulartorus/radialsegments/) { get; set; } | रेडियल सेगमेंट्स, डिफ़ॉल्ट मान 10 है। |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |

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
| override [ToMesh](../../aspose.threed.entities/rectangulartorus/tomesh/)() | इस प्रिमिटिव को [`Mesh`](../mesh/) में बदलें |

### देखें भी

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


