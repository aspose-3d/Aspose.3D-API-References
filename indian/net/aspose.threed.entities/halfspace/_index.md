---
title: "क्लास HalfSpace"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.HalfSpace क्लास। HalfSpace एक अनंत स्थान को दर्शाता है जिसे एक तल द्वारा विभाजित किया जाता है, इसे BooleanOperator के साथ उपयोग किया जा सकता है"
type: docs
weight: 420
url: /hi/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` एक अनंत स्थान को दर्शाता है जिसे एक तल द्वारा विभाजित किया जाता है, इसे [`BooleanOperator`](../booleanoperator/) के साथ उपयोग किया जा सकता है

```csharp
public class HalfSpace : Entity
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | एक नया `HalfSpace` उदाहरण बनाता है |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | दिए गए सामान्य वेक्टर और कट्टर प्लेन पर स्थिति के साथ एक नया `HalfSpace` उदाहरण बनाता है; |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | विभाजन प्लेन का सामान्य, प्लेन को N * P + D = 0 के रूप में परिभाषित किया गया है जहाँ N सामान्य है और P प्लेन पर कोई भी बिंदु है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | विभाजन प्लेन पर कोई भी बिंदु, प्लेन को N * P + D = 0 के रूप में परिभाषित किया गया है जहाँ N सामान्य है और P प्लेन पर कोई भी बिंदु है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
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

### देखें भी

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


