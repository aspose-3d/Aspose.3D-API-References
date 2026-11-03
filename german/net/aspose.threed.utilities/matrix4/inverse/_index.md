---
title: "Matrix4.Inverse"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Matrix4-Methode. Invertiert diese Instanz"
type: docs
weight: 260
url: /de/net/aspose.threed.utilities/matrix4/inverse/
---
## Matrix4.Inverse method

Invertiert diese Instanz.

```csharp
public Matrix4 Inverse()
```

### Rückgabewert

Inverse Matrix4

## Beispiele

Der folgende Code zeigt, wie man eine Matrix invertiert

```csharp
var t = Matrix4.Translate(0, 10, 9);
var mat = t.Inverse();
Console.WriteLine($"Inversed Matrix: {mat}");
```

### Siehe auch

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


