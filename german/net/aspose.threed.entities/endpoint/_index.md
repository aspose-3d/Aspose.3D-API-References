---
title: "Struktur EndPoint"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.EndPoint Struktur. Der Endpunkt zum Trimmen der Kurve kann ein Parameterwert oder ein kartesischer Punkt sein"
type: docs
weight: 390
url: /de/net/aspose.threed.entities/endpoint/
---
## EndPoint structure

Der Endpunkt zum Beschneiden der Kurve, kann ein Parameterwert oder ein kartesischer Punkt sein.

```csharp
public struct EndPoint
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [EndPoint](endpoint/#constructor_1)(double) | Erstelle ein `EndPoint` aus einem reellen Parameter. |
| [EndPoint](endpoint/#constructor)(Vector3) | Erstelle ein `EndPoint` aus einem kartesischen Punkt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsPoint](../../aspose.threed.entities/endpoint/aspoint/) { get; } | Gibt den Endpunkt als kartesischen Punkt zurück, oder wirft eine Ausnahme. |
| [AsValue](../../aspose.threed.entities/endpoint/asvalue/) { get; } | Gibt den Endpunkt als reellen Parameter zurück, oder wirft eine Ausnahme. |
| [IsCartesianPoint](../../aspose.threed.entities/endpoint/iscartesianpoint/) { get; } | Ist der Endpunkt ein kartesischer Punkt? |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromDegree](../../aspose.threed.entities/endpoint/fromdegree/)(double) | Erstelle einen Endpunkt gemessen in Grad. |
| static [FromRadian](../../aspose.threed.entities/endpoint/fromradian/)(double) | Erstelle einen Endpunkt gemessen in Radiant. |
| override [ToString](../../aspose.threed.entities/endpoint/tostring/)() | Gibt eine Zeichenkettenrepräsentation des aktuellen Endpunkts zurück. |

### Siehe auch

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


