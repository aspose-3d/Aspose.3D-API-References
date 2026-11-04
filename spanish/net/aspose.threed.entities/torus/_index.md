---
title: "Clase Torus"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.Torus. Toro parametrizado."
type: docs
weight: 770
url: /es/net/aspose.threed.entities/torus/
---
## Torus class

Toro parametrizado.

```csharp
public class Torus : Primitive
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Torus](torus/#constructor)() | Inicializa una nueva instancia de la clase `Torus`. |
| [Torus](torus/#constructor_1)(double, double) | Inicializa una nueva instancia de la clase `Torus`. |
| [Torus](torus/#constructor_2)(double, double, double) | Inicializa una nueva instancia de la clase `Torus`. |
| [Torus](torus/#constructor_3)(string, double, double, int, int, double) | Inicializa una nueva instancia de la clase `Torus`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Arc](../../aspose.threed.entities/torus/arc/) { get; set; } | Obtiene o establece el arco. |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtiene o establece si esta geometría puede proyectar sombras |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [RadialSegments](../../aspose.threed.entities/torus/radialsegments/) { get; set; } | Obtiene o establece los segmentos radiales. |
| [Radius](../../aspose.threed.entities/torus/radius/) { get; set; } | Obtiene o establece el radio del torus. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtiene o establece si esta geometría puede recibir sombra. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Tube](../../aspose.threed.entities/torus/tube/) { get; set; } | Obtiene o establece el radio del tubo. |
| [TubularSegments](../../aspose.threed.entities/torus/tubularsegments/) { get; set; } | Obtiene o establece los segmentos tubulares. |

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
| override [ToMesh](../../aspose.threed.entities/torus/tomesh/)() | Convertir el objeto actual a malla |

### Ver también

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


