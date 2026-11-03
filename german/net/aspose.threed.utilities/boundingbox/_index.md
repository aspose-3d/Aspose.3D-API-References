---
title: "Struktur BoundingBox"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Utilities.BoundingBox Struktur. Die achsenorientierte Begrenzungsbox"
type: docs
weight: 2670
url: /de/net/aspose.threed.utilities/boundingbox/
---
## BoundingBox structure

Die achsenparallel ausgerichtete Begrenzungsbox

```csharp
public struct BoundingBox
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BoundingBox](boundingbox/#constructor)(Vector3, Vector3) | Initialisiert eine endliche Begrenzungsbox mit angegebenen minimalen und maximalen Eckpunkten. |
| [BoundingBox](boundingbox/#constructor_1)(double, double, double, double, double, double) | Initialisiert eine endliche Begrenzungsbox mit angegebenen minimalen und maximalen Eckpunkten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Infinite](../../aspose.threed.utilities/boundingbox/infinite/) { get; } | Die unendliche Begrenzungsbox |
| static [Null](../../aspose.threed.utilities/boundingbox/null/) { get; } | Die Null‑Begrenzungsbox |
| [Center](../../aspose.threed.utilities/boundingbox/center/) { get; } | Der Mittelpunkt der Begrenzungsbox. |
| [Extent](../../aspose.threed.utilities/boundingbox/extent/) { get; } | Gibt die Ausdehnung der Begrenzungsbox zurück. |
| [Maximum](../../aspose.threed.utilities/boundingbox/maximum/) { get; } | Der maximale Eckpunkt der Begrenzungsbox |
| [Minimum](../../aspose.threed.utilities/boundingbox/minimum/) { get; } | Der minimale Eckpunkt der Begrenzungsbox |
| [Size](../../aspose.threed.utilities/boundingbox/size/) { get; } | Die Größe der Begrenzungsbox |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/boundingbox/fromgeometry/)(Geometry) | Erstelle eine Begrenzungsbox aus gegebener Geometrie |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains)(BoundingBox) | Die Begrenzungsbox, um zu prüfen, ob sie innerhalb der aktuellen Begrenzungsbox liegt. |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains_1)(Vector3) | Prüfen, ob der Punkt p innerhalb der Begrenzungsbox liegt |
| override [Equals](../../aspose.threed.utilities/boundingbox/equals/)(object) | Bestimmt, ob zwei Objekte gleich sind |
| override [GetHashCode](../../aspose.threed.utilities/boundingbox/gethashcode/)() | Gibt den Hashcode für diese Instanz zurück |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge)(BoundingBox) | Fügt die neue Box in die aktuelle Begrenzungsbox ein. |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_1)(Vector3) | Füge die aktuelle Begrenzungsbox mit dem angegebenen Punkt zusammen |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_2)(Vector4) | Füge die aktuelle Begrenzungsbox mit dem angegebenen Punkt zusammen |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_3)(double, double, double) | Füge die aktuelle Begrenzungsbox mit dem angegebenen Punkt zusammen |
| [OverlapsWith](../../aspose.threed.utilities/boundingbox/overlapswith/)(BoundingBox) | Prüfen, ob die aktuelle Begrenzungsbox mit der angegebenen Begrenzungsbox überlappt. |
| [Scale](../../aspose.threed.utilities/boundingbox/scale/)() | Berechnet den absoluten größten Koordinatenwert eines beliebigen enthaltenen Punktes. |
| override [ToString](../../aspose.threed.utilities/boundingbox/tostring/)() | Gibt die String‑Repräsentation der Begrenzungsbox zurück. |
| [operator *](../../aspose.threed.utilities/boundingbox/op_multiply/) | Operatorüberladung für Multiplikation, die minimale und maximale Ecke der neuen Begrenzungsbox werden durch die Matrix transformiert. |

## Beispiele

Der folgende Code zeigt, wie man eine Begrenzungsbox aus einer Entity-Instanz erhält.

```csharp
var sphere = new Sphere();
var boundingBox = sphere.GetBoundingBox();
Console.WriteLine("Bounding box = " + boundingBox);
```

### Siehe auch

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


