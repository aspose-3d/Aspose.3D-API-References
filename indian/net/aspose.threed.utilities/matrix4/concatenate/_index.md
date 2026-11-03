---
title: "Matrix4.Concatenate"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Matrix4 विधि. दो मैट्रिसेज़ को जोड़ता है"
type: docs
weight: 240
url: /hi/net/aspose.threed.utilities/matrix4/concatenate/
---
## Matrix4.Concatenate method

दोनों मैट्रिक्स को जोड़ता है

```csharp
public Matrix4 Concatenate(Matrix4 m2)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

### रिटर्न वैल्यू

नया matrix4

## उदाहरण

```csharp
var t = Matrix4.Translate(0, 10, 9);
var s = Matrix4.Scale(10, 10, 10);
var transform = t.Concatenate(s);
var pos = new Vector3(10, 0, -1);
var transformed = transform * pos;
```

### देखें भी

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


