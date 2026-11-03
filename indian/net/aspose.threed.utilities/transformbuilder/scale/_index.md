---
title: "TransformBuilder.Scale"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TransformBuilder विधि। s द्वारा स्केल किए गए घटक के साथ स्केलिंग ट्रांसफ़ॉर्म मैट्रिक्स को श्रृंखला बनाएं"
type: docs
weight: 140
url: /hi/net/aspose.threed.utilities/transformbuilder/scale/
---
## Scale(double) {#scale_1}

एक घटक को s द्वारा स्केल किए हुए स्केलिंग रूपांतरण मैट्रिक्स को श्रृंखलाबद्ध करें

```csharp
public TransformBuilder Scale(double s)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | डबल |  |

## उदाहरण

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

स्केलिंग रूपांतरण मैट्रिक्स को श्रृंखलाबद्ध करें

```csharp
public TransformBuilder Scale(double x, double y, double z)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | डबल |  |
| y | डबल |  |
| z | डबल |  |

## उदाहरण

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10, 10, 10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(Vector3) {#scale}

स्केल रूपांतरण को श्रृंखलाबद्ध करें

```csharp
public TransformBuilder Scale(Vector3 s)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | Vector3 |  |

## उदाहरण

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(new Vector3(10, 10, 10));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


