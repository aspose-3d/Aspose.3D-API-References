---
title: "Estructura EndPoint"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Estructura Aspose.ThreeD.Entities.EndPoint. El punto final para recortar la curva puede ser un valor de parámetro o un punto cartesiano"
type: docs
weight: 390
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
| [EndPoint](endpoint/#constructor_1)(double) | Construir un `EndPoint` a partir de un parámetro real. |
| [EndPoint](endpoint/#constructor)(Vector3) | Construir un `EndPoint` a partir de un punto cartesiano. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsPoint](../../aspose.threed.entities/endpoint/aspoint/) { get; } | Obtiene el punto final como punto cartesiano, o lanza una excepción. |
| [AsValue](../../aspose.threed.entities/endpoint/asvalue/) { get; } | Obtiene el punto final como un parámetro real, o lanza una excepción. |
| [IsCartesianPoint](../../aspose.threed.entities/endpoint/iscartesianpoint/) { get; } | ¿Es el punto final un punto cartesiano? |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromDegree](../../aspose.threed.entities/endpoint/fromdegree/)(double) | Crear un punto final medido en grados. |
| static [FromRadian](../../aspose.threed.entities/endpoint/fromradian/)(double) | Crear un punto final medido en radianes. |
| override [ToString](../../aspose.threed.entities/endpoint/tostring/)() | Devuelve una representación en cadena del punto final actual. |

### Ver también

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


