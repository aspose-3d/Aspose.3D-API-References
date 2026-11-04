---
title: "Clase UShape"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Profiles.UShape. Ushape compatible con IFC definido por parámetros"
type: docs
weight: 1840
url: /es/net/aspose.threed.profiles/ushape/
---
## UShape class

Forma en U compatible con IFC definida por parámetros.

```csharp
public class UShape : ParameterizedProfile
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [UShape](ushape/)() | Constructor de `UShape` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Depth](../../aspose.threed.profiles/ushape/depth/) { get; set; } | Obtiene o establece la longitud del web. |
| [EdgeRadius](../../aspose.threed.profiles/ushape/edgeradius/) { get; set; } | Obtiene o establece el radio del borde en el borde de la brida. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [FilletRadius](../../aspose.threed.profiles/ushape/filletradius/) { get; set; } | Obtiene o establece el radio del filete entre la brida y el web. |
| [FlangeThickness](../../aspose.threed.profiles/ushape/flangethickness/) { get; set; } | Obtiene o establece el espesor de la brida. |
| [FlangeWidth](../../aspose.threed.profiles/ushape/flangewidth/) { get; set; } | Obtiene o establece la longitud de la brida. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [WebThickness](../../aspose.threed.profiles/ushape/webthickness/) { get; set; } | Obtiene o establece el grosor del alma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| override [GetExtent](../../aspose.threed.profiles/ushape/getextent/)() | Obtiene la extensión en las dimensiones x e y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


