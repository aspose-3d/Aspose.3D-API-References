---
title: "Mesh.op_Subtraction"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Mesh. Calcula la diferencia de dos mallas"
type: docs
weight: 150
url: /es/net/aspose.threed.entities/mesh/op_subtraction/
---
## Mesh Subtraction operator

Calcular la diferencia de dos mallas

```csharp
public static Mesh operator -(Mesh a, Mesh b)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | Malla | Primera malla |
| b | Malla | Segunda malla |

### Valor de retorno

Malla resultante

## Ejemplos

El siguiente código muestra cómo calcular la diferencia de dos mallas:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 - box2;
```

### Ver también

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


