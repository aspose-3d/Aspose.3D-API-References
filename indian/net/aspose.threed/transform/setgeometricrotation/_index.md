---
title: "Transform.SetGeometricRotation"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Transform मेथड। ज्यामितीय यूलेर रोटेशन को डिग्री में सेट करता है। ज्यामितीय ट्रांसफ़ॉर्मेशन केवल जुड़े हुए एंटिटीज़ को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित छोड़ देता है। जब आप ज्यामितीय ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मर्ज हो जाएगा।"
type: docs
weight: 160
url: /hi/net/aspose.threed/transform/setgeometricrotation/
---
## Transform.SetGeometricRotation method

ज्यामितीय Euler रोटेशन (डिग्री में मापी गई) को सेट करता है। ज्यामितीय ट्रांसफ़ॉर्मेशन केवल जुड़े हुए इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित रखता है। जब आप इस ज्यामितीय ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा।

```csharp
public Transform SetGeometricRotation(double rx, double ry, double rz)
```

## उदाहरण

```csharp
Node node = new Node();
node.Transform.SetGeometricRotation(90, 0, 0);
```

### देखें भी

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


