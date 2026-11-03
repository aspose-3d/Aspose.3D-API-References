---
title: "Struktur Matrix4"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Utilities.Matrix4 Struktur. 4x4-Matrix-Implementierung"
type: docs
weight: 2790
url: /de/net/aspose.threed.utilities/matrix4/
---
## Matrix4 structure

4x4-Matrix-Implementierung.

```csharp
public struct Matrix4
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Matrix4](matrix4/#constructor_3)(double[]) | Initialisiert eine neue Instanz der `Matrix4`-Struktur. |
| [Matrix4](matrix4/#constructor)(FMatrix4) | Konstruiere `Matrix4` aus einer [`FMatrix4`](../fmatrix4/)-Instanz |
| [Matrix4](matrix4/#constructor_1)(Vector4, Vector4, Vector4, Vector4) | Konstruiert die Matrix aus 4 Zeilen. |
| [Matrix4](matrix4/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | Initialisiert eine neue Instanz der `Matrix4`-Struktur. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Identity](../../aspose.threed.utilities/matrix4/identity/) { get; } | Gibt die Einheitsmatrix zurück. |
| [Determinant](../../aspose.threed.utilities/matrix4/determinant/) { get; } | Gibt die Determinante der Matrix zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate)(Quaternion) | Erstelle eine Rotationsmatrix aus einem Quaternion |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate_1)(double, Vector3) | Erstelle eine Rotationsmatrix anhand des Rotationswinkels und der Achse |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler)(Vector3) | Erstelle eine Rotationsmatrix aus einem Euler-Winkel |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler_1)(double, double, double) | Erstelle eine Rotationsmatrix aus einem Euler-Winkel |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_1)(double) | Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse skaliert. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale)(Vector3) | Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse skaliert. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_2)(double, double, double) | Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse skaliert. |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate)(Vector3) | Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse verschiebt |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate_1)(double, double, double) | Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse verschiebt |
| [Concatenate](../../aspose.threed.utilities/matrix4/concatenate/)(Matrix4) | Verkettet die beiden Matrizen |
| [Decompose](../../aspose.threed.utilities/matrix4/decompose/)(out Vector3, out Vector3, out Quaternion) |  |
| [Inverse](../../aspose.threed.utilities/matrix4/inverse/)() | Invertiert diese Instanz. |
| [Normalize](../../aspose.threed.utilities/matrix4/normalize/)() | Normalisiert diese Instanz. |
| [SetTRS](../../aspose.threed.utilities/matrix4/settrs/)(Vector3, Vector3, Vector3) | Initialisiert die Matrix mit Translation/Rotation/Skalierung |
| [ToArray](../../aspose.threed.utilities/matrix4/toarray/)() | Konvertiert die Matrix in ein Array. |
| override [ToString](../../aspose.threed.utilities/matrix4/tostring/)() | Gibt einen String zurück, der das aktuelle `Matrix4` darstellt. |
| [Transpose](../../aspose.threed.utilities/matrix4/transpose/)() | Transponiert diese Instanz. |
| [operator *](../../aspose.threed.utilities/matrix4/op_multiply/#op_multiply) | Multipliziert die beiden Matrizen (4 Operatoren) |

## Felder

| Name | Beschreibung |
| --- | --- |
| [m00](../../aspose.threed.utilities/matrix4/m00/) | Der m00. |
| [m01](../../aspose.threed.utilities/matrix4/m01/) | Der m01. |
| [m02](../../aspose.threed.utilities/matrix4/m02/) | Der m02. |
| [m03](../../aspose.threed.utilities/matrix4/m03/) | Der m03. |
| [m10](../../aspose.threed.utilities/matrix4/m10/) | Der m10. |
| [m11](../../aspose.threed.utilities/matrix4/m11/) | Der m11. |
| [m12](../../aspose.threed.utilities/matrix4/m12/) | Der m12. |
| [m13](../../aspose.threed.utilities/matrix4/m13/) | Der m13. |
| [m20](../../aspose.threed.utilities/matrix4/m20/) | Der m20. |
| [m21](../../aspose.threed.utilities/matrix4/m21/) | Der m21. |
| [m22](../../aspose.threed.utilities/matrix4/m22/) | Der m22. |
| [m23](../../aspose.threed.utilities/matrix4/m23/) | Der m23. |
| [m30](../../aspose.threed.utilities/matrix4/m30/) | Der m30. |
| [m31](../../aspose.threed.utilities/matrix4/m31/) | Der m31. |
| [m32](../../aspose.threed.utilities/matrix4/m32/) | Der m32. |
| [m33](../../aspose.threed.utilities/matrix4/m33/) | Der m33. |

## Beispiele

```csharp
Matrix4 mat = Matrix4.RotateFromEuler(90, 0, 0);
Matrix4 mat2 = Matrix4.Translate(0, 10, -50);
Matrix4 transform = mat2 * mat;
Vector4 pos = new Vector4(10, 9, 0, 1);
Vector4 transformed = transform * pos;

```

### Siehe auch

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


