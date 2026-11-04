---
title: "Clase Sphere"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.Sphere. Esfera parametrizada"
type: docs
weight: 730
url: /es/net/aspose.threed.entities/sphere/
---
## Sphere class

Esfera parametrizada.

```csharp
public class Sphere : Primitive
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Sphere](sphere/#constructor)() | Inicializa una nueva instancia de `Sphere` con radio predeterminado 1. |
| [Sphere](sphere/#constructor_1)(double) | Inicializa una nueva instancia de la clase `Sphere` con el radio especificado. |
| [Sphere](sphere/#constructor_2)(double, int, int) | Inicializa una nueva instancia de la clase `Sphere` con el radio especificado, segmentos de ancho y segmentos de altura. |
| [Sphere](sphere/#constructor_3)(string, double, int, int, double, double, double, double) | Inicializa una nueva instancia de la clase `Sphere`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtiene o establece si esta geometría puede proyectar sombras |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [HeightSegments](../../aspose.threed.entities/sphere/heightsegments/) { get; set; } | Obtiene o establece los segmentos de altura. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [PhiLength](../../aspose.threed.entities/sphere/philength/) { get; set; } | Obtiene o establece la longitud de phi. |
| [PhiStart](../../aspose.threed.entities/sphere/phistart/) { get; set; } | Obtiene o establece el inicio de phi. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Radius](../../aspose.threed.entities/sphere/radius/) { get; set; } | Obtiene o establece el radio de la esfera. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtiene o establece si esta geometría puede recibir sombra. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [ThetaLength](../../aspose.threed.entities/sphere/thetalength/) { get; set; } | Obtiene o establece la longitud de theta. |
| [ThetaStart](../../aspose.threed.entities/sphere/thetastart/) { get; set; } | Obtiene o establece el inicio de theta. |
| [WidthSegments](../../aspose.threed.entities/sphere/widthsegments/) { get; set; } | Obtiene o establece los segmentos de ancho. |

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
| override [ToMesh](../../aspose.threed.entities/sphere/tomesh/)() | Convertir el objeto actual a malla |

### Ver también

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


