---
title: "क्लास Bone"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Deformers.Bone क्लास। एक बोन ज्योमेट्री के कंट्रोल पॉइंट के उपसमुच्चय को परिभाषित करता है और प्रत्येक कंट्रोल पॉइंट के लिए ब्लेंड वेट निर्धारित करता है। Bone ऑब्जेक्ट को सीधे उपयोग नहीं किया जा सकता; एक SkinDeformer इंस्टेंस का उपयोग ज्योमेट्री को विकृत करने के लिए किया जाता है और SkinDeformer कई बोंस के सेट के साथ आता है, प्रत्येक बोन एक नोड से जुड़ा होता है। नोट: एक ज्योमेट्री का कंट्रोल पॉइंट एक से अधिक बोंस से बंधा हो सकता है।"
type: docs
weight: 190
url: /hi/net/aspose.threed.deformers/bone/
---
## Bone class

एक बोन ज्योमेट्री के कंट्रोल पॉइंट के उपसमुच्चय को परिभाषित करता है, और प्रत्येक कंट्रोल पॉइंट के लिए ब्लेंड वेट निर्धारित करता है। `Bone` ऑब्जेक्ट को सीधे उपयोग नहीं किया जा सकता, एक [`SkinDeformer`](../skindeformer/) इंस्टेंस का उपयोग ज्योमेट्री को विकृत करने के लिए किया जाता है, और [`SkinDeformer`](../skindeformer/) कई बोंस के सेट के साथ आता है, प्रत्येक बोन एक नोड से जुड़ा होता है। नोट: एक ज्योमेट्री का कंट्रोल पॉइंट एक से अधिक बोंस से बंधा हो सकता है।

```csharp
public class Bone : A3DObject
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Bone](bone/#constructor)() | `Bone` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Bone](bone/#constructor_1)(string) | `Bone` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BoneTransform](../../aspose.threed.deformers/bone/bonetransform/) { get; set; } | बोन के ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है। |
| [Item](../../aspose.threed.deformers/bone/item/) { get; set; } |  |
| [LinkMode](../../aspose.threed.deformers/bone/linkmode/) { get; set; } | हड्डी का लिंक मोड उस तरीके को दर्शाता है जिसमें एक हड्डी को पदानुक्रमित संरचना में उसकी पैरेंट हड्डी से जोड़ा या लिंक किया जाता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Node](../../aspose.threed.deformers/bone/node/) { get; set; } | नोड को प्राप्त करता है या सेट करता है। बोन नोड वह बोन है जिससे स्किन जुड़ा होता है, [`SkinDeformer`](../skindeformer/) बोन नोड का उपयोग कंट्रोल पॉइंट्स के विस्थापन को प्रभावित करने के लिए करेगा। बोन नोड आमतौर पर एक [`Skeleton`](../../aspose.threed.entities/skeleton/) से जुड़ा होता है, लेकिन यह आवश्यक नहीं है। जुड़ा हुआ [`Skeleton`](../../aspose.threed.entities/skeleton/) आमतौर पर DCC सॉफ़्टवेयर द्वारा उपयोगकर्ता को स्केलेटन दिखाने के लिए प्रयोग किया जाता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Transform](../../aspose.threed.deformers/bone/transform/) { get; set; } | बोन को सम्मिलित करने वाले नोड के ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है। |
| [WeightCount](../../aspose.threed.deformers/bone/weightcount/) { get; } | वेट की गिनती प्राप्त करता है, यह स्वचालित रूप से [`SetWeight`](./setweight/) द्वारा विस्तारित किया जाता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [GetWeight](../../aspose.threed.deformers/bone/getweight/)(int) | इंडेक्स द्वारा निर्दिष्ट कंट्रोल पॉइंट के लिए वेट प्राप्त करता है |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [SetWeight](../../aspose.threed.deformers/bone/setweight/)(int, double) | इंडेक्स द्वारा निर्दिष्ट कंट्रोल पॉइंट के लिए वेट सेट करता है |

### देखें भी

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


