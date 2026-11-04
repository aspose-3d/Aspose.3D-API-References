---
title: "Clase Skeleton"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.Skeleton. El Skeleton se utiliza principalmente en software CAD para ayudar al diseñador a manipular la transformación de la estructura esquelética; suele ser inútil fuera de los softwares CAD. Para que la jerarquía del esqueleto actúe como un solo objeto en el software CAD, es necesario marcar el nodo Skeleton superior como la raíz estableciendo Type a Skeleton y configurando todos los hijos como Bone."
type: docs
weight: 710
url: /es/net/aspose.threed.entities/skeleton/
---
## Skeleton class

El `Skeleton` se utiliza principalmente en software CAD para ayudar al diseñador a manipular la transformación de la estructura esquelética; suele ser inútil fuera de los softwares CAD. Para que la jerarquía del esqueleto actúe como un solo objeto en el software CAD, es necesario marcar el nodo `Skeleton` superior como la raíz estableciendo [`Type`](./type/) a Skeleton, y configurando todos los hijos como Bone.

```csharp
public class Skeleton : Entity
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Skeleton](skeleton/#constructor)() | Inicializa una nueva instancia de la clase `Skeleton`. |
| [Skeleton](skeleton/#constructor_1)(string) | Inicializa una nueva instancia de la clase `Skeleton`. |
| [Skeleton](skeleton/#constructor_2)(string, SkeletonType) | Inicializa una nueva instancia de la clase `Skeleton`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Size](../../aspose.threed.entities/skeleton/size/) { get; set; } | Obtiene o establece el tamaño del nodo de extremidad que se usa en el software CAD para representar el tamaño del hueso. |
| [Type](../../aspose.threed.entities/skeleton/type/) { get; set; } | Obtiene o establece el tipo del esqueleto. |

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


