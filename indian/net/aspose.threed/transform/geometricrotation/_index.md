---
title: "Transform.GeometricRotation"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Transform प्रॉपर्टी। ज्यामितीय Euler रोटेशन को डिग्री में प्राप्त करता है या सेट करता है। ज्यामितीय ट्रांसफ़ॉर्मेशन केवल संलग्न इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अप्रभावित छोड़ता है। जब आप ज्यामितीय ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा।"
type: docs
weight: 20
url: /hi/net/aspose.threed/transform/geometricrotation/
---
## Transform.GeometricRotation property

ज्यामितीय Euler रोटेशन (डिग्री में मापी गई) को प्राप्त करता है या सेट करता है। ज्यामितीय ट्रांसफ़ॉर्मेशन केवल जुड़े हुए इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित रखता है। जब आप इस ज्यामितीय ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा।

```csharp
public Vector3 GeometricRotation { get; set; }
```

## उदाहरण

```csharp
Node node = new Node();
node.getTransform().setGeometricRotation(new Vector3(90, 0, 0));
```

### देखें भी

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


