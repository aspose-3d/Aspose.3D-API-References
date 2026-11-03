---
title: "क्लास Pose"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Pose क्लास। जब ज्योमेट्री स्किन्ड होती है तो ट्रांसफ़ॉर्मेशन मैट्रिक्स को संग्रहीत करने के लिए पोज़ का उपयोग किया जाता है। पोज़ BonePose का एक सेट है, प्रत्येक BonePose हड्डी नोड की ठोस ट्रांसफ़ॉर्मेशन जानकारी सहेजता है।"
type: docs
weight: 1650
url: /hi/net/aspose.threed/pose/
---
## Pose class

जब ज्योमेट्री स्किन्ड होती है तो ट्रांसफ़ॉर्मेशन मैट्रिक्स को संग्रहीत करने के लिए पोज़ का उपयोग किया जाता है। पोज़ [`BonePose`](../bonepose/) का एक सेट है, प्रत्येक [`BonePose`](../bonepose/) हड्डी नोड की ठोस ट्रांसफ़ॉर्मेशन जानकारी सहेजता है।

```csharp
public class Pose : A3DObject
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Pose](pose/#constructor)() | `Pose` क्लास का नया उदाहरण प्रारंभ करता है। |
| [Pose](pose/#constructor_1)(string) | `Pose` क्लास का नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BonePoses](../../aspose.threed/pose/boneposes/) { get; } | सभी [`BonePose`](../bonepose/) प्राप्त करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [PoseType](../../aspose.threed/pose/posetype/) { get; set; } | पोज़ के प्रकार को प्राप्त करता है या सेट करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose)(Node, Matrix4) | दिए गए हड्डी नोड के लिए पोज़ ट्रांसफ़ॉर्मेशन मैट्रिक्स सहेजता है। ग्लोबल ट्रांसफ़ॉर्मेशन मैट्रिक्स निहित है। |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose_1)(Node, Matrix4, bool) | दिए गए हड्डी नोड के लिए पोज़ ट्रांसफ़ॉर्मेशन मैट्रिक्स सहेजता है। |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

### देखें भी

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


