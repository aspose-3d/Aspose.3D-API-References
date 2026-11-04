---
title: "Clase HollowRectangleShape"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Profiles.HollowRectangleShape. Forma rectangular hueca compatible con IFC con esquinas redondeadas internas/externas."
type: docs
weight: 1750
url: /es/net/aspose.threed.profiles/hollowrectangleshape/
---
## HollowRectangleShape class

Forma rectangular hueca compatible con IFC con esquinas redondeadas internas/externas.

```csharp
public class HollowRectangleShape : RectangleShape
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HollowRectangleShape](hollowrectangleshape/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [InnerFilletRadius](../../aspose.threed.profiles/hollowrectangleshape/innerfilletradius/) { get; set; } | El radio de filete interno del rectángulo interno. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [RoundingRadius](../../aspose.threed.profiles/rectangleshape/roundingradius/) { get; set; } | Obtiene o establece el radio de los arcos circulares de las cuatro esquinas, medido en grados. El valor predeterminado es 0.0 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [WallThickness](../../aspose.threed.profiles/hollowrectangleshape/wallthickness/) { get; set; } | El grosor entre el contorno del rectángulo y el agujero interno |
| [XDim](../../aspose.threed.profiles/rectangleshape/xdim/) { get; set; } | Obtiene o establece la extensión del rectángulo en la dirección del eje x. El valor predeterminado es 2.0 |
| [YDim](../../aspose.threed.profiles/rectangleshape/ydim/) { get; set; } | Obtiene o establece la extensión del rectángulo en la dirección del eje y. El valor predeterminado es 2.0 |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| override [GetExtent](../../aspose.threed.profiles/rectangleshape/getextent/)() | Obtiene la extensión en las dimensiones x e y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [RectangleShape](../rectangleshape/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


