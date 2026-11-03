---
title: "TransformBuilder.RotateDegree"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TransformBuilder विधि। डिग्री में घूर्णन ट्रांसफ़ॉर्म श्रृंखला बनाएं"
type: docs
weight: 100
url: /hi/net/aspose.threed.utilities/transformbuilder/rotatedegree/
---
## RotateDegree(double, Vector3) {#rotatedegree}

डिग्री में एक रोटेशन ट्रांसफ़ॉर्म श्रृंखलाबद्ध करें।

```csharp
public TransformBuilder RotateDegree(double angle, Vector3 axis)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कोण | डबल | घुमाने के लिए डिग्री में कोण |
| अक्ष | Vector3 | घुमाने के लिए अक्ष |

## उदाहरण

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateDegree(90, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateDegree(Vector3, RotationOrder) {#rotatedegree_1}

निर्दिष्ट क्रम के साथ घुमाव जोड़ें

```csharp
public void RotateDegree(Vector3 rot, RotationOrder order)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rot | Vector3 | डिग्री में घूर्णन |
| क्रम | RotationOrder |  |

### देखें भी

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


