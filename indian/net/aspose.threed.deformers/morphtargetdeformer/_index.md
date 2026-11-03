---
title: "क्लास MorphTargetDeformer"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Deformers.MorphTargetDeformer क्लास। MorphTargetDeformer प्रति-वर्टेक्स एनीमेशन प्रदान करता है। MorphTargetDeformer सभी लक्ष्यों को MorphTargetChannel के माध्यम से व्यवस्थित करता है, प्रत्येक चैनल कई लक्ष्यों को व्यवस्थित कर सकता है। morph target deformer का एक सामान्य उपयोग किसी चरित्र पर चेहरे की अभिव्यक्ति लागू करना है। अधिक विवरण https//en.wikipedia.org/wiki/Morph_target_animation पर पाया जा सकता है।"
type: docs
weight: 230
url: /hi/net/aspose.threed.deformers/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer प्रति-वर्टेक्स एनीमेशन प्रदान करता है। MorphTargetDeformer सभी लक्ष्यों को [`MorphTargetChannel`](../morphtargetchannel/) के माध्यम से व्यवस्थित करता है, प्रत्येक चैनल कई लक्ष्यों को व्यवस्थित कर सकता है। morph target deformer का एक सामान्य उपयोग किसी चरित्र पर चेहरे की अभिव्यक्ति लागू करना है। अधिक विवरण https://en.wikipedia.org/wiki/Morph_target_animation पर पाया जा सकता है।

```csharp
public class MorphTargetDeformer : Deformer
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MorphTargetDeformer](morphtargetdeformer/#constructor)() | `MorphTargetDeformer` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MorphTargetDeformer](morphtargetdeformer/#constructor_1)(string) | `MorphTargetDeformer` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Channels](../../aspose.threed.deformers/morphtargetdeformer/channels/) { get; } | इस डिफॉर्मर में शामिल सभी चैनलों को प्राप्त करता है |
| [Item](../../aspose.threed.deformers/morphtargetdeformer/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Owner](../../aspose.threed.deformers/deformer/owner/) { get; } | उस ज्योमेट्री को प्राप्त करता है जो इस डीफ़ॉर्मर का मालिक है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

### देखें भी

* class [Deformer](../deformer/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


