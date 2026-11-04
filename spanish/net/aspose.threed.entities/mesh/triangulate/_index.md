---
title: "Mesh.Triangulate"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Mesh. Devuelve una malla triangulada"
type: docs
weight: 120
url: /es/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

Devuelve la malla triangulada

```csharp
public Mesh Triangulate()
```

### Valor de retorno

Malla actual si ya está triangulada; de lo contrario, se calculará y devolverá una nueva malla triangulada

## Ejemplos

El siguiente código muestra cómo triangular una malla:

```csharp
//La malla plana tiene solo un polígono con 4 puntos de control
var mesh = (new Plane()).ToMesh();
//Después de triangular, el rectángulo de la nueva malla se convertirá en 2 triángulos.
var triangulated = mesh.Triangulate();
```

### Ver también

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


