---
title: "Matrix4.Rotate"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Matrix4 विधि। घुमाव कोण और अक्ष द्वारा रोटेशन मैट्रिक्स बनाता है"
type: docs
weight: 30
url: /hi/net/aspose.threed.utilities/matrix4/rotate/
---
## Rotate(double, Vector3) {#rotate_1}

रोटेशन कोण और अक्ष द्वारा एक रोटेशन मैट्रिक्स बनाएं

```csharp
public static Matrix4 Rotate(double angle, Vector3 axis)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कोण | डबल | रैडियन में घुमाव कोण |
| अक्ष | Vector3 | घूर्णन अक्ष |

## उदाहरण

निम्नलिखित कोड दिखाता है कि घुमाव ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं।

```csharp
var t = Matrix4.Rotate(Math.PI, new Vector3(0, 1, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### देखें भी

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Rotate(Quaternion) {#rotate}

क्वाटरनियन से एक रोटेशन मैट्रिक्स बनाएं

```csharp
public static Matrix4 Rotate(Quaternion q)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| q | क्वाटरनियन | घूर्णन क्वाटरनियन |

## उदाहरण

निम्नलिखित कोड दिखाता है कि घुमाव ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं।

```csharp
var t = Matrix4.Rotate(Quaternion.FromAngleAxis(Math.PI, Vector3.YAxis));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### देखें भी

* struct [Quaternion](../../quaternion/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


