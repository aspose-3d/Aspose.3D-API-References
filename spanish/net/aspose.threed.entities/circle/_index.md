---
title: Circle
second_title: Referencia de API de Aspose.3D para .NET
description: ACircle./circle la curva consta de un conjunto de puntos en el borde de la forma del círculo.
type: docs
weight: 260
url: /es/net/aspose.threed.entities/circle/
---
## Circle class

A[`Circle`](../circle) la curva consta de un conjunto de puntos en el borde de la forma del círculo.

```csharp
public class Circle : Curve
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Circle](circle#constructor)() | Constructor de[`Circle`](../circle) |
| [Circle](circle#constructor_1)(double) | Constructor de[`Circle`](../circle) |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color) { get; set; } | Obtiene o establece el color de la línea, el valor predeterminado es blanco (1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Obtiene o establece si se excluye esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Obtiene o establece el primer nodo principal; si se establece el primer nodo principal, esta entidad se separará de otros nodos principales. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Obtiene todos los nodos principales, una entidad se puede adjuntar a varios nodos principales para crear instancias de geometría |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtiene la colección de todas las propiedades. |
| [Radius](../../aspose.threed.entities/circle/radius) { get; set; } | El radio de la curva circular, el valor predeterminado es 10 |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Obtiene la escena a la que pertenece este objeto |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey)() | Obtiene la clave del renderizador de entidades registrado en el renderizador |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtener el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Eliminar la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [Curve](../curve)
* espacio de nombres [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
