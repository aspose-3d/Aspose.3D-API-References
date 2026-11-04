---
title: "Clase TriMeshT"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Entities.TriMesh1T class. Versión genérica de TriMesh para el tipo de vértice estáticamente definido por el usuario"
type: docs
weight: 800
url: /es/net/aspose.threed.entities/trimesh-1/
---
## TriMesh&lt;T&gt; class

Versión genérica de [`TriMesh`](../trimesh/) para el tipo de vértice estáticamente definido por el usuario

```csharp
public class TriMesh<T> : TriMesh
    where T : struct
```

| Parámetro | Descripción |
| --- | --- |
| T |  |

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TriMesh](trimesh/)(string) | Inicializa una instancia de [`TriMesh`](../trimesh/) |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Capacity](../../aspose.threed.entities/trimesh/capacity/) { get; } | La capacidad de los vértices preasignados. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [IndicesCount](../../aspose.threed.entities/trimesh/indicescount/) { get; } | El número de índices en este [`TriMesh`](../trimesh/) |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [UnmergedVerticesCount](../../aspose.threed.entities/trimesh/unmergedverticescount/) { get; } | El número de vértices no fusionados que se pasaron mediante [`BeginVertex`](../trimesh/beginvertex/) y [`EndVertex`](../trimesh/endvertex/). |
| [VertexDeclaration](../../aspose.threed.entities/trimesh/vertexdeclaration/) { get; } | El diseño de vértices del [`TriMesh`](../trimesh/). |
| [VerticesCount](../../aspose.threed.entities/trimesh/verticescount/) { get; } | El número de vértices en este [`TriMesh`](../trimesh/) |
| [VerticesSizeInBytes](../../aspose.threed.entities/trimesh/verticessizeinbytes/) { get; } | El tamaño total de todos los vértices en bytes |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromMesh](../../aspose.threed.entities/trimesh-1/frommesh/)(Mesh) | Crea un TriMesh a partir del objeto malla dado con un diseño de vértices generado automáticamente. |
| [AddTriangle](../../aspose.threed.entities/trimesh/addtriangle/)(int, int, int) | Agregar un nuevo triángulo |
| [BeginVertex](../../aspose.threed.entities/trimesh/beginvertex/)() | Comenzar a agregar vértice |
| [EndVertex](../../aspose.threed.entities/trimesh/endvertex/)() | Finalizar la adición de vértice |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [GetEnumerator](../../aspose.threed.entities/trimesh/getenumerator/)() | Obtener el enumerador para enumerar [`Vertex`](../../aspose.threed.utilities/vertex/) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/)(out int[]) |  |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/)(out ushort[]) |  |
| [LoadVerticesFromBytes](../../aspose.threed.entities/trimesh/loadverticesfrombytes/)(byte[]) | Cargar vértices desde bytes, la longitud de los bytes debe ser un múltiplo entero del tamaño del vértice. |
| [ReadDouble](../../aspose.threed.entities/trimesh/readdouble/)(int, VertexField) | Leer el campo double |
| [ReadFloat](../../aspose.threed.entities/trimesh/readfloat/)(int, VertexField) | Leer el campo float |
| [ReadFVector2](../../aspose.threed.entities/trimesh/readfvector2/)(int, VertexField) | Leer el campo vector2 |
| [ReadFVector3](../../aspose.threed.entities/trimesh/readfvector3/)(int, VertexField) | Leer el campo vector3 |
| [ReadFVector4](../../aspose.threed.entities/trimesh/readfvector4/)(int, VertexField) | Leer el campo vector4 |
| [ReadVector2](../../aspose.threed.entities/trimesh/readvector2/)(int, VertexField) | Leer el campo vector2 |
| [ReadVector3](../../aspose.threed.entities/trimesh/readvector3/)(int, VertexField) | Leer el campo vector3 |
| [ReadVector4](../../aspose.threed.entities/trimesh/readvector4/)(int, VertexField) | Leer el campo vector4 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |
| override [ToString](../../aspose.threed.entities/trimesh/tostring/)() | Obtiene la representación en cadena de [`TriMesh`](../trimesh/) |
| [VerticesToArray](../../aspose.threed.entities/trimesh/verticestoarray/)() | Convertir los datos de los vértices a una matriz de bytes |
| [VerticesToTypedArray](../../aspose.threed.entities/trimesh-1/verticestotypedarray/)() | Convierte los datos de los vértices a una matriz tipada |
| [Write16bIndicesTo](../../aspose.threed.entities/trimesh/write16bindicesto/)(Stream) | Escribir los datos de índices como entero de 16 bits al flujo |
| [Write32bIndicesTo](../../aspose.threed.entities/trimesh/write32bindicesto/)(Stream) | Escribe los datos de índices como entero de 32 bits al flujo |
| [WriteVerticesTo](../../aspose.threed.entities/trimesh/writeverticesto/)(Stream) | Escribe los datos de vértices al flujo especificado |

### Ver también

* class [TriMesh](../trimesh/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


