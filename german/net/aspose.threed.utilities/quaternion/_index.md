---
title: "Struktur Quaternion"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Utilities.Quaternion Struktur. Quaternion wird üblicherweise verwendet, um Rotationen in der Computergrafik durchzuführen"
type: docs
weight: 2810
url: /de/net/aspose.threed.utilities/quaternion/
---
## Quaternion structure

Quaternion wird üblicherweise verwendet, um Rotationen in der Computergrafik durchzuführen.

```csharp
public struct Quaternion
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Quaternion](quaternion/)(double, double, double, double) | Initialisiert eine neue Instanz der `Quaternion` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Length](../../aspose.threed.utilities/quaternion/length/) { get; } | Gibt die Länge des Quaternions zurück |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromAngleAxis](../../aspose.threed.utilities/quaternion/fromangleaxis/)(double, Vector3) | Erstellt ein Quaternion um die gegebene Achse und rotiert im Uhrzeigersinn |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle)(Vector3) | Erstellt ein Quaternion aus dem gegebenen Eulerwinkel |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle_1)(double, double, double) | Erstellt ein Quaternion aus dem gegebenen Eulerwinkel |
| static [FromRotation](../../aspose.threed.utilities/quaternion/fromrotation/)(Vector3, Vector3) | Erstellt ein Quaternion, das von der ursprünglichen zur Zielrichtung rotiert |
| static [Interpolate](../../aspose.threed.utilities/quaternion/interpolate/)(float, Quaternion, Quaternion) | Füllt dieses Quaternion mit dem interpolierten Wert zwischen den angegebenen Quaternion-Argumenten für ein t zwischen von und bis. |
| static [Slerp](../../aspose.threed.utilities/quaternion/slerp/)(double, Quaternion, Quaternion) | Führt eine sphärische lineare Interpolation zwischen zwei Werten durch |
| [Concat](../../aspose.threed.utilities/quaternion/concat/)(Quaternion) | Verkettet zwei Quaternionen |
| [Conjugate](../../aspose.threed.utilities/quaternion/conjugate/)() | Gibt ein konjugiertes Quaternion des aktuellen Quaternion zurück |
| [Dot](../../aspose.threed.utilities/quaternion/dot/)(Quaternion) | Skalarprodukt |
| override [Equals](../../aspose.threed.utilities/quaternion/equals/)(object) | Prüft, ob zwei Quaternionen gleich sind |
| [EulerAngles](../../aspose.threed.utilities/quaternion/eulerangles/)() | Konvertiert ein Quaternion in eine Rotation, die durch Eulerwinkel dargestellt wird. Alle Komponenten sind in Radiant. |
| override [GetHashCode](../../aspose.threed.utilities/quaternion/gethashcode/)() | Gibt den Hashcode des Quaternion zurück |
| [Inverse](../../aspose.threed.utilities/quaternion/inverse/)() | Gibt ein inverses Quaternion des aktuellen Quaternion zurück |
| [Normalize](../../aspose.threed.utilities/quaternion/normalize/)() | Normalisiert das Quaternion |
| [ToAngleAxis](../../aspose.threed.utilities/quaternion/toangleaxis/)(out double, out Vector3) |  |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix)() | Konvertiert die von einem Quaternion dargestellte Rotation in eine Transformationsmatrix. |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix_1)(Vector3) | Konvertiert die von einem Quaternion dargestellte Rotation in eine Transformationsmatrix. |
| override [ToString](../../aspose.threed.utilities/quaternion/tostring/)() | Gibt die Darstellung des Quaternion als Zeichenkette zurück |
| [operator +](../../aspose.threed.utilities/quaternion/op_addition/) | Operatorüberladung für + |
| [operator /](../../aspose.threed.utilities/quaternion/op_division/) | Operatorüberladung für / |
| [operator ==](../../aspose.threed.utilities/quaternion/op_equality/) | Gleichheitsoperator für Quaternion |
| [operator !=](../../aspose.threed.utilities/quaternion/op_inequality/) | Ungleichheitsoperator für Quaternion |
| [operator *](../../aspose.threed.utilities/quaternion/op_multiply/#op_multiply_1) | Operatorüberladung für * (5 Operatoren) |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Identity](../../aspose.threed.utilities/quaternion/identity/) | Das Identitäts-Quaternion. |
| [W](../../aspose.threed.utilities/quaternion/w/) | Die w-Komponente. |
| [X](../../aspose.threed.utilities/quaternion/x/) | Die x-Komponente. |
| [Y](../../aspose.threed.utilities/quaternion/y/) | Die y-Komponente. |
| [Z](../../aspose.threed.utilities/quaternion/z/) | Die z-Komponente. |

### Siehe auch

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


