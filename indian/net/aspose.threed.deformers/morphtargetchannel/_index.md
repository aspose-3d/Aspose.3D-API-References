---
title: "क्लास MorphTargetChannel"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Deformers.MorphTargetChannel क्लास। एक MorphTargetChannel का उपयोग MorphTargetDeformer द्वारा लक्ष्य ज्योमेट्री को व्यवस्थित करने के लिए किया जाता है। कुछ फ़ाइल फ़ॉर्मेट जैसे FBX समानांतर में कई चैनल का समर्थन करते हैं।"
type: docs
weight: 220
url: /hi/net/aspose.threed.deformers/morphtargetchannel/
---
## MorphTargetChannel class

एक MorphTargetChannel का उपयोग [`MorphTargetDeformer`](../morphtargetdeformer/) द्वारा लक्ष्य ज्योमेट्री को व्यवस्थित करने के लिए किया जाता है। कुछ फ़ाइल फ़ॉर्मेट जैसे FBX समानांतर में कई चैनल का समर्थन करते हैं।

```csharp
public class MorphTargetChannel : A3DObject
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MorphTargetChannel](morphtargetchannel/#constructor)() | `MorphTargetChannel` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MorphTargetChannel](morphtargetchannel/#constructor_1)(string) | `MorphTargetChannel` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [ChannelWeight](../../aspose.threed.deformers/morphtargetchannel/channelweight/) { get; set; } | इस चैनल का डिफॉर्मर वेट प्राप्त करता है या सेट करता है। वेट 0.0 और 1.0 के बीच होता है। |
| [Item](../../aspose.threed.deformers/morphtargetchannel/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Targets](../../aspose.threed.deformers/morphtargetchannel/targets/) { get; } | चैनल से जुड़े सभी टार्गेट्स प्राप्त करता है। |
| [Weights](../../aspose.threed.deformers/morphtargetchannel/weights/) { get; } | लक्ष्य ज्योमेट्री के पूर्ण वेट मान प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [GetWeight](../../aspose.threed.deformers/morphtargetchannel/getweight/)(Shape) | निर्दिष्ट टार्गेट के लिए वेट प्राप्त करता है, यदि टार्गेट इस चैनल से संबंधित नहीं है, तो डिफ़ॉल्ट मान 0 लौटाया जाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [SetWeight](../../aspose.threed.deformers/morphtargetchannel/setweight/)(Shape, double) | निर्दिष्ट टार्गेट के लिए वेट सेट करता है, डिफ़ॉल्ट मान 1 है, रेंज 0~1 के बीच होनी चाहिए। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [DefaultWeight](../../aspose.threed.deformers/morphtargetchannel/defaultweight/) | मॉर्फ़ लक्ष्य के लिए डिफ़ॉल्ट वजन। |

## टिप्पणियाँ

वजन 0 और 1.0 के बीच है, और लक्ष्य के लिए डिफ़ॉल्ट वजन 0.0 है;

### देखें भी

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


