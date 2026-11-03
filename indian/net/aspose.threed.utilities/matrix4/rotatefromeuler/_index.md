---
title: "Matrix4.RotateFromEuler"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Matrix4 मेथड। ईयूलर कोण से एक घूर्णन मैट्रिक्स बनाएं"
type: docs
weight: 40
url: /hi/net/aspose.threed.utilities/matrix4/rotatefromeuler/
---
## RotateFromEuler(Vector3) {#rotatefromeuler}

ऑयलर कोण से एक रोटेशन मैट्रिक्स बनाएं

```csharp
public static Matrix4 RotateFromEuler(Vector3 eul)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| eul | Vector3 | रैडियन में घूर्णन |

## उदाहरण

निम्नलिखित कोड दिखाता है कि घुमाव ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं।

```csharp
var t = Matrix4.RotateFromEuler(new Vector3(0, Math.PI, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### देखें भी

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## RotateFromEuler(double, double, double) {#rotatefromeuler_1}

ऑयलर कोण से एक रोटेशन मैट्रिक्स बनाएं

```csharp
public static Matrix4 RotateFromEuler(double rx, double ry, double rz)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rx | डबल | x-अक्ष में रैडियन में घूर्णन |
| ry | डबल | y-अक्ष में रैडियन में घूर्णन |
| rz | डबल | z-अक्ष में रैडियन में घूर्णन |

## उदाहरण

निम्नलिखित कोड दिखाता है कि घुमाव ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं।

```csharp
var t = Matrix4.RotateFromEuler(0, Math.PI, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### देखें भी

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


