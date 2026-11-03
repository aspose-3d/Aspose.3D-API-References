---
title: "Matrix4.Concatenate"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Matrix4-Methode. Verkettet die beiden Matrizen"
type: docs
weight: 240
url: /de/net/aspose.threed.utilities/matrix4/concatenate/
---
## Matrix4.Concatenate method

Verkettet die beiden Matrizen

```csharp
public Matrix4 Concatenate(Matrix4 m2)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

### Rückgabewert

Neue matrix4

## Beispiele

```csharp
var t = Matrix4.Translate(0, 10, 9);
var s = Matrix4.Scale(10, 10, 10);
var transform = t.Concatenate(s);
var pos = new Vector3(10, 0, -1);
var transformed = transform * pos;
```

### Siehe auch

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


