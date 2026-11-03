---
title: "Structure Matrix4"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Structure Aspose.ThreeD.Utilities.Matrix4. Implémentation d'une matrice 4x4"
type: docs
weight: 2790
url: /fr/net/aspose.threed.utilities/matrix4/
---
## Matrix4 structure

Implémentation d'une matrice 4x4.

```csharp
public struct Matrix4
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Matrix4](matrix4/#constructor_3)(double[]) | Initialise une nouvelle instance de la structure `Matrix4`. |
| [Matrix4](matrix4/#constructor)(FMatrix4) | Construit `Matrix4` à partir d'une instance [`FMatrix4`](../fmatrix4/) |
| [Matrix4](matrix4/#constructor_1)(Vector4, Vector4, Vector4, Vector4) | Construit une matrice à partir de 4 lignes. |
| [Matrix4](matrix4/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | Initialise une nouvelle instance de la structure `Matrix4`. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Identity](../../aspose.threed.utilities/matrix4/identity/) { get; } | Obtient la matrice identité. |
| [Determinant](../../aspose.threed.utilities/matrix4/determinant/) { get; } | Obtient le déterminant de la matrice. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate)(Quaternion) | Crée une matrice de rotation à partir d'un quaternion |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate_1)(double, Vector3) | Crée une matrice de rotation à partir d'un angle de rotation et d'un axe |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler)(Vector3) | Crée une matrice de rotation à partir d'un angle d'Euler |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler_1)(double, double, double) | Crée une matrice de rotation à partir d'un angle d'Euler |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_1)(double) | Crée une matrice qui met à l'échelle le long des axes x, y et z. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale)(Vector3) | Crée une matrice qui met à l'échelle le long des axes x, y et z. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_2)(double, double, double) | Crée une matrice qui met à l'échelle le long des axes x, y et z. |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate)(Vector3) | Crée une matrice qui traduit le long des axes x, y et z |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate_1)(double, double, double) | Crée une matrice qui traduit le long des axes x, y et z |
| [Concatenate](../../aspose.threed.utilities/matrix4/concatenate/)(Matrix4) | Concatène les deux matrices |
| [Decompose](../../aspose.threed.utilities/matrix4/decompose/)(out Vector3, out Vector3, out Quaternion) |  |
| [Inverse](../../aspose.threed.utilities/matrix4/inverse/)() | Inverse cette instance. |
| [Normalize](../../aspose.threed.utilities/matrix4/normalize/)() | Normalise cette instance. |
| [SetTRS](../../aspose.threed.utilities/matrix4/settrs/)(Vector3, Vector3, Vector3) | Initialise la matrice avec translation/rotation/échelle |
| [ToArray](../../aspose.threed.utilities/matrix4/toarray/)() | Convertit la matrice en tableau. |
| override [ToString](../../aspose.threed.utilities/matrix4/tostring/)() | Renvoie une chaîne qui représente le `Matrix4` actuel. |
| [Transpose](../../aspose.threed.utilities/matrix4/transpose/)() | Transpose cette instance. |
| [operator *](../../aspose.threed.utilities/matrix4/op_multiply/#op_multiply) | Multiplie les deux matrices (4 opérateurs) |

## Champs

| Nom | Description |
| --- | --- |
| [m00](../../aspose.threed.utilities/matrix4/m00/) | Le m00. |
| [m01](../../aspose.threed.utilities/matrix4/m01/) | Le m01. |
| [m02](../../aspose.threed.utilities/matrix4/m02/) | Le m02. |
| [m03](../../aspose.threed.utilities/matrix4/m03/) | Le m03. |
| [m10](../../aspose.threed.utilities/matrix4/m10/) | Le m10. |
| [m11](../../aspose.threed.utilities/matrix4/m11/) | Le m11. |
| [m12](../../aspose.threed.utilities/matrix4/m12/) | Le m12. |
| [m13](../../aspose.threed.utilities/matrix4/m13/) | Le m13. |
| [m20](../../aspose.threed.utilities/matrix4/m20/) | Le m20. |
| [m21](../../aspose.threed.utilities/matrix4/m21/) | Le m21. |
| [m22](../../aspose.threed.utilities/matrix4/m22/) | Le m22. |
| [m23](../../aspose.threed.utilities/matrix4/m23/) | Le m23. |
| [m30](../../aspose.threed.utilities/matrix4/m30/) | Le m30. |
| [m31](../../aspose.threed.utilities/matrix4/m31/) | Le m31. |
| [m32](../../aspose.threed.utilities/matrix4/m32/) | Le m32. |
| [m33](../../aspose.threed.utilities/matrix4/m33/) | Le m33. |

## Exemples

```csharp
Matrix4 mat = Matrix4.RotateFromEuler(90, 0, 0);
Matrix4 mat2 = Matrix4.Translate(0, 10, -50);
Matrix4 transform = mat2 * mat;
Vector4 pos = new Vector4(10, 9, 0, 1);
Vector4 transformed = transform * pos;

```

### Voir aussi

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


