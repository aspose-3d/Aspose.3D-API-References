---
title: "TriMesh.WriteVerticesTo"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TriMesh. Escribir los datos de vértices al flujo especificado"
type: docs
weight: 290
url: /es/net/aspose.threed.entities/trimesh/writeverticesto/
---
## TriMesh.WriteVerticesTo method

Escribe los datos de vértices al flujo especificado

```csharp
public void WriteVerticesTo(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo al que se escribirán los datos de vértices |

## Ejemplos

```csharp
//convertir una malla a TriMesh, el diseño se infiere automáticamente de la malla de entrada
var triMesh = TriMesh.FromMesh(new Sphere().ToMesh());
//guárdalo en un flujo, 115 vértices * 32 bytes por vértice
var stream = new MemoryStream();
triMesh.WriteVerticesTo(stream);
//guarda los índices como ushort en el flujo, 504 índices * 2 bytes por índice
triMesh.Write16bIndicesTo(stream);
```

### Ver también

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


