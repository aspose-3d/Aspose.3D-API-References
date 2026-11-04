---
title: "Clase LShape"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Profiles.LShape. Perfil Lshape compatible con IFC definido por parámetros"
type: docs
weight: 1760
url: /es/net/aspose.threed.profiles/lshape/
---
## LShape class

Perfil de forma L compatible con IFC definido por parámetros.

```csharp
public class LShape : ParameterizedProfile
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LShape](lshape/)() | Constructor de `LShape` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Depth](../../aspose.threed.profiles/lshape/depth/) { get; set; } | Obtiene o establece la profundidad del perfil. |
| [EdgeRadius](../../aspose.threed.profiles/lshape/edgeradius/) { get; set; } | Obtiene o establece el radio del borde. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [FilletRadius](../../aspose.threed.profiles/lshape/filletradius/) { get; set; } | Obtiene o establece el radio del filete. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Thickness](../../aspose.threed.profiles/lshape/thickness/) { get; set; } | Obtiene o establece el grosor de la pared constante. |
| [Width](../../aspose.threed.profiles/lshape/width/) { get; set; } | Obtiene o establece el ancho del perfil. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| override [GetExtent](../../aspose.threed.profiles/lshape/getextent/)() | Obtiene la extensión en las dimensiones x e y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


