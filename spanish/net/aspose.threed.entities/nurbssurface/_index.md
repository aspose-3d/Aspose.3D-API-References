---
title: "Clase NurbsSurface"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.NurbsSurface. NurbsSurface es una superficie representada por NURBS Non-uniform rational basis spline. Una NurbsSurface se define por dos NurbsDirectionU y V. El componente w en el punto de control se usa como peso de los puntos de control, sea cual sea el tipo de dirección, TwoDimensional o ThreeDimensional."
type: docs
weight: 540
url: /es/net/aspose.threed.entities/nurbssurface/
---
## NurbsSurface class

`NurbsSurface` es una superficie representada por [NURBS(Non-uniform rational basis spline)](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline), una `NurbsSurface` se define por dos [`NurbsDirection`](../nurbsdirection/)[`U`](./u/) y [`V`](./v/). El componente w en el punto de control se usa como peso del punto de control, sea cual sea el tipo de dirección, TwoDimensional o ThreeDimensional

```csharp
public class NurbsSurface : Geometry, IMeshConvertible
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [NurbsSurface](nurbssurface/#constructor)() | Inicializa una nueva instancia de la clase `NurbsSurface`. |
| [NurbsSurface](nurbssurface/#constructor_1)(string) | Inicializa una nueva instancia de la clase `NurbsSurface`. |

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
| [U](../../aspose.threed.entities/nurbssurface/u/) { get; } | Obtiene la dirección U de la superficie NURBS |
| [V](../../aspose.threed.entities/nurbssurface/v/) { get; } | Obtiene la dirección V de la superficie NURBS |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Obtiene todos los elementos de vértice |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Obtiene o establece si la geometría es visible |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Agrega un elemento de vértice existente a la geometría actual |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | Crea un [`VertexElementUV`](../vertexelementuv/) con el tipo de mapeado de textura dado. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | Crea un [`VertexElementUV`](../vertexelementuv/) con el tipo de mapeado de textura dado. |
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
| [ToMesh](../../aspose.threed.entities/nurbssurface/tomesh/)() | Convierte la superficie NURBS a la malla |

### Ver también

* class [Geometry](../geometry/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


