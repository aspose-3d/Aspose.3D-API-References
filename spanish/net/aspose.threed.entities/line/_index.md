---
title: "Clase Line"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.Line. Una polilínea es una ruta definida por un conjunto de puntos con ControlPoints y conectada por Segments, lo que significa que también puede ser un conjunto de segmentos de línea conectados. La línea suele ser un objeto lineal, lo que significa que no puede usarse para representar una curva; para representar una curva se utiliza NurbsCurve."
type: docs
weight: 480
url: /es/net/aspose.threed.entities/line/
---
## Line class

Una polilínea es una ruta definida por un conjunto de puntos con [`ControlPoints`](../geometry/controlpoints/), y conectada por [`Segments`](./segments/), lo que significa que también puede ser un conjunto de segmentos de línea conectados. La línea suele ser un objeto lineal, lo que significa que no puede usarse para representar una curva; para representar una curva, se usa [`NurbsCurve`](../nurbscurve/).

```csharp
public class Line : Curve
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Line](line/#constructor)() | Inicializa una nueva instancia de la clase `Line`. |
| [Line](line/#constructor_1)(string) | Inicializa una nueva instancia de la clase `Line`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Obtiene o establece el color de la línea, el valor predeterminado es blanco(1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/line/controlpoints/) { get; } | Obtiene todos los puntos de control |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Segments](../../aspose.threed.entities/line/segments/) { get; } | Obtiene los segmentos de la línea |
| [Visible](../../aspose.threed.entities/line/visible/) { get; set; } | Obtiene o establece si la geometría es visible |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromPoints](../../aspose.threed.entities/line/frompoints/)(params Vector3[]) | Construye una instancia de `Line` a partir de un conjunto de puntos. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [MakeDefaultIndices](../../aspose.threed.entities/line/makedefaultindices/)() | Genera la secuencia 0,1,2,3....[`ControlPoints`](../geometry/controlpoints/).Length-1 a [`Segments`](./segments/) para que los ControlPoints puedan usarse como una sola línea. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


