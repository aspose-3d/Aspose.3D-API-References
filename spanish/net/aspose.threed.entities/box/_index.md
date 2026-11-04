---
title: "Clase Box"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.Box. Box"
type: docs
weight: 290
url: /es/net/aspose.threed.entities/box/
---
## Box class

Caja.

```csharp
public class Box : Primitive
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Box](box/#constructor)() | Inicializa una nueva instancia de la clase `Box`. |
| [Box](box/#constructor_1)(double, double, double) | Inicializa una nueva instancia de la clase `Box`. |
| [Box](box/#constructor_2)(string, double, double, double, int, int, int) | Inicializa una nueva instancia de la clase `Box`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtiene o establece si esta geometría puede proyectar sombras |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [Height](../../aspose.threed.entities/box/height/) { get; set; } | Obtiene o establece la altura de la caja alineada en el eje y. |
| [HeightSegments](../../aspose.threed.entities/box/heightsegments/) { get; set; } | Obtiene o establece los segmentos de altura. |
| [Length](../../aspose.threed.entities/box/length/) { get; set; } | Obtiene o establece la longitud de la caja alineada en el eje z. |
| [LengthSegments](../../aspose.threed.entities/box/lengthsegments/) { get; set; } | Obtiene o establece los segmentos de longitud. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtiene o establece si esta geometría puede recibir sombra. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Width](../../aspose.threed.entities/box/width/) { get; set; } | Obtiene o establece el ancho de la caja alineada en el eje x. |
| [WidthSegments](../../aspose.threed.entities/box/widthsegments/) { get; set; } | Obtiene o establece los segmentos de ancho |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |
| override [ToMesh](../../aspose.threed.entities/box/tomesh/)() | Convertir el objeto actual a malla |

### Ver también

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


