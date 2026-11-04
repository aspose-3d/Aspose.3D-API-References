---
title: "Clase ZShape"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Profiles.ZShape. Perfil Zshape compatible con IFC definido por parámetros"
type: docs
weight: 1850
url: /es/net/aspose.threed.profiles/zshape/
---
## ZShape class

Perfil en forma Z compatible con IFC definido por parámetros.

```csharp
public class ZShape : ParameterizedProfile
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ZShape](zshape/)() | Constructor de `ZShape` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Depth](../../aspose.threed.profiles/zshape/depth/) { get; set; } | Obtiene o establece la longitud del web. |
| [EdgeRadius](../../aspose.threed.profiles/zshape/edgeradius/) { get; set; } | Obtiene o establece el radio del borde de la brida. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [FilletRadius](../../aspose.threed.profiles/zshape/filletradius/) { get; set; } | Obtiene o establece el radio del filete entre la brida y el web. |
| [FlangeThickness](../../aspose.threed.profiles/zshape/flangethickness/) { get; set; } | Obtiene o establece el espesor de la brida. |
| [FlangeWidth](../../aspose.threed.profiles/zshape/flangewidth/) { get; set; } | Obtiene o establece la longitud de la brida. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [WebThickness](../../aspose.threed.profiles/zshape/webthickness/) { get; set; } | Obtiene o establece el espesor de la pared. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| override [GetExtent](../../aspose.threed.profiles/zshape/getextent/)() | Obtiene la extensión en las dimensiones x e y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


