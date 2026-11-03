---
title: "Matrix4.Scale"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Matrix4 मेथड। एक मैट्रिक्स बनाता है जो x‑अक्ष, y‑अक्ष और z‑अक्ष के साथ स्केल करता है"
type: docs
weight: 50
url: /hi/net/aspose.threed.utilities/matrix4/scale/
---
## Scale(Vector3) {#scale}

एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ स्केल करता है।

```csharp
public static Matrix4 Scale(Vector3 s)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | Vector3 | स्केलिंग फ़ैक्टरीज़ x‑अक्ष, y‑अक्ष और z‑अक्ष पर लागू होती हैं |

## उदाहरण

निम्नलिखित कोड दर्शाता है कि स्केल ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं।

```csharp
var t = Matrix4.Scale(new Vector3(10, 10, 10));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### देखें भी

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double) {#scale_1}

एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ स्केल करता है।

```csharp
public static Matrix4 Scale(double s)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | डबल | स्केलिंग फ़ैक्टरीज़ सभी अक्षों पर लागू होती हैं |

## उदाहरण

निम्नलिखित कोड दर्शाता है कि स्केल ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं।

```csharp
var t = Matrix4.Scale(10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### देखें भी

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ स्केल करता है।

```csharp
public static Matrix4 Scale(double sx, double sy, double sz)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sx | डबल | स्केलिंग फैक्ट्रीज़ x-अक्ष पर लागू होती हैं |
| sy | डबल | स्केलिंग फैक्ट्रीज़ y-अक्ष पर लागू होती हैं |
| sz | डबल | स्केलिंग फैक्ट्रीज़ z-अक्ष पर लागू होती हैं |

## उदाहरण

निम्नलिखित कोड दर्शाता है कि स्केल ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं।

```csharp
var t = Matrix4.Scale(10, 20, 10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### देखें भी

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


