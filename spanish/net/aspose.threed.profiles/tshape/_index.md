---
title: "Clase TShape"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Profiles.TShape. Tshape compatible con IFC definido por parámetros"
type: docs
weight: 1810
url: /es/net/aspose.threed.profiles/tshape/
---
## TShape class

Forma en T compatible con IFC definida por parámetros.

```csharp
public class TShape : ParameterizedProfile
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TShape](tshape/)() | Constructor de `TShape` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Depth](../../aspose.threed.profiles/tshape/depth/) { get; set; } | Obtiene o establece la longitud del alma. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [FilletRadius](../../aspose.threed.profiles/tshape/filletradius/) { get; set; } | Obtiene o establece el radio del filete entre el alma y el ala. |
| [FlangeEdgeRadius](../../aspose.threed.profiles/tshape/flangeedgeradius/) { get; set; } | Obtiene o establece el radio del borde del ala. |
| [FlangeThickness](../../aspose.threed.profiles/tshape/flangethickness/) { get; set; } | Obtiene o establece el espesor de pared del ala. |
| [FlangeWidth](../../aspose.threed.profiles/tshape/flangewidth/) { get; set; } | Obtiene o establece la longitud del ala. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [WebEdgeRadius](../../aspose.threed.profiles/tshape/webedgeradius/) { get; set; } | Obtiene o establece el radio del borde del alma. |
| [WebThickness](../../aspose.threed.profiles/tshape/webthickness/) { get; set; } | Obtiene o establece el espesor de pared del alma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| override [GetExtent](../../aspose.threed.profiles/tshape/getextent/)() | Obtiene la extensión en las dimensiones x e y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


