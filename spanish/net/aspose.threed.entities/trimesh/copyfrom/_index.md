---
title: "TriMesh.CopyFrom"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TriMesh. Copiar el TriMesh de la entrada con una nueva disposición de vértices"
type: docs
weight: 20
url: /es/net/aspose.threed.entities/trimesh/copyfrom/
---
## TriMesh.CopyFrom method

Copiar el [`TriMesh`](../) de la entrada con una nueva disposición de vértices

```csharp
public static TriMesh CopyFrom(TriMesh input, VertexDeclaration vd)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entrada | TriMesh | El TriMesh de entrada para copiar |
| vd | VertexDeclaration | La nueva declaración de vértices del TriMesh de salida |

### Valor de retorno

Una nueva instancia de TriMesh con una nueva declaración de vértices.

## Ejemplos

```csharp
//Define una declaración de vértice como {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//convertir una malla a TriMesh, el diseño se infiere automáticamente de la malla de entrada
var oldTriMesh = TriMesh.FromMesh((new Sphere()).ToMesh());
//Ahora crea un nuevo TriMesh a partir del TriMesh antiguo, usando una disposición de memoria explícita definida por vd
var newTriMesh = TriMesh.CopyFrom(oldTriMesh, vd);
```

### Ver también

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


