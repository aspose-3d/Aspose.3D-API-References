---
title: "Clase VertexDeclaration"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Utilities.VertexDeclaration. La declaración de una estructura de vértices definida de forma personalizada"
type: docs
weight: 2910
url: /es/net/aspose.threed.utilities/vertexdeclaration/
---
## VertexDeclaration class

La declaración de la estructura de un vértice definido de forma personalizada

```csharp
public sealed class VertexDeclaration : IComparable<VertexDeclaration>, IEnumerable<VertexField>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VertexDeclaration](vertexdeclaration/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.threed.utilities/vertexdeclaration/count/) { get; } | Obtiene el recuento de todos los campos definidos en este `VertexDeclaration` |
| [Item](../../aspose.threed.utilities/vertexdeclaration/item/) { get; } |  |
| [Sealed](../../aspose.threed.utilities/vertexdeclaration/sealed/) { get; } | Una `VertexDeclaration` se sellará cuando haya sido usada por [`TriMesh`](../../aspose.threed.entities/trimesh-1/) o [`TriMesh`](../../aspose.threed.entities/trimesh/), no se permitirán más modificaciones. |
| [Size](../../aspose.threed.utilities/vertexdeclaration/size/) { get; } | El tamaño en bytes de la estructura de vértices. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/vertexdeclaration/fromgeometry/)(Geometry, bool) | Crea una `VertexDeclaration` basada en el diseño de un [`Geometry`](../../aspose.threed.entities/geometry/). |
| static [FromType&lt;T&gt;](../../aspose.threed.utilities/vertexdeclaration/fromtype/)() |  |
| [AddField](../../aspose.threed.utilities/vertexdeclaration/addfield/)(VertexFieldDataType, VertexFieldSemantic, int, string) | Agregar un nuevo campo de vértice |
| [Clear](../../aspose.threed.utilities/vertexdeclaration/clear/)() | Borrar todos los campos. |
| [CompareTo](../../aspose.threed.utilities/vertexdeclaration/compareto/)(VertexDeclaration) | Compara esta instancia con un objeto especificado y devuelve una indicación de sus valores relativos. |
| override [Equals](../../aspose.threed.utilities/vertexdeclaration/equals/)(object) | Determina si esta instancia y un objeto especificado, que también debe ser un objeto `VertexDeclaration`, tienen el mismo valor. |
| [GetEnumerator](../../aspose.threed.utilities/vertexdeclaration/getenumerator/)() | Obtiene un enumerador para recorrer todos los campos de vértice en esta instancia. |
| override [GetHashCode](../../aspose.threed.utilities/vertexdeclaration/gethashcode/)() | Devuelve el código hash de esta cadena. |
| override [ToString](../../aspose.threed.utilities/vertexdeclaration/tostring/)() | Representación en cadena de `VertexDeclaration` |

### Ver también

* class [VertexField](../vertexfield/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


