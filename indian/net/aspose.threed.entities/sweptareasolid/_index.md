---
title: "क्लास SweptAreaSolid"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.SweptAreaSolid क्लास। एक SweptAreaSolid प्रोफ़ाइल को डायरेक्ट्रिक्स के साथ स्वीप करके ज्यामिति बनाता है।"
type: docs
weight: 750
url: /hi/net/aspose.threed.entities/sweptareasolid/
---
## SweptAreaSolid class

एक `SweptAreaSolid` प्रोफ़ाइल को डायरेक्ट्रिक्स के साथ स्विप करके एक ज्यामिति बनाता है।

```csharp
public class SweptAreaSolid : Entity, IMeshConvertible
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SweptAreaSolid](sweptareasolid/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Directrix](../../aspose.threed.entities/sweptareasolid/directrix/) { get; set; } | डायरेक्ट्रिक्स जिसके साथ स्विप्ड एरिया स्विप किया जाता है। |
| [EndPoint](../../aspose.threed.entities/sweptareasolid/endpoint/) { get; set; } | डायरेक्ट्रिक्स का अंत बिंदु। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [Shape](../../aspose.threed.entities/sweptareasolid/shape/) { get; set; } | ज्यामिति बनाने के लिए आधार प्रोफ़ाइल। |
| [StartPoint](../../aspose.threed.entities/sweptareasolid/startpoint/) { get; set; } | डायरेक्ट्रिक्स का प्रारंभ बिंदु। |

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
| [ToMesh](../../aspose.threed.entities/sweptareasolid/tomesh/)() | वर्तमान ऑब्जेक्ट को मेष में परिवर्तित करें |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक ठोस इकाई को एक वृत्त पर C-आकार स्विप करके मॉडल किया जाता है।

```csharp
var directrix = new Circle(20);
var shape = new CShape();

var swept = new SweptAreaSolid()
{
  Shape = shape,
  Directrix = directrix,
  StartPoint = EndPoint.FromDegree(0),
  EndPoint = EndPoint.FromDegree(130)
};

var scene = new Scene();
scene.RootNode.CreateChildNode(swept);
scene.Save("swept.obj");
```

### देखें भी

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


