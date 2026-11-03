---
title: "क्लास Cylinder"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.Cylinder क्लास। पैरामीटरयुक्त सिलेंडर। जब radiusTop या radiusBottom में से कोई एक शून्य हो तो इसे शंकु के रूप में भी उपयोग किया जा सकता है।"
type: docs
weight: 360
url: /hi/net/aspose.threed.entities/cylinder/
---
## Cylinder class

पैरामीटरयुक्त सिलिंडर। जब radiusTop या radiusBottom में से कोई एक शून्य हो तो इसे शंकु के रूप में भी उपयोग किया जा सकता है।

```csharp
public class Cylinder : Primitive
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Cylinder](cylinder/#constructor)() | `Cylinder` क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [Cylinder](cylinder/#constructor_1)(double, double) | `Cylinder` क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [Cylinder](cylinder/#constructor_2)(double, double, double) | `Cylinder` क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [Cylinder](cylinder/#constructor_3)(double, double, double, int, int, bool) | `Cylinder` क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [Cylinder](cylinder/#constructor_4)(string, double, double, double, int, int, bool, double, double) | `Cylinder` क्लास का एक नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह ज्योमेट्री शैडो कास्ट कर सकती है या नहीं |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| [GenerateFanCylinder](../../aspose.threed.entities/cylinder/generatefancylinder/) { get; set; } | ThetaLength 2*PI से कम होने पर फैन-स्टाइल सिलेंडर उत्पन्न करना है या नहीं, इसे प्राप्त करता है या सेट करता है; अन्यथा मॉडल नहीं कटेगा। |
| [Height](../../aspose.threed.entities/cylinder/height/) { get; set; } | सिलेंडर की ऊँचाई को प्राप्त करता है या सेट करता है। |
| [HeightSegments](../../aspose.threed.entities/cylinder/heightsegments/) { get; set; } | ऊँचाई सेगमेंट को प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [OffsetBottom](../../aspose.threed.entities/cylinder/offsetbottom/) { get; set; } | निचली तरफ के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट को प्राप्त करता है या सेट करता है। |
| [OffsetTop](../../aspose.threed.entities/cylinder/offsettop/) { get; set; } | ऊपरी तरफ के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट को प्राप्त करता है या सेट करता है। |
| [OpenEnded](../../aspose.threed.entities/cylinder/openended/) { get; set; } | इस `Cylinder` का खुला अंत है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान false है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [RadialSegments](../../aspose.threed.entities/cylinder/radialsegments/) { get; set; } | रेडियल सेगमेंट्स को प्राप्त करता है या सेट करता है। |
| [RadiusBottom](../../aspose.threed.entities/cylinder/radiusbottom/) { get; set; } | सिलिंडर के नीचे के कैप का त्रिज्या प्राप्त करता है या सेट करता है। |
| [RadiusTop](../../aspose.threed.entities/cylinder/radiustop/) { get; set; } | सिलिंडर के ऊपर के कैप का त्रिज्या प्राप्त करता है या सेट करता है। |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [ShearBottom](../../aspose.threed.entities/cylinder/shearbottom/) { get; set; } | नीचे की तरफ़ के शीयर ट्रांसफ़ॉर्म को प्राप्त करता है या सेट करता है, वेक्टर (x-अक्ष, z-अक्ष) शीयर मान को रेडियन में संग्रहीत करता है, डिफ़ॉल्ट मान (0, 0) है। |
| [ShearTop](../../aspose.threed.entities/cylinder/sheartop/) { get; set; } | ऊपर की तरफ़ के शीयर ट्रांसफ़ॉर्म को प्राप्त करता है या सेट करता है, वेक्टर (x-अक्ष, z-अक्ष) शीयर मान को रेडियन में संग्रहीत करता है, डिफ़ॉल्ट मान (0, 0) है। |
| [ThetaLength](../../aspose.threed.entities/cylinder/thetalength/) { get; set; } | थीटा की लंबाई को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 2π है। |
| [ThetaStart](../../aspose.threed.entities/cylinder/thetastart/) { get; set; } | थीटा की शुरुआत को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 0 है। |

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
| override [ToMesh](../../aspose.threed.entities/cylinder/tomesh/)() | वर्तमान ऑब्जेक्ट को मेष में परिवर्तित करें |

### देखें भी

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


