---
title: "Clase Plane"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.Plane. Plano parametrizado"
type: docs
weight: 590
url: /es/net/aspose.threed.entities/plane/
---
## Plane class

Plano parametrizado.

```csharp
public class Plane : Primitive
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Plane](plane/#constructor)() | Inicializa una nueva instancia de `Plane` con tamaño predeterminado 1x1. |
| [Plane](plane/#constructor_1)(double, double) | Inicializa una nueva instancia de `Plane`. |
| [Plane](plane/#constructor_2)(string, double, double, int, int) | Inicializa una nueva instancia de `Plane`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtiene o establece si esta geometría puede proyectar sombras |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [Length](../../aspose.threed.entities/plane/length/) { get; set; } | Obtiene o establece la longitud del plano. |
| [LengthSegments](../../aspose.threed.entities/plane/lengthsegments/) { get; set; } | Obtiene o establece los segmentos de longitud. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtiene o establece si esta geometría puede recibir sombra. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Up](../../aspose.threed.entities/plane/up/) { get; set; } | Obtiene o establece el vector ascendente del plano, el valor predeterminado es (0, 1, 0), esto afecta la generación del plano. |
| [Width](../../aspose.threed.entities/plane/width/) { get; set; } | Obtiene o establece el ancho del plano. |
| [WidthSegments](../../aspose.threed.entities/plane/widthsegments/) { get; set; } | Obtiene o establece los segmentos de ancho. |

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
| override [ToMesh](../../aspose.threed.entities/plane/tomesh/)() | Convertir el objeto actual a malla |

### Ver también

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


