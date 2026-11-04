---
title: "Clase EllipseShape"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Profiles.EllipseShape. Forma de elipse compatible con IFC definida por parámetros. La posición central del perfil está en el centro del cuadro delimitador"
type: docs
weight: 1710
url: /es/net/aspose.threed.profiles/ellipseshape/
---
## EllipseShape class

Forma elíptica compatible con IFC definida por parámetros. La posición central del perfil está en el centro del cuadro delimitador.

```csharp
public class EllipseShape : ParameterizedProfile
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EllipseShape](ellipseshape/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [SemiAxis1](../../aspose.threed.profiles/ellipseshape/semiaxis1/) { get; set; } | Obtiene o establece el primer radio de la elipse medido en la dirección del eje x. |
| [SemiAxis2](../../aspose.threed.profiles/ellipseshape/semiaxis2/) { get; set; } | Obtiene o establece el segundo radio de la elipse medido en la dirección del eje y. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| override [GetExtent](../../aspose.threed.profiles/ellipseshape/getextent/)() | Obtiene la extensión en las dimensiones x e y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


