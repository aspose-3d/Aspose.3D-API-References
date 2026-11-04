---
title: "Clase RectangularTorus"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.RectangularTorus. Toro rectangular parametrizado"
type: docs
weight: 660
url: /es/net/aspose.threed.entities/rectangulartorus/
---
## RectangularTorus class

Toro rectangular parametrizado.

```csharp
public class RectangularTorus : Primitive
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RectangularTorus](rectangulartorus/#constructor)() | Constructor de `RectangularTorus` |
| [RectangularTorus](rectangulartorus/#constructor_1)(string) | Constructor de `RectangularTorus` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AngleStart](../../aspose.threed.entities/rectangulartorus/anglestart/) { get; set; } | El ángulo inicial del arco, medido en radianes. El valor predeterminado es 0 |
| [Arc](../../aspose.threed.entities/rectangulartorus/arc/) { get; set; } | El ángulo total del arco, medido en radianes. El valor predeterminado es PI |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtiene o establece si esta geometría puede proyectar sombras |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [Height](../../aspose.threed.entities/rectangulartorus/height/) { get; set; } | La altura del toro rectangular. El valor predeterminado es 20 |
| [InnerRadius](../../aspose.threed.entities/rectangulartorus/innerradius/) { get; set; } | El radio interno del toro rectangular. El valor predeterminado es 17 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [OuterRadius](../../aspose.threed.entities/rectangulartorus/outerradius/) { get; set; } | El radio externo del toro rectangular. El valor predeterminado es 20 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [RadialSegments](../../aspose.threed.entities/rectangulartorus/radialsegments/) { get; set; } | Los segmentos radiales, el valor predeterminado es 10 |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtiene o establece si esta geometría puede recibir sombra. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |

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
| override [ToMesh](../../aspose.threed.entities/rectangulartorus/tomesh/)() | Convertir este primitivo a [`Mesh`](../mesh/) |

### Ver también

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


