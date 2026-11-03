---
title: "Mesh.op_BitwiseOr"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Mesh मेथड। दो मेषों का यूनियन गणना करता है"
type: docs
weight: 140
url: /hi/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

दो मेशों का संघ गणना करें

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| a | मेश | पहला मेष |
| b | मेश | दूसरा मेष |

### रिटर्न वैल्यू

परिणाम मेष

## उदाहरण

निम्नलिखित कोड दिखाता है कि दो मेषों को एक मेष में कैसे यूनियन किया जाए:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### देखें भी

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


