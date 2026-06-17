---
title: from_mesh method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 70
url: /el/python-net/aspose.threed.entities/trimesh/from_mesh/
is_root: false
---

## from_mesh(, declaration, mesh) {#aspose.threed.utilities.VertexDeclaration-aspose.threed.entities.Mesh}

Create a TriMesh from given mesh object with given vertex layout.


### Returns 


Instance of TriMesh converted from input mesh with specified vertex's memory layout


```python

@staticmethod
def from_mesh(declaration, mesh):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| declaration | aspose.threed.utilities.VertexDeclaration | Vertex's type definition, or memory layout |
| mesh | aspose.threed.entities.Mesh | Source mesh |

### Example 


The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```python
from aspose.threed.entities import Sphere, TriMesh
from aspose.threed.utilities import VertexDeclaration, VertexFieldDataType, VertexFieldSemantic

# Ορίστε μια δήλωση κορυφής ως {FVector3 Position; FVector3 Normal; FVector2 UV}
vd = VertexDeclaration()
vd.add_field(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION)
vd.add_field(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL)
vd.add_field(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV)
# μετατρέψτε ένα πλέγμα σε τρι-πλέγμα χρησιμοποιώντας την καθορισμένη διάταξη μνήμης
mesh = Sphere().to_mesh()
triMesh = TriMesh.from_mesh(vd, mesh)
# αποθηκεύστε το σε ροή, 115 κορυφές * 32 bytes ανά κορυφή
with open("output.bin", "wb") as stream:
    triMesh.write_vertices_to(stream)
    # αποθηκεύστε τα ευρετήρια ως ushort σε ροή, 504 ευρετήρια * 2 bytes ανά ευρετήριο
    triMesh.write_16b_indices_to(stream)

```


## from_mesh(, mesh, use_float) {#aspose.threed.entities.Mesh-bool}

Create a TriMesh from given mesh object, the vertex declaration are based on the input mesh's structure.


### Returns 


The [`TriMesh`](/3d/python-net/aspose.threed.entities/trimesh) generated from given [`Mesh`](/3d/python-net/aspose.threed.entities/mesh)


```python

@staticmethod
def from_mesh(mesh, use_float):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| mesh | aspose.threed.entities.Mesh |  |
| use_float | bool | Use float type instead of double type for each vertex element component. |

### Example 


The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```python
from aspose.threed.entities import Sphere, TriMesh
from aspose.threed.utilities import VertexDeclaration, VertexFieldDataType, VertexFieldSemantic

# Ορίστε μια δήλωση κορυφής ως {FVector3 Position; FVector3 Normal; FVector2 UV}
vd = VertexDeclaration()
vd.add_field(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION)
vd.add_field(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL)
vd.add_field(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV)
# μετατρέψτε ένα πλέγμα σε τρι-πλέγμα χρησιμοποιώντας την καθορισμένη διάταξη μνήμης
mesh = Sphere().to_mesh()
triMesh = TriMesh.from_mesh(vd, mesh)
# αποθηκεύστε το σε ροή, 115 κορυφές * 32 bytes ανά κορυφή
with open("output.bin", "wb") as stream:
    triMesh.write_vertices_to(stream)
    # αποθηκεύστε τα ευρετήρια ως ushort σε ροή, 504 ευρετήρια * 2 bytes ανά ευρετήριο
    triMesh.write_16b_indices_to(stream)

```



### See Also
* module [`aspose.threed.entities`](../../)
* class [`Mesh`](/3d/python-net/aspose.threed.entities/mesh)
* class [`TriMesh`](/3d/python-net/aspose.threed.entities/trimesh)
