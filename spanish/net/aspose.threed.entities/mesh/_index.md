---
title: "Clase Mesh"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.Mesh. Una malla está compuesta de muchos polígonos de n lados"
type: docs
weight: 510
url: /es/net/aspose.threed.entities/mesh/
---
## Mesh class

Una malla está compuesta por muchos polígonos de n lados.

```csharp
public class Mesh : Geometry, IEnumerable<int[]>, IMeshConvertible
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Mesh](mesh/#constructor)() | Inicializa una nueva instancia de la clase `Mesh`. |
| [Mesh](mesh/#constructor_4)(string) | Inicializa una nueva instancia de la clase `Mesh`. |
| [Mesh](mesh/#constructor_1)(TextureData) | Construye una malla usando el mapa de alturas especificado; si el formato de píxel del mapa de alturas contiene múltiples componentes, el primero (normalmente el rojo) se usará como el valor de altura (z). Los componentes x e y del punto de control son coordenadas de píxel normalizadas. |
| [Mesh](mesh/#constructor_2)(TextureData, Matrix4) | Construye una malla usando el mapa de alturas especificado; si el formato de píxel del mapa de alturas contiene múltiples componentes, el primero (normalmente el rojo) se usará como el valor de altura (z). Los componentes x e y del punto de control son coordenadas de píxel normalizadas. |
| [Mesh](mesh/#constructor_3)(TextureData, bool, Matrix4) | Construye una malla usando el mapa de alturas especificado; si el formato de píxel del mapa de alturas contiene múltiples componentes, el primero (normalmente el rojo) se usará como el valor de altura (z). Los componentes x e y del punto de control son coordenadas de píxel normalizadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | Obtiene o establece si esta geometría puede proyectar sombras |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | Obtiene todos los puntos de control |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | Obtiene todos los deformadores asociados con esta geometría. |
| [Edges](../../aspose.threed.entities/mesh/edges/) { get; } | Obtiene los bordes de la malla. El borde es opcional en la malla, por lo que puede estar vacío. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [PolygonCount](../../aspose.threed.entities/mesh/polygoncount/) { get; } | Obtiene el recuento de polígonos |
| [Polygons](../../aspose.threed.entities/mesh/polygons/) { get; } | Obtiene la definición de polígonos de la malla |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | Obtiene o establece si esta geometría puede recibir sombra. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Obtiene todos los elementos de vértice |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Obtiene o establece si la geometría es visible |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [DoBoolean](../../aspose.threed.entities/mesh/doboolean/)(BooleanOperation, Mesh, Matrix4?, Mesh, Matrix4?) |  |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Agrega un elemento de vértice existente a la geometría actual |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | Crea un [`VertexElementUV`](../vertexelementuv/) con el tipo de mapeado de textura dado. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | Crea un [`VertexElementUV`](../vertexelementuv/) con el tipo de mapeado de textura dado. |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_2)(int[]) | Crea un nuevo polígono con todos los vértices definidos en *indices*. Para crear el polígono vértice a vértice, por favor use [`PolygonBuilder`](../polygonbuilder/). |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon)(int, int, int) | Crea un polígono con 3 vértices (triángulo) |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_3)(int[], int, int) | Crea un nuevo polígono con todos los vértices definidos en *indices*. Para crear el polígono vértice a vértice, por favor use [`PolygonBuilder`](../polygonbuilder/). |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_1)(int, int, int, int) | Crea un polígono con 4 vértices (cuadrilátero) |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | Obtiene un elemento de vértice con el tipo especificado |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [GetEnumerator](../../aspose.threed.entities/mesh/getenumerator/)() | Obtiene el enumerador para cada polígono interno. |
| [GetPolygonSize](../../aspose.threed.entities/mesh/getpolygonsize/)(int) | Obtiene el recuento de vértices del polígono especificado. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | Obtiene una instancia de [`VertexElementUV`](../vertexelementuv/) con el tipo de mapeado de textura dado |
| [IsManifold](../../aspose.threed.entities/mesh/ismanifold/)() | Verifica si la malla actual es una malla manifold. Esta función no almacenará en caché el resultado del cálculo manifold. |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize)(bool) | Optimiza el uso de memoria de la malla eliminando puntos de control duplicados |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize_1)(bool, float, float, float) | Optimiza el uso de memoria de la malla eliminando puntos de control duplicados |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |
| [ToMesh](../../aspose.threed.entities/mesh/tomesh/)() | Obtiene la instancia de Mesh de la entidad actual. |
| [Triangulate](../../aspose.threed.entities/mesh/triangulate/)() | Devuelve la malla triangulada |
| [operator &amp;](../../aspose.threed.entities/mesh/op_bitwiseand/) | Calcula la intersección de dos mallas |
| [operator &#x7C;](../../aspose.threed.entities/mesh/op_bitwiseor/) | Calcula la unión de dos mallas |
| [operator -](../../aspose.threed.entities/mesh/op_subtraction/) | Calcular la diferencia de dos mallas |

## Ejemplos

Para agregar un polígono en la malla:

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

Recorrer todos los polígonos en la malla:

```csharp
Mesh mesh = new Mesh();
foreach(int[] polygon in mesh)
{
    //manejar polígono
}
```

### Ver también

* class [Geometry](../geometry/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


