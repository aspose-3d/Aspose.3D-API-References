---
title: Quaternion
second_title: Aspose.3D för .NET API-referens
description: Quaternion används vanligtvis för att utföra rotation i datorgrafik.
type: docs
weight: 2590
url: /sv/net/aspose.threed.utilities/quaternion/
---
## Quaternion structure

Quaternion används vanligtvis för att utföra rotation i datorgrafik.

```csharp
public struct Quaternion
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Quaternion](quaternion)(double, double, double, double) | Initierar en ny instans av[`Quaternion`](../quaternion) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Length](../../aspose.threed.utilities/quaternion/length) { get; } | Får längden på quaternion |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromAngleAxis](../../aspose.threed.utilities/quaternion/fromangleaxis)(double, Vector3) | Skapar en kvaternion runt en given axel och roterar medurs |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle#fromeulerangle)(Vector3) | Skapar quaternion från given Euler-vinkel |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle#fromeulerangle_1)(double, double, double) | Skapar quaternion från given Euler-vinkel |
| static [FromRotation](../../aspose.threed.utilities/quaternion/fromrotation)(Vector3, Vector3) | Skapar en quaternion som roterar från original till destinationsriktning |
| static [Interpolate](../../aspose.threed.utilities/quaternion/interpolate)(float, Quaternion, Quaternion) | Fyller detta kvartjon med det interpolerade värdet mellan de givna kvartjonsargumenten för vid mellan från och till. |
| [Concat](../../aspose.threed.utilities/quaternion/concat)(Quaternion) | Sammanfoga två quaternions |
| [Conjugate](../../aspose.threed.utilities/quaternion/conjugate)() | Returnerar en konjugerad quaternion av nuvarande quaternion |
| [Dot](../../aspose.threed.utilities/quaternion/dot)(Quaternion) | Punkter produkt |
| override [Equals](../../aspose.threed.utilities/quaternion/equals)(object) | Kontrollera om två kvaternioner är lika med |
| [EulerAngles](../../aspose.threed.utilities/quaternion/eulerangles)() | Konverterar quaternion till rotation representerad av Euler angles Alla komponenter är i radian |
| override [GetHashCode](../../aspose.threed.utilities/quaternion/gethashcode)() | Hämtar hashkoden för Quaternion |
| [Inverse](../../aspose.threed.utilities/quaternion/inverse)() | Returnerar en invers quaternion av nuvarande quaternion |
| [Normalize](../../aspose.threed.utilities/quaternion/normalize)() | Normalisera quaternion |
| [ToAngleAxis](../../aspose.threed.utilities/quaternion/toangleaxis)(out double, out Vector3) |  |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix)() | Konvertera rotationen som presenteras av quaternion för att transformera matris. |
| override [ToString](../../aspose.threed.utilities/quaternion/tostring)() | Får representationen av quaternion i string |
| [operator +](../../aspose.threed.utilities/quaternion/op_addition) | Operatör överbelastning för + |
| [operator /](../../aspose.threed.utilities/quaternion/op_division) | Operatörsöverbelastning för / |
| [operator ==](../../aspose.threed.utilities/quaternion/op_equality) | Lika operator för quaternion |
| [operator !=](../../aspose.threed.utilities/quaternion/op_inequality) | Olik operator för quaternion |
| [operator *](../../aspose.threed.utilities/quaternion/op_multiply#op_multiply_1) | Operatör överbelastning för * (5 operators) |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Identity](../../aspose.threed.utilities/quaternion/identity) | Identity quaternion. |
| [w](../../aspose.threed.utilities/quaternion/w) | W-komponenten. |
| [x](../../aspose.threed.utilities/quaternion/x) | x-komponenten. |
| [y](../../aspose.threed.utilities/quaternion/y) | Y-komponenten. |
| [z](../../aspose.threed.utilities/quaternion/z) | Z-komponenten. |

### Se även

* namnutrymme [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
