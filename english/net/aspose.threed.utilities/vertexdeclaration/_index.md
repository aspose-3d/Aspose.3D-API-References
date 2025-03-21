---
title: Class VertexDeclaration
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Utilities.VertexDeclaration class. The declaration of a custom defined vertexs structure
type: docs
weight: 2810
url: /net/aspose.threed.utilities/vertexdeclaration/
---
## VertexDeclaration class

The declaration of a custom defined vertex's structure

```csharp
public sealed class VertexDeclaration : IComparable<VertexDeclaration>, IEnumerable<VertexField>
```

## Constructors

| Name | Description |
| --- | --- |
| [VertexDeclaration](vertexdeclaration/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.threed.utilities/vertexdeclaration/count/) { get; } | Gets the count of all fields defined in this `VertexDeclaration` |
| [Item](../../aspose.threed.utilities/vertexdeclaration/item/) { get; } |  |
| [Sealed](../../aspose.threed.utilities/vertexdeclaration/sealed/) { get; } | A `VertexDeclaration` will be sealed when its been used by [`TriMesh`](../../aspose.threed.entities/trimesh-1/) or [`TriMesh`](../../aspose.threed.entities/trimesh/), no more modifications is allowed. |
| [Size](../../aspose.threed.utilities/vertexdeclaration/size/) { get; } | The size in byte of the vertex structure. |

## Methods

| Name | Description |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/vertexdeclaration/fromgeometry/)(Geometry, bool) | Create a `VertexDeclaration` based on a [`Geometry`](../../aspose.threed.entities/geometry/)'s layout. |
| static [FromType&lt;T&gt;](../../aspose.threed.utilities/vertexdeclaration/fromtype/)() |  |
| [AddField](../../aspose.threed.utilities/vertexdeclaration/addfield/)(VertexFieldDataType, VertexFieldSemantic, int, string) | Add a new vertex field |
| [Clear](../../aspose.threed.utilities/vertexdeclaration/clear/)() | Clear all fields. |
| [CompareTo](../../aspose.threed.utilities/vertexdeclaration/compareto/)(VertexDeclaration) | Compares this instance to a specified object and returns an indication of their relative values. |
| override [Equals](../../aspose.threed.utilities/vertexdeclaration/equals/)(object) | Determines whether this instance and a specified object, which must also be a `VertexDeclaration` object, have the same value. |
| [GetEnumerator](../../aspose.threed.utilities/vertexdeclaration/getenumerator/)() | Gets an enumerator to walk through all vertex fields in this instance. |
| override [GetHashCode](../../aspose.threed.utilities/vertexdeclaration/gethashcode/)() | Returns the hash code for this string. |
| override [ToString](../../aspose.threed.utilities/vertexdeclaration/tostring/)() | String representation of `VertexDeclaration` |

### See Also

* class [VertexField](../vertexfield/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


