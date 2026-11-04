---
title: "Clase RectangleShape"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Profiles.RectangleShape. Forma rectangular compatible con IFC con esquinas redondeadas"
type: docs
weight: 1800
url: /es/net/aspose.threed.profiles/rectangleshape/
---
## RectangleShape class

Forma rectangular compatible con IFC con esquinas redondeadas.

```csharp
public class RectangleShape : ParameterizedProfile
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RectangleShape](rectangleshape/#constructor)() | Constructor de `RectangleShape` |
| [RectangleShape](rectangleshape/#constructor_1)(double, double) | Constructor de `RectangleShape` con dimensiones especificadas en los ejes x e y. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [RoundingRadius](../../aspose.threed.profiles/rectangleshape/roundingradius/) { get; set; } | Obtiene o establece el radio de los arcos circulares de las cuatro esquinas, medido en grados. El valor predeterminado es 0.0 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
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

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


