---
title: "Mesh.op_Subtraction"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Mesh मेथड। दो मेषों का अंतर निकालें"
type: docs
weight: 150
url: /hi/net/aspose.threed.entities/mesh/op_subtraction/
---
## Mesh Subtraction operator

दो मेषों का अंतर गणना करें

```csharp
public static Mesh operator -(Mesh a, Mesh b)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| a | मेश | पहला मेष |
| b | मेश | दूसरा मेष |

### रिटर्न वैल्यू

परिणाम मेष

## उदाहरण

निम्नलिखित कोड दिखाता है कि दो मेषों का अंतर कैसे निकालें:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 - box2;
```

### देखें भी

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


