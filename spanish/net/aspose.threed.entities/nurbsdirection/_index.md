---
title: "Clase NurbsDirection"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.NurbsDirection. Una NurbsSurface 3D tiene dos direcciones, la U y la V; el NurbsDirection define los datos para cada dirección. Una dirección es en realidad una curva NURBS, lo que significa que también está definida por su Order, sus KnotVectors y un conjunto de puntos de control ponderados definidos en NurbsSurface."
type: docs
weight: 530
url: /es/net/aspose.threed.entities/nurbsdirection/
---
## NurbsDirection class

Una [`NurbsSurface`](../nurbssurface/) 3D tiene dos direcciones, la [`U`](../nurbssurface/u/) y la [`V`](../nurbssurface/v/); el `NurbsDirection` define los datos para cada dirección. Una dirección es en realidad una curva NURBS, lo que significa que también está definida por su [`Order`](./order/), sus [`KnotVectors`](./knotvectors/) y un conjunto de puntos de control ponderados (definidos en [`NurbsSurface`](../nurbssurface/)).

```csharp
public class NurbsDirection
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [NurbsDirection](nurbsdirection/)() | Construya una nueva instancia de `NurbsDirection` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.threed.entities/nurbsdirection/count/) { get; set; } | Obtiene o establece el recuento de puntos de control en la dirección actual. |
| [Degree](../../aspose.threed.entities/nurbsdirection/degree/) { get; set; } | Obtiene o establece el grado de una curva NURBS, el grado se define como Orden - 1 |
| [Divisions](../../aspose.threed.entities/nurbsdirection/divisions/) { get; set; } | Obtiene o establece el número de divisiones entre puntos de control adyacentes en la dirección actual. |
| [KnotVectors](../../aspose.threed.entities/nurbsdirection/knotvectors/) { get; } | Obtiene el vector de nudos, es una secuencia de valores de parámetro que determina dónde y cómo los puntos de control afectan a la curva NURBS. |
| [Multiplicity](../../aspose.threed.entities/nurbsdirection/multiplicity/) { get; } | Obtiene la multiplicidad. |
| [Order](../../aspose.threed.entities/nurbsdirection/order/) { get; set; } | Obtiene o establece el orden de una curva NURBS, define el número de puntos de control cercanos que influyen en cualquier punto de la curva. |
| [Type](../../aspose.threed.entities/nurbsdirection/type/) { get; set; } | Obtiene o establece el tipo de la dirección actual. |

### Ver también

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


