---
title: "TriMesh.Write32bIndicesTo"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TriMesh. Escribir los datos de índices como entero de 32 bits al flujo"
type: docs
weight: 280
url: /es/net/aspose.threed.entities/trimesh/write32bindicesto/
---
## TriMesh.Write32bIndicesTo method

Escribe los datos de índices como entero de 32 bits al flujo

```csharp
public void Write32bIndicesTo(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream |  |

## Ejemplos

```csharp
//convertir una malla a TriMesh, el diseño se infiere automáticamente de la malla de entrada
var triMesh = TriMesh.FromMesh(new Sphere().ToMesh());
//guárdalo en un flujo, 115 vértices * 32 bytes por vértice
var stream = new MemoryStream();
triMesh.WriteVerticesTo(stream);
//guarda los índices como ushort en el flujo, 504 índices * 2 bytes por índice
triMesh.Write32bIndicesTo(stream);
```

### Ver también

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


