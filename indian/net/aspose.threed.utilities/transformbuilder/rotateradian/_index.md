---
title: "TransformBuilder.RotateRadian"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TransformBuilder विधि। रेडियन में घूर्णन ट्रांसफ़ॉर्म श्रृंखला बनाएं"
type: docs
weight: 130
url: /hi/net/aspose.threed.utilities/transformbuilder/rotateradian/
---
## RotateRadian(double, Vector3) {#rotateradian}

रेडियन में घुमाव रूपांतरण को श्रृंखलाबद्ध करें

```csharp
public TransformBuilder RotateRadian(double angle, Vector3 axis)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कोण | डबल | रेडियन में घुमाने के लिए कोण |
| अक्ष | Vector3 | घुमाने के लिए अक्ष |

## उदाहरण

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(Math.PI, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateRadian(Vector3, RotationOrder) {#rotateradian_1}

निर्दिष्ट क्रम के साथ घुमाव जोड़ें

```csharp
public void RotateRadian(Vector3 rot, RotationOrder order)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rot | Vector3 | रैडियन में घूर्णन |
| क्रम | RotationOrder |  |

## उदाहरण

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(new Vector3(0.3, 0.4, 0.1), RotationOrder.YZX);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


