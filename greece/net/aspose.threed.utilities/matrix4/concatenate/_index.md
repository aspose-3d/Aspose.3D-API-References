---
title: "Matrix4.Concatenate"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Matrix4. Συνενώνει τις δύο μήτρες"
type: docs
weight: 240
url: /el/net/aspose.threed.utilities/matrix4/concatenate/
---
## Matrix4.Concatenate method

Συνενώνει τους δύο πίνακες

```csharp
public Matrix4 Concatenate(Matrix4 m2)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

### Τιμή επιστροφής

Νέος matrix4

## Παραδείγματα

```csharp
var t = Matrix4.Translate(0, 10, 9);
var s = Matrix4.Scale(10, 10, 10);
var transform = t.Concatenate(s);
var pos = new Vector3(10, 0, -1);
var transformed = transform * pos;
```

### Δείτε επίσης

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


