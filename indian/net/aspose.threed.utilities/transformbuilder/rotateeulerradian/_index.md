---
title: "TransformBuilder.RotateEulerRadian"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TransformBuilder विधि। रेडियन में यूलेर कोणों द्वारा घूर्णन को श्रृंखलाबद्ध करें"
type: docs
weight: 120
url: /hi/net/aspose.threed.utilities/transformbuilder/rotateeulerradian/
---
## RotateEulerRadian(double, double, double) {#rotateeulerradian_1}

रेडियन में यूलेर कोणों द्वारा घुमाव को श्रृंखलाबद्ध करें

```csharp
public TransformBuilder RotateEulerRadian(double x, double y, double z)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | डबल |  |
| y | डबल |  |
| z | डबल |  |

## उदाहरण

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(0, Math.PI, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateEulerRadian(Vector3) {#rotateeulerradian}

रेडियन में यूलेर कोणों द्वारा घुमाव को श्रृंखलाबद्ध करें

```csharp
public TransformBuilder RotateEulerRadian(Vector3 r)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| r | Vector3 |  |

## उदाहरण

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(new Vector3(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


