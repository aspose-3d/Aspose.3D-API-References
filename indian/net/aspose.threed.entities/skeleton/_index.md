---
title: "क्लास Skeleton"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.Skeleton क्लास। Skeleton मुख्यतः CAD सॉफ़्टवेयर द्वारा डिज़ाइनर को कंकाल संरचना के रूपांतरण को नियंत्रित करने में मदद करने के लिए उपयोग किया जाता है; यह आमतौर पर CAD सॉफ़्टवेयर के बाहर बेकार होता है। CAD सॉफ़्टवेयर में कंकाल पदानुक्रम को एक वस्तु की तरह कार्य करने के लिए, शीर्ष Skeleton नोड को Type को Skeleton सेट करके रूट नोड के रूप में चिह्नित करना आवश्यक है और सभी चाइल्ड को Bone सेट करना चाहिए।"
type: docs
weight: 710
url: /hi/net/aspose.threed.entities/skeleton/
---
## Skeleton class

`Skeleton` मुख्यतः CAD सॉफ़्टवेयर द्वारा डिज़ाइनर को कंकाल संरचना के रूपांतरण को नियंत्रित करने में मदद करने के लिए उपयोग किया जाता है, यह आमतौर पर CAD सॉफ़्टवेयर के बाहर बेकार होता है। कंकाल पदानुक्रम को CAD सॉफ़्टवेयर में एक वस्तु की तरह कार्य करने के लिए, शीर्ष `Skeleton` नोड को रूट बनाना आवश्यक है, जिसके लिए [`Type`](./type/) को Skeleton सेट किया जाए, और सभी चाइल्ड को Bone सेट किया जाए।

```csharp
public class Skeleton : Entity
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Skeleton](skeleton/#constructor)() | `Skeleton` क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [Skeleton](skeleton/#constructor_1)(string) | `Skeleton` क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [Skeleton](skeleton/#constructor_2)(string, SkeletonType) | `Skeleton` क्लास का एक नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [Size](../../aspose.threed.entities/skeleton/size/) { get; set; } | CAD सॉफ़्टवेयर में हड्डी के आकार को दर्शाने के लिए उपयोग किए जाने वाले लिम्ब नोड आकार को प्राप्त करता है या सेट करता है। |
| [Type](../../aspose.threed.entities/skeleton/type/) { get; set; } | स्केलेटन का प्रकार प्राप्त करता है या सेट करता है। |

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


