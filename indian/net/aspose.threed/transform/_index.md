---
title: "क्लास Transform"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Transform क्लास। एक ट्रांसफ़ॉर्म में ऐसी जानकारी होती है जो ऑब्जेक्ट्स को ट्रांसलेट/स्केल/रोटेशन या ट्रांसफ़ॉर्म मैट्रिक्स तक न्यूनतम लागत पर पहुँचने की अनुमति देती है। यह स्थानीय ट्रांसफ़ॉर्म द्वारा उपयोग किया जाता है।"
type: docs
weight: 2650
url: /hi/net/aspose.threed/transform/
---
## Transform class

एक ट्रांसफ़ॉर्म में ऐसी जानकारी होती है जो ऑब्जेक्ट के ट्रांसलेट/स्केल/रोटेशन या ट्रांसफ़ॉर्म मैट्रिक्स तक न्यूनतम लागत पर पहुंच प्रदान करती है। यह स्थानीय ट्रांसफ़ॉर्म द्वारा उपयोग किया जाता है।

```csharp
public class Transform : A3DObject
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [EulerAngles](../../aspose.threed/transform/eulerangles/) { get; set; } | Euler कोणों में दर्शाई गई रोटेशन को प्राप्त करता है या सेट करता है, डिग्री में मापी गई |
| [GeometricRotation](../../aspose.threed/transform/geometricrotation/) { get; set; } | ज्यामितीय Euler रोटेशन (डिग्री में मापी गई) को प्राप्त करता है या सेट करता है। ज्यामितीय ट्रांसफ़ॉर्मेशन केवल जुड़े हुए इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित रखता है। जब आप इस ज्यामितीय ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा। |
| [GeometricScaling](../../aspose.threed/transform/geometricscaling/) { get; set; } | ज्यामितीय स्केलिंग को प्राप्त करता है या सेट करता है। ज्यामितीय ट्रांसफ़ॉर्मेशन केवल जुड़े हुए इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित रखता है। जब आप इस ज्यामितीय ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा। |
| [GeometricTranslation](../../aspose.threed/transform/geometrictranslation/) { get; set; } | ज्यामितीय ट्रांसलेशन को प्राप्त करता है या सेट करता है। ज्यामितीय ट्रांसफ़ॉर्मेशन केवल जुड़े हुए इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित रखता है। जब आप इस ज्यामितीय ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [PostRotation](../../aspose.threed/transform/postrotation/) { get; set; } | डिग्री में दर्शाए गए पोस्ट-रोटेशन को प्राप्त करता है या सेट करता है |
| [PreRotation](../../aspose.threed/transform/prerotation/) { get; set; } | डिग्री में दर्शाए गए प्री-रोटेशन को प्राप्त करता है या सेट करता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Rotation](../../aspose.threed/transform/rotation/) { get; set; } | क्वाटरनियन में दर्शाए गए रोटेशन को प्राप्त करता है या सेट करता है। |
| [RotationOffset](../../aspose.threed/transform/rotationoffset/) { get; set; } | रोटेशन ऑफ़सेट को प्राप्त करता है या सेट करता है |
| [RotationPivot](../../aspose.threed/transform/rotationpivot/) { get; set; } | रोटेशन पिवट को प्राप्त करता है या सेट करता है |
| [Scaling](../../aspose.threed/transform/scaling/) { get; set; } | स्केलिंग को प्राप्त करता है या सेट करता है |
| [ScalingOffset](../../aspose.threed/transform/scalingoffset/) { get; set; } | स्केलिंग ऑफ़सेट को प्राप्त करता है या सेट करता है |
| [ScalingPivot](../../aspose.threed/transform/scalingpivot/) { get; set; } | स्केलिंग पिवट को प्राप्त करता है या सेट करता है |
| [TransformMatrix](../../aspose.threed/transform/transformmatrix/) { get; set; } | ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है। |
| [Translation](../../aspose.threed/transform/translation/) { get; set; } | ट्रांसलेशन को प्राप्त करता है या सेट करता है |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetEulerAngles](../../aspose.threed/transform/seteulerangles/)(double, double, double) | वर्तमान ट्रांसफ़ॉर्म के Euler कोणों को डिग्री में सेट करता है। |
| [SetGeometricRotation](../../aspose.threed/transform/setgeometricrotation/)(double, double, double) | ज्यामितीय Euler रोटेशन (डिग्री में मापी गई) को सेट करता है। ज्यामितीय ट्रांसफ़ॉर्मेशन केवल जुड़े हुए इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित रखता है। जब आप इस ज्यामितीय ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा। |
| [SetGeometricScaling](../../aspose.threed/transform/setgeometricscaling/)(double, double, double) | ज्यामितीय स्केलिंग को सेट करता है। ज्यामितीय ट्रांसफ़ॉर्मेशन केवल जुड़े हुए इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित रखता है। जब आप इस ज्यामितीय ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा। |
| [SetGeometricTranslation](../../aspose.threed/transform/setgeometrictranslation/)(double, double, double) | ज्यामितीय ट्रांसलेशन को सेट करता है। ज्यामितीय ट्रांसफ़ॉर्मेशन केवल जुड़े हुए इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित रखता है। जब आप इस ज्यामितीय ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा। |
| [SetPostRotation](../../aspose.threed/transform/setpostrotation/)(double, double, double) | डिग्री में दर्शाए गए पोस्ट-रोटेशन को सेट करता है |
| [SetPreRotation](../../aspose.threed/transform/setprerotation/)(double, double, double) | डिग्री में दर्शाए गए प्री-रोटेशन को सेट करता है |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [SetRotation](../../aspose.threed/transform/setrotation/)(double, double, double, double) | वर्तमान ट्रांसफ़ॉर्म की रोटेशन (क्वाटरनियन घटकों के रूप में) को सेट करता है। |
| [SetScale](../../aspose.threed/transform/setscale/)(double, double, double) | वर्तमान ट्रांसफ़ॉर्म का स्केल सेट करता है। |
| [SetTranslation](../../aspose.threed/transform/settranslation/)(double, double, double) | वर्तमान ट्रांसफ़ॉर्म का ट्रांसलेशन सेट करता है। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि नोड का ट्रांसफ़ॉर्म कैसे बदलें:

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//बॉक्स को (10, 0, 0) पर रखें
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### देखें भी

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


