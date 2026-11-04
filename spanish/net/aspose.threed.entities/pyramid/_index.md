---
title: "Clase Pyramid"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.Pyramid. Pirámide parametrizada"
type: docs
weight: 650
url: /es/net/aspose.threed.entities/pyramid/
---
## Pyramid class

Pirámide parametrizada.

```csharp
public class Pyramid : Primitive
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Pyramid](pyramid/#constructor)() | Construye una nueva instancia de pirámide con el área inferior predeterminada(10, 10) y la altura predeterminada(5) |
| [Pyramid](pyramid/#constructor_1)(double, double, double) | Construye una nueva instancia de pirámide con el área inferior especificada |
| [Pyramid](pyramid/#constructor_2)(double, double, double, double, double) | Construye una nueva instancia de pirámide con el área inferior y el área superior especificadas y la altura. |
| [Pyramid](pyramid/#constructor_3)(string, double, double, double, double, double) | Construye una nueva instancia de pirámide con el área inferior y el área superior especificadas y la altura. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BottomArea](../../aspose.threed.entities/pyramid/bottomarea/) { get; set; } | Área de la tapa inferior |
| [BottomOffset](../../aspose.threed.entities/pyramid/bottomoffset/) { get; set; } | Desplazamiento para los vértices inferiores |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtiene o establece si esta geometría puede proyectar sombras |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [Height](../../aspose.threed.entities/pyramid/height/) { get; set; } | Altura de la pirámide |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtiene o establece si esta geometría puede recibir sombra. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [TopArea](../../aspose.threed.entities/pyramid/toparea/) { get; set; } | Área de la tapa superior |

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
| override [ToMesh](../../aspose.threed.entities/pyramid/tomesh/)() | Convertir el objeto actual a malla |

### Ver también

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


