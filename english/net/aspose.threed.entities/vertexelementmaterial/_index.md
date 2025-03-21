---
title: Class VertexElementMaterial
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Entities.VertexElementMaterial class. Defines material index for specified components. A node can have multiple materials the VertexElementMaterial is used to render different part of the geometry in different materials
type: docs
weight: 850
url: /net/aspose.threed.entities/vertexelementmaterial/
---
## VertexElementMaterial class

Defines material index for specified components. A node can have multiple materials, the `VertexElementMaterial` is used to render different part of the geometry in different materials.

```csharp
public class VertexElementMaterial : VertexElement
```

## Constructors

| Name | Description |
| --- | --- |
| [VertexElementMaterial](vertexelementmaterial/)() | Initializes a new instance of the `VertexElementMaterial` class. |

## Properties

| Name | Description |
| --- | --- |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | Gets the indices data |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | Gets or sets how the element is mapped. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | Gets or sets the name. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | Gets or sets how the element is referenced. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | Gets the type of the [`VertexElement`](../vertexelement/) |

## Methods

| Name | Description |
| --- | --- |
| override [Clear](../../aspose.threed.entities/vertexelementmaterial/clear/)() | Removes all elements from the direct and the index arrays. |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | Load indices |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | String representation of vertex element. |

## Examples

The following code shows how to assign different material to different face of a box.

```csharp
// Create a mesh of box(A box is composed by 6 planes)
Mesh box = (new Box()).ToMesh();
// Create a material element on this mesh
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// And specify different material index for each plane
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
```

### See Also

* class [VertexElement](../vertexelement/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


