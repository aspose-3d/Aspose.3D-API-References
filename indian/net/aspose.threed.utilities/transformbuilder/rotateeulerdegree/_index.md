---
title: "TransformBuilder.RotateEulerDegree"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TransformBuilder विधि। डिग्री में यूलेर कोणों द्वारा घूर्णन श्रृंखला बनाएं"
type: docs
weight: 110
url: /hi/net/aspose.threed.utilities/transformbuilder/rotateeulerdegree/
---
## TransformBuilder.RotateEulerDegree method

डिग्री में यूलेर कोणों द्वारा घुमाव को श्रृंखलाबद्ध करें

```csharp
public TransformBuilder RotateEulerDegree(double degX, double degY, double degZ)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| degX | डबल |  |
| degY | डबल |  |
| degZ | डबल |  |

## उदाहरण

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerDegree(0, 90, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### देखें भी

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


