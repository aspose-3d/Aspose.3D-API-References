---
title: "Clase TrapeziumShape"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Profiles.TrapeziumShape. Forma Trapezium compatible con IFC definida por parámetros"
type: docs
weight: 1830
url: /es/net/aspose.threed.profiles/trapeziumshape/
---
## TrapeziumShape class

Forma de trapecio compatible con IFC definida por parámetros.

```csharp
public class TrapeziumShape : ParameterizedProfile
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TrapeziumShape](trapeziumshape/)() | Constructor de `TrapeziumShape` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BottomXDim](../../aspose.threed.profiles/trapeziumshape/bottomxdim/) { get; set; } | Obtiene o establece la extensión de la línea inferior medida a lo largo del eje x. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [TopXDim](../../aspose.threed.profiles/trapeziumshape/topxdim/) { get; set; } | Obtiene o establece la extensión de la línea superior medida a lo largo del eje x. |
| [TopXOffset](../../aspose.threed.profiles/trapeziumshape/topxoffset/) { get; set; } | Obtiene o establece el desplazamiento desde el inicio de la línea superior hasta la línea inferior. |
| [YDim](../../aspose.threed.profiles/trapeziumshape/ydim/) { get; set; } | Obtiene o establece la distancia entre las líneas superior e inferior medida a lo largo del eje y. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| override [GetExtent](../../aspose.threed.profiles/trapeziumshape/getextent/)() | Obtiene la extensión en las dimensiones x e y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


