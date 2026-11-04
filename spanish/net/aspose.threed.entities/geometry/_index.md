---
title: "Clase Geometry"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.Geometry. La clase base de todos los objetos geométricos renderizables como Mesh, NurbsSurface, Patch, etc."
type: docs
weight: 410
url: /es/net/aspose.threed.entities/geometry/
---
## Geometry class

La clase base de todos los objetos geométricos renderizables (como [`Mesh`](../mesh/), [`NurbsSurface`](../nurbssurface/), [`Patch`](../patch/) y etc.).

La clase base `Geometry` admite: **Gestión de puntos de control**, los puntos de control definen la estructura espacial 3D base de la geometría, los diferentes tipos geométricos tienen diferentes formas de definir modelos 3D concretos. **Definición de elemento de vértice**, los elementos de vértice aplican información adicional como normales/coordenadas uv/colores de vértice a la geometría, vea [`VertexElement`](../vertexelement/) para más detalles. **Deformación de objetos**, [`Deformer`](../../aspose.threed.deformers/deformer/) puede enlazarse para animar la forma de la geometría.

```csharp
public class Geometry : Entity
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Geometry](geometry/)(string) | Inicializa una nueva instancia de la clase `Geometry`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | Obtiene o establece si esta geometría puede proyectar sombras |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | Obtiene todos los puntos de control |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | Obtiene todos los deformadores asociados con esta geometría. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | Obtiene o establece si esta geometría puede recibir sombra. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Obtiene todos los elementos de vértice |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Obtiene o establece si la geometría es visible |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Agrega un elemento de vértice existente a la geometría actual |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/#createelement)(VertexElementType) | Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/#createelement_1)(VertexElementType, MappingMode, ReferenceMode) | Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/#createelementuv)(TextureMapping) | Crea un [`VertexElementUV`](../vertexelementuv/) con el tipo de mapeado de textura dado. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/#createelementuv_1)(TextureMapping, MappingMode, ReferenceMode) | Crea un [`VertexElementUV`](../vertexelementuv/) con el tipo de mapeado de textura dado. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | Obtiene un elemento de vértice con el tipo especificado |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | Obtiene una instancia de [`VertexElementUV`](../vertexelementuv/) con el tipo de mapeado de textura dado |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


