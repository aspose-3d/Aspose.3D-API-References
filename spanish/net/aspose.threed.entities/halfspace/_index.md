---
title: "Clase HalfSpace"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Entities.HalfSpace class. HalfSpace representa un espacio infinito que se divide por un plano; esto puede usarse con BooleanOperator"
type: docs
weight: 420
url: /es/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` representa un espacio infinito que se divide por un plano, esto puede usarse con [`BooleanOperator`](../booleanoperator/)

```csharp
public class HalfSpace : Entity
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | Construye una nueva instancia de `HalfSpace` |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | Construye una nueva instancia de `HalfSpace` con el vector normal dado y una posición en el plano de corte; |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | La normal del plano de división, el plano se define como N * P + D = 0 donde N es la Normal y P es cualquier punto en el plano. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | Cualquier punto en el plano de división, el plano se define como N * P + D = 0 donde N es la Normal y P es cualquier punto en el plano. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
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

### Ver también

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


