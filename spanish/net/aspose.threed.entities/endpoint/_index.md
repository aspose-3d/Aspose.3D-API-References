---
title: EndPoint
second_title: Referencia de API de Aspose.3D para .NET
description: El punto final para recortar la curva puede ser un valor de parámetro o un punto cartesiano.
type: docs
weight: 340
url: /es/net/aspose.threed.entities/endpoint/
---
## EndPoint structure

El punto final para recortar la curva, puede ser un valor de parámetro o un punto cartesiano.

```csharp
public struct EndPoint
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EndPoint](endpoint#constructor_1)(double) | Construye un[`EndPoint`](../endpoint) de un parámetro real. |
| [EndPoint](endpoint#constructor)(Vector3) | Construye un[`EndPoint`](../endpoint) desde un punto cartesiano. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsPoint](../../aspose.threed.entities/endpoint/aspoint) { get; } | Obtiene el punto final como punto cartesiano, o lanza una excepción. |
| [AsValue](../../aspose.threed.entities/endpoint/asvalue) { get; } | Obtiene el punto final como un parámetro real, o lanza una excepción. |
| [IsCartesianPoint](../../aspose.threed.entities/endpoint/iscartesianpoint) { get; } | ¿El punto final es un punto cartesiano? |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromDegree](../../aspose.threed.entities/endpoint/fromdegree)(double) | Crea un punto final medido en grados. |
| static [FromRadian](../../aspose.threed.entities/endpoint/fromradian)(double) | Crea un punto final medido en radianes. |
| override [ToString](../../aspose.threed.entities/endpoint/tostring)() | Devuelve una representación de cadena del punto final actual. |

### Ver también

* espacio de nombres [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
