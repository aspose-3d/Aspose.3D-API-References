---
title: "संरचना Quaternion"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Utilities.Quaternion संरचना। क्वाटरनियन आमतौर पर कंप्यूटर ग्राफिक्स में घूर्णन करने के लिए उपयोग किया जाता है"
type: docs
weight: 2810
url: /hi/net/aspose.threed.utilities/quaternion/
---
## Quaternion structure

क्वाटरनियन का सामान्यतः कंप्यूटर ग्राफ़िक्स में रोटेशन करने के लिए उपयोग किया जाता है।

```csharp
public struct Quaternion
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Quaternion](quaternion/)(double, double, double, double) | `Quaternion` क्लास का नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Length](../../aspose.threed.utilities/quaternion/length/) { get; } | क्वाटरनियन की लंबाई प्राप्त करता है |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromAngleAxis](../../aspose.threed.utilities/quaternion/fromangleaxis/)(double, Vector3) | दिए गए अक्ष के चारों ओर एक क्वाटरनियन बनाता है और घड़ी की दिशा में घुमाता है |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle)(Vector3) | दिए गए यूलेर कोण से क्वाटरनियन बनाता है |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle_1)(double, double, double) | दिए गए यूलेर कोण से क्वाटरनियन बनाता है |
| static [FromRotation](../../aspose.threed.utilities/quaternion/fromrotation/)(Vector3, Vector3) | मूल दिशा से गंतव्य दिशा की ओर घुमाने वाला क्वाटरनियन बनाता है |
| static [Interpolate](../../aspose.threed.utilities/quaternion/interpolate/)(float, Quaternion, Quaternion) | इस क्वाटरनियन को दिए गए क्वाटरनियन तर्कों के बीच इंटरपोलेटेड मान से भरता है, जहाँ t प्रारंभ से अंत तक होता है। |
| static [Slerp](../../aspose.threed.utilities/quaternion/slerp/)(double, Quaternion, Quaternion) | दो मानों के बीच गोलाकार रैखिक इंटरपोलेशन करता है |
| [Concat](../../aspose.threed.utilities/quaternion/concat/)(Quaternion) | दो क्वाटरनियनों को जोड़ता है |
| [Conjugate](../../aspose.threed.utilities/quaternion/conjugate/)() | वर्तमान क्वाटरनियन का संयुग्म क्वाटरनियन लौटाता है |
| [Dot](../../aspose.threed.utilities/quaternion/dot/)(Quaternion) | डॉट उत्पाद |
| override [Equals](../../aspose.threed.utilities/quaternion/equals/)(object) | जाँचें कि दो क्वाटरनियन बराबर हैं या नहीं |
| [EulerAngles](../../aspose.threed.utilities/quaternion/eulerangles/)() | क्वाटरनियन को यूलेर कोणों द्वारा दर्शाए गए घूर्णन में परिवर्तित करता है। सभी घटक रेडियन में हैं। |
| override [GetHashCode](../../aspose.threed.utilities/quaternion/gethashcode/)() | क्वाटरनियन का हैश कोड प्राप्त करता है |
| [Inverse](../../aspose.threed.utilities/quaternion/inverse/)() | वर्तमान क्वाटरनियन का उलटा क्वाटरनियन लौटाता है |
| [Normalize](../../aspose.threed.utilities/quaternion/normalize/)() | क्वाटरनियन को सामान्यीकृत करें |
| [ToAngleAxis](../../aspose.threed.utilities/quaternion/toangleaxis/)(out double, out Vector3) |  |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix)() | क्वाटरनियन द्वारा प्रस्तुत घूर्णन को ट्रांसफ़ॉर्म मैट्रिक्स में परिवर्तित करें। |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix_1)(Vector3) | क्वाटरनियन द्वारा प्रस्तुत घूर्णन को ट्रांसफ़ॉर्म मैट्रिक्स में परिवर्तित करें। |
| override [ToString](../../aspose.threed.utilities/quaternion/tostring/)() | क्वाटरनियन का स्ट्रिंग में प्रतिनिधित्व प्राप्त करता है |
| [operator +](../../aspose.threed.utilities/quaternion/op_addition/) | + के लिए ऑपरेटर ओवरलोडिंग |
| [operator /](../../aspose.threed.utilities/quaternion/op_division/) | / के लिए ऑपरेटर ओवरलोडिंग |
| [operator ==](../../aspose.threed.utilities/quaternion/op_equality/) | क्वाटरनियन के लिए समानता ऑपरेटर |
| [operator !=](../../aspose.threed.utilities/quaternion/op_inequality/) | क्वाटरनियन के लिए असमानता ऑपरेटर |
| [operator *](../../aspose.threed.utilities/quaternion/op_multiply/#op_multiply_1) | * के लिए ऑपरेटर ओवरलोडिंग (5 ऑपरेटर) |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| static readonly [Identity](../../aspose.threed.utilities/quaternion/identity/) | पहचान क्वाटरनियन। |
| [W](../../aspose.threed.utilities/quaternion/w/) | w घटक। |
| [X](../../aspose.threed.utilities/quaternion/x/) | x घटक। |
| [Y](../../aspose.threed.utilities/quaternion/y/) | y घटक। |
| [Z](../../aspose.threed.utilities/quaternion/z/) | z घटक। |

### देखें भी

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


