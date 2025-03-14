---
title: TriMesh.FromRawData
second_title: Aspose.3D for .NET API Reference
description: TriMesh method. Create TriMesh from raw data
type: docs
weight: 40
url: /net/aspose.threed.entities/trimesh/fromrawdata/
---
## TriMesh.FromRawData method

Create TriMesh from raw data

```csharp
public static TriMesh FromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, 
    bool generateVertexMapping)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vd | VertexDeclaration | Vertex declaration, must contains at least one field. |
| vertices | Byte[] | The input vertex data, the minimum length of the vertices must be greater or equal to vertex declaration's size |
| indices | Int32[] | The triangle indices |
| generateVertexMapping | Boolean | Generate [`Vertex`](../../../aspose.threed.utilities/vertex/) for each vertex, which is not necessary for just serialization/deserialization. |

### Return Value

The [`TriMesh`](../) instance that encapsulated the input byte array.

## Remarks

The returned TriMesh will not copy the input byte array for performance, external changes on the array will be reflected to this instance.

## Examples

The following code shows how to construct a TriMesh from raw bytes, this is useful when build your own 3D format

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

### See Also

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


