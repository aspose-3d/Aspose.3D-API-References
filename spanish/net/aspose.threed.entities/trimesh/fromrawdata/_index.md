---
title: "TriMesh.FromRawData"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TriMesh. Crear TriMesh a partir de datos sin procesar"
type: docs
weight: 40
url: /es/net/aspose.threed.entities/trimesh/fromrawdata/
---
## TriMesh.FromRawData method

Crear TriMesh a partir de datos sin procesar

```csharp
public static TriMesh FromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, 
    bool generateVertexMapping)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vd | VertexDeclaration | Declaración del vértice, debe contener al menos un campo. |
| vertices | Byte[] | Los datos de vértice de entrada, la longitud mínima de los vértices debe ser mayor o igual al tamaño de la declaración del vértice |
| indices | Int32[] | Los índices del triángulo |
| generateVertexMapping | Boolean | Generar [`Vertex`](../../../aspose.threed.utilities/vertex/) para cada vértice, lo cual no es necesario solo para serialización/deserialización. |

### Valor de retorno

La instancia [`TriMesh`](../) que encapsuló el arreglo de bytes de entrada.

## Observaciones

El TriMesh devuelto no copiará el arreglo de bytes de entrada por rendimiento, los cambios externos en el arreglo se reflejarán en esta instancia.

## Ejemplos

El siguiente código muestra cómo construir un TriMesh a partir de bytes sin procesar, lo cual es útil al crear tu propio formato 3D

```csharp
var indices = new int[] { 0,  1,  2 };
var vertices = new byte[]{
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 191,
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 63,
    0, 0, 0, 63,
    0, 0, 0, 0,
    0, 0, 0, 63
};
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```

### Ver también

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


