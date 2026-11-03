---
title: "TransformBuilder.Rotate"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TransformBuilder विधि। क्वाटरनियन द्वारा घूर्णन श्रृंखला बनाएं"
type: docs
weight: 90
url: /hi/net/aspose.threed.utilities/transformbuilder/rotate/
---
## TransformBuilder.Rotate method

क्वाटरनियन द्वारा एक रोटेशन श्रृंखलाबद्ध करें।

```csharp
public TransformBuilder Rotate(Quaternion q)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| q | क्वाटरनियन |  |

## उदाहरण

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Rotate(Quaternion.FromEulerAngle(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* struct [Quaternion](../../quaternion/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


