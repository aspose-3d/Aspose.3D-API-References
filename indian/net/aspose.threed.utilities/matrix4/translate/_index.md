---
title: "Matrix4.Translate"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Matrix4 मेथड। एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ ट्रांसलेट करता है"
type: docs
weight: 60
url: /hi/net/aspose.threed.utilities/matrix4/translate/
---
## Translate(Vector3) {#translate}

एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ ट्रांसलेट करता है।

```csharp
public static Matrix4 Translate(Vector3 t)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| t | Vector3 | ट्रांसलेट ऑफ़सेट |

## उदाहरण

निम्नलिखित कोड दिखाता है कि ट्रांसलेट ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं।

```csharp
var t = Matrix4.Translate(new Vector3(10, 0, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### देखें भी

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Translate(double, double, double) {#translate_1}

एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ ट्रांसलेट करता है।

```csharp
public static Matrix4 Translate(double tx, double ty, double tz)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| tx | डबल | X-कोऑर्डिनेट ऑफ़सेट |
| ty | डबल | Y-कोऑर्डिनेट ऑफ़सेट |
| tz | डबल | Z-कोऑर्डिनेट ऑफ़सेट |

## उदाहरण

निम्नलिखित कोड दिखाता है कि ट्रांसलेट ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं।

```csharp
var t = Matrix4.Translate(10, 0, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### देखें भी

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


