---
title: "TriMesh.FromMesh"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TriMesh. Crear un TriMesh a partir del objeto de malla dado con el diseño de vértice especificado"
type: docs
weight: 30
url: /es/net/aspose.threed.entities/trimesh/frommesh/
---
## FromMesh(VertexDeclaration, Mesh) {#frommesh_1}

Crear un TriMesh a partir del objeto de malla dado con el diseño de vértices especificado.

```csharp
public static TriMesh FromMesh(VertexDeclaration declaration, Mesh mesh)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| declaración | VertexDeclaration | Definición de tipo de Vertex, o diseño de memoria |
| malla | Malla | Malla de origen |

### Valor de retorno

Instancia de TriMesh convertida de la malla de entrada con el diseño de memoria del vértice especificado

## Ejemplos

El siguiente código muestra cómo crear un TriMesh con una disposición de memoria personalizada y exportarlo a un archivo.

```csharp
//Define una declaración de vértice como {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//convierte una malla a tri-mesh usando la disposición de memoria especificada
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//guárdalo en un flujo, 115 vértices * 32 bytes por vértice
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //guarda los índices como ushort en el flujo, 504 índices * 2 bytes por índice
    triMesh.Write16bIndicesTo(stream);
}
```

### Ver también

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)

---

## FromMesh(Mesh, bool) {#frommesh}

Crear un TriMesh a partir del objeto de malla dado, la declaración de vértices se basa en la estructura de la malla de entrada.

```csharp
public static TriMesh FromMesh(Mesh mesh, bool useFloat = true)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| malla | Malla |  |
| useFloat | Boolean | Usar tipo float en lugar de tipo double para cada componente del elemento de vértice. |

### Valor de retorno

El [`TriMesh`](../) generado a partir de la [`Mesh`](../../mesh/)

## Ejemplos

El siguiente código muestra cómo crear un TriMesh con una disposición de memoria personalizada y exportarlo a un archivo.

```csharp
//Define una declaración de vértice como {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//convierte una malla a tri-mesh usando la disposición de memoria especificada
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//guárdalo en un flujo, 115 vértices * 32 bytes por vértice
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //guarda los índices como ushort en el flujo, 504 índices * 2 bytes por índice
    triMesh.Write16bIndicesTo(stream);
}
```

### Ver también

* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


