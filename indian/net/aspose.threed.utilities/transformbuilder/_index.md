---
title: "क्लास TransformBuilder"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Utilities.TransformBuilder क्लास। TransformBuilder का उपयोग ट्रांसफ़ॉर्म मैट्रिक्स को ट्रांसफ़ॉर्मेशन्स की श्रृंखला द्वारा बनाने के लिए किया जाता है।"
type: docs
weight: 2860
url: /hi/net/aspose.threed.utilities/transformbuilder/
---
## TransformBuilder class

`TransformBuilder` का उपयोग ट्रांसफ़ॉर्म मैट्रिक्स को ट्रांसफ़ॉर्मेशन्स की श्रृंखला द्वारा बनाने के लिए किया जाता है।

```csharp
public class TransformBuilder
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TransformBuilder](transformbuilder/#constructor)(ComposeOrder) | `TransformBuilder` को प्रारंभिक आइडेंटिटी ट्रांसफ़ॉर्म मैट्रिक्स और निर्दिष्ट कंपोज़ क्रम के साथ बनाएं। |
| [TransformBuilder](transformbuilder/#constructor_1)(Matrix4, ComposeOrder) | `TransformBuilder` को प्रारंभिक ट्रांसफ़ॉर्म मैट्रिक्स और निर्दिष्ट कंपोज़ क्रम के साथ बनाएं। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [ComposeOrder](../../aspose.threed.utilities/transformbuilder/composeorder/) { get; set; } | श्रृंखला कंपोज़ क्रम को प्राप्त करता है या सेट करता है। |
| [Matrix](../../aspose.threed.utilities/transformbuilder/matrix/) { get; set; } | वर्तमान मैट्रिक्स मान को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Append](../../aspose.threed.utilities/transformbuilder/append/)(Matrix4) | नया ट्रांसफ़ॉर्म मैट्रिक्स ट्रांसफ़ॉर्म श्रृंखला में जोड़ें। |
| [Compose](../../aspose.threed.utilities/transformbuilder/compose/)(Matrix4) | आर्ग्युमेंट को आंतरिक मैट्रिक्स में जोड़ें या प्रीपेंड करें। |
| [Prepend](../../aspose.threed.utilities/transformbuilder/prepend/)(Matrix4) | नया ट्रांसफ़ॉर्म मैट्रिक्स ट्रांसफ़ॉर्म श्रृंखला में प्रीपेंड करें। |
| [Rearrange](../../aspose.threed.utilities/transformbuilder/rearrange/)(Axis, Axis, Axis) | अक्ष की लेआउट को पुनर्व्यवस्थित करें। |
| [Reset](../../aspose.threed.utilities/transformbuilder/reset/)() | ट्रांसफ़ॉर्म को आइडेंटिटी मैट्रिक्स में रीसेट करें। |
| [Rotate](../../aspose.threed.utilities/transformbuilder/rotate/)(Quaternion) | क्वाटरनियन द्वारा एक रोटेशन श्रृंखलाबद्ध करें। |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree)(double, Vector3) | डिग्री में एक रोटेशन ट्रांसफ़ॉर्म श्रृंखलाबद्ध करें। |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree_1)(Vector3, RotationOrder) | निर्दिष्ट क्रम के साथ घुमाव जोड़ें |
| [RotateEulerDegree](../../aspose.threed.utilities/transformbuilder/rotateeulerdegree/)(double, double, double) | डिग्री में यूलेर कोणों द्वारा घुमाव को श्रृंखलाबद्ध करें |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian)(Vector3) | रेडियन में यूलेर कोणों द्वारा घुमाव को श्रृंखलाबद्ध करें |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian_1)(double, double, double) | रेडियन में यूलेर कोणों द्वारा घुमाव को श्रृंखलाबद्ध करें |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian)(double, Vector3) | रेडियन में घुमाव रूपांतरण को श्रृंखलाबद्ध करें |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian_1)(Vector3, RotationOrder) | निर्दिष्ट क्रम के साथ घुमाव जोड़ें |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_1)(double) | एक घटक को s द्वारा स्केल किए हुए स्केलिंग रूपांतरण मैट्रिक्स को श्रृंखलाबद्ध करें |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale)(Vector3) | स्केल रूपांतरण को श्रृंखलाबद्ध करें |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_2)(double, double, double) | स्केलिंग रूपांतरण मैट्रिक्स को श्रृंखलाबद्ध करें |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate)(Vector3) | अनुवाद रूपांतरण को श्रृंखलाबद्ध करें |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate_1)(double, double, double) | अनुवाद रूपांतरण को श्रृंखलाबद्ध करें |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक सेट ऑपरेशन द्वारा मैट्रिक्स बनाया जाए

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(10, 20, 0);
tb.Scale(10, 10, 10);
tb.RotateEulerDegree(90, 0, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


