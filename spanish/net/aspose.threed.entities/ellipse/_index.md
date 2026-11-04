---
title: "Clase Ellipse"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.Ellipse. Una Ellipse define un conjunto de puntos que forman la forma de una elipse"
type: docs
weight: 380
url: /es/net/aspose.threed.entities/ellipse/
---
## Ellipse class

Una `Ellipse` define un conjunto de puntos que forman la forma de una elipse.

```csharp
public class Ellipse : Curve
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Ellipse](ellipse/#constructor)() | Constructor de `Ellipse` |
| [Ellipse](ellipse/#constructor_1)(double, double) | Constructor de `Ellipse` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Obtiene o establece el color de la línea, el valor predeterminado es blanco(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [SemiAxis1](../../aspose.threed.entities/ellipse/semiaxis1/) { get; set; } | Radio en el eje X |
| [SemiAxis2](../../aspose.threed.entities/ellipse/semiaxis2/) { get; set; } | Radio en el eje Y |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


