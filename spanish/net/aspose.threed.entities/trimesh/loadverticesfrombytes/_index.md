---
title: "TriMesh.LoadVerticesFromBytes"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TriMesh. Cargar vértices desde bytes; la longitud de los bytes debe ser un múltiplo entero del tamaño del vértice"
type: docs
weight: 160
url: /es/net/aspose.threed.entities/trimesh/loadverticesfrombytes/
---
## TriMesh.LoadVerticesFromBytes method

Cargar vértices desde bytes, la longitud de los bytes debe ser un múltiplo entero del tamaño del vértice.

```csharp
public void LoadVerticesFromBytes(byte[] verticesInBytes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| verticesInBytes | Byte[] |  |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException |  |
| ArgumentException |  |

## Ejemplos

El siguiente código muestra cómo crear un TriMesh vacío y cargar manualmente vértices desde bytes sin procesar.

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
//crear un TriMesh vacío con la declaración de vértice especificada
var triMesh = new TriMesh("", vd);
//cargar vértices directamente desde bytes
triMesh.LoadVerticesFromBytes(vertices);
triMesh.AddTriangle(0, 1, 2);
```

```csharp
int[] indices = new int[] { 0,  1,  2 };
byte[] vertices = new byte[]{
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
vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
//crear un TriMesh vacío con la declaración de vértice especificada
var triMesh = new TriMesh("", vd);
//cargar vértices directamente desde bytes
triMesh.loadVerticesFromBytes(vertices);
triMesh.addTriangle(0, 1, 2);
```

### Ver también

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


