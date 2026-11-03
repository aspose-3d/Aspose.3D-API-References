---
title: "TransformBuilder.Translate"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TransformBuilder विधि। एक अनुवाद ट्रांसफ़ॉर्म को श्रृंखलाबद्ध करें"
type: docs
weight: 150
url: /hi/net/aspose.threed.utilities/transformbuilder/translate/
---
## Translate(double, double, double) {#translate_1}

अनुवाद रूपांतरण को श्रृंखलाबद्ध करें

```csharp
public TransformBuilder Translate(double tx, double ty, double tz)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| tx | डबल |  |
| ty | डबल |  |
| tz | डबल |  |

## उदाहरण

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(0, 10, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Translate(Vector3) {#translate}

अनुवाद रूपांतरण को श्रृंखलाबद्ध करें

```csharp
public TransformBuilder Translate(Vector3 v)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| v | Vector3 |  |

## उदाहरण

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(new Vector3(0, 10, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


