---
title: NurbsDirection
second_title: Referencia de API de Aspose.3D para .NET
description: Un 3DNurbsSurface./nurbssurface tiene dos direcciones laU./nurbssurface/u yV./nurbssurface/v  laNurbsDirection./nurbsdirection define datos para cada dirección. Una dirección es en realidad una curva NURBS eso significa que también está definida por suOrder./nurbsdirection/order  aKnotVectors./nurbsdirection/knotvectors  y un conjunto de puntos de control ponderados definidos enNurbsSurface./nurbssurface .
type: docs
weight: 470
url: /es/net/aspose.threed.entities/nurbsdirection/
---
## NurbsDirection class

Un 3D[`NurbsSurface`](../nurbssurface) tiene dos direcciones, la[`U`](../nurbssurface/u) y[`V`](../nurbssurface/v) , la[`NurbsDirection`](../nurbsdirection) define datos para cada dirección. Una dirección es en realidad una curva NURBS, eso significa que también está definida por su[`Order`](./order) , a[`KnotVectors`](./knotvectors) , y un conjunto de puntos de control ponderados (definidos en[`NurbsSurface`](../nurbssurface) ).

```csharp
public class NurbsDirection
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [NurbsDirection](nurbsdirection)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.threed.entities/nurbsdirection/count) { get; set; } | Obtiene o establece el recuento de puntos de control en la dirección actual. |
| [Divisions](../../aspose.threed.entities/nurbsdirection/divisions) { get; set; } | Obtiene o establece el número de divisiones entre puntos de control adyacentes en la dirección actual. |
| [KnotVectors](../../aspose.threed.entities/nurbsdirection/knotvectors) { get; } | Obtiene el vector nudo, es una secuencia de valores de parámetros que determina dónde y cómo afectan los puntos de control a la curva NURBS. |
| [Multiplicity](../../aspose.threed.entities/nurbsdirection/multiplicity) { get; } | Obtiene la multiplicidad. |
| [Order](../../aspose.threed.entities/nurbsdirection/order) { get; set; } | Obtiene o establece el orden de una curva NURBS, define el número de puntos de control cercanos que influyen en cualquier punto de la curva. |
| [Type](../../aspose.threed.entities/nurbsdirection/type) { get; set; } | Obtiene o establece el tipo de la dirección actual. |

### Ver también

* espacio de nombres [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
