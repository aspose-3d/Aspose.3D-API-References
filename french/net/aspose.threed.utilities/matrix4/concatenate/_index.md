---
title: "Matrix4.Concatenate"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Matrix4. Concatène les deux matrices"
type: docs
weight: 240
url: /fr/net/aspose.threed.utilities/matrix4/concatenate/
---
## Matrix4.Concatenate method

Concatène les deux matrices

```csharp
public Matrix4 Concatenate(Matrix4 m2)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

### Valeur de retour

Nouvelle matrix4

## Exemples

```csharp
var t = Matrix4.Translate(0, 10, 9);
var s = Matrix4.Scale(10, 10, 10);
var transform = t.Concatenate(s);
var pos = new Vector3(10, 0, -1);
var transformed = transform * pos;
```

### Voir aussi

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


