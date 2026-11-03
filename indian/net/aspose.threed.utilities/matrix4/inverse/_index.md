---
title: "Matrix4.Inverse"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Matrix4 मेथड। इस इंस्टेंस को इनवर्स करता है"
type: docs
weight: 260
url: /hi/net/aspose.threed.utilities/matrix4/inverse/
---
## Matrix4.Inverse method

इस उदाहरण को उलटता है।

```csharp
public Matrix4 Inverse()
```

### रिटर्न वैल्यू

इनवर्स matrix4

## उदाहरण

निम्नलिखित कोड दिखाता है कि मैट्रिक्स को कैसे इनवर्स करें

```csharp
var t = Matrix4.Translate(0, 10, 9);
var mat = t.Inverse();
Console.WriteLine($"Inversed Matrix: {mat}");
```

### देखें भी

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


