---
title: "Mesh.op_BitwiseOr"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Mesh. Calcula la unión de dos mallas"
type: docs
weight: 140
url: /es/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

Calcula la unión de dos mallas

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | Malla | Primera malla |
| b | Malla | Segunda malla |

### Valor de retorno

Malla resultante

## Ejemplos

El siguiente código muestra cómo unir dos mallas en una sola malla:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### Ver también

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


