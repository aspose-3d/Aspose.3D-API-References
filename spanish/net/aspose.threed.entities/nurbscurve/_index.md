---
title: "Clase NurbsCurve"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.NurbsCurve. Una curva NURBS es una curva representada por NURBSNonuniform rational basis spline. Una curva NURBS se define por su Order, un conjunto de ControlPoints ponderados y un KnotVectors. El componente w en el punto de control se utiliza como peso del punto de control, sea TwoDimensional o ThreeDimensional."
type: docs
weight: 520
url: /es/net/aspose.threed.entities/nurbscurve/
---
## NurbsCurve class

[NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [`Order`](./order/), a set of weighted [`ControlPoints`](../geometry/controlpoints/) and a [`KnotVectors`](./knotvectors/) The w component in control point is used as control point's weight, whatever it is a TwoDimensional or ThreeDimensional

```csharp
public class NurbsCurve : Curve
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [NurbsCurve](nurbscurve/#constructor)() | Inicializa una nueva instancia de la clase `NurbsCurve`. |
| [NurbsCurve](nurbscurve/#constructor_1)(string) | Inicializa una nueva instancia de la clase `NurbsCurve`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Obtiene o establece el color de la línea, el valor predeterminado es blanco(1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/nurbscurve/controlpoints/) { get; } | Obtiene todos los puntos de control |
| [CurveType](../../aspose.threed.entities/nurbscurve/curvetype/) { get; set; } | Obtiene o establece el tipo de la curva. |
| [Degree](../../aspose.threed.entities/nurbscurve/degree/) { get; set; } | Obtiene o establece el grado de una curva NURBS, el grado se define como Orden - 1 |
| [Dimension](../../aspose.threed.entities/nurbscurve/dimension/) { get; set; } | Obtiene o establece la dimensión de la curva. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [KnotVectors](../../aspose.threed.entities/nurbscurve/knotvectors/) { get; } | Obtiene el vector de nudos, es una secuencia de valores de parámetro que determina dónde y cómo los puntos de control afectan a la curva NURBS. |
| [Multiplicity](../../aspose.threed.entities/nurbscurve/multiplicity/) { get; } | Obtiene la multiplicidad. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Order](../../aspose.threed.entities/nurbscurve/order/) { get; set; } | Obtiene o establece el orden de una curva NURBS, define el número de puntos de control cercanos que influyen en cualquier punto de la curva. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Rational](../../aspose.threed.entities/nurbscurve/rational/) { get; set; } | Obtiene o establece si es racional, este valor indica si este `NurbsCurve` es una spline racional o una spline no racional. La B-spline no racional es un caso especial de B-splines racionales. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Evaluate](../../aspose.threed.entities/nurbscurve/evaluate/)(int) | Evaluar la curva NURBS |
| [EvaluateAt](../../aspose.threed.entities/nurbscurve/evaluateat/)(double) | Evaluar el punto de la curva en la posición especificada |
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


