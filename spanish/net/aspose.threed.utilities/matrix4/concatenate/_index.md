---
title: "Matrix4.Concatenate"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Matrix4. Concatena las dos matrices"
type: docs
weight: 240
url: /es/net/aspose.threed.utilities/matrix4/concatenate/
---
## Matrix4.Concatenate method

Concatena las dos matrices

```csharp
public Matrix4 Concatenate(Matrix4 m2)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

### Valor de retorno

Nuevo matrix4

## Ejemplos

```csharp
var t = Matrix4.Translate(0, 10, 9);
var s = Matrix4.Scale(10, 10, 10);
var transform = t.Concatenate(s);
var pos = new Vector3(10, 0, -1);
var transformed = transform * pos;
```

### Ver también

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


