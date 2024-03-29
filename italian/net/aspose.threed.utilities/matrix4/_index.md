---
title: Matrix4
second_title: Riferimento API Aspose.3D per .NET
description: Implementazione matrice 4x4.
type: docs
weight: 2560
url: /it/net/aspose.threed.utilities/matrix4/
---
## Matrix4 structure

Implementazione matrice 4x4.

```csharp
public struct Matrix4
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Matrix4](matrix4#constructor_3)(double[]) | Inizializza una nuova istanza di[`Matrix4`](../matrix4) struttura |
| [Matrix4](matrix4#constructor)(FMatrix4) | Costruire[`Matrix4`](../matrix4) da un[`FMatrix4`](../fmatrix4) istanza |
| [Matrix4](matrix4#constructor_1)(Vector4, Vector4, Vector4, Vector4) | Costruisce la matrice da 4 righe. |
| [Matrix4](matrix4#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | Inizializza una nuova istanza di[`Matrix4`](../matrix4) struttura |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Identity](../../aspose.threed.utilities/matrix4/identity) { get; } | Ottiene la matrice dell'identità. |
| [Determinant](../../aspose.threed.utilities/matrix4/determinant) { get; } | Ottiene il determinante della matrice. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate#rotate)(Quaternion) | Crea una matrice di rotazione da un quaternione |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate#rotate_1)(double, Vector3) | Crea una matrice di rotazione in base all'angolo di rotazione e all'asse |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler#rotatefromeuler)(Vector3) | Crea una matrice di rotazione dall'angolo di Eulero |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler#rotatefromeuler_1)(double, double, double) | Crea una matrice di rotazione dall'angolo di Eulero |
| static [Scale](../../aspose.threed.utilities/matrix4/scale#scale_1)(double) | Crea una matrice che scala lungo l'asse x, l'asse y e l'asse z. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale#scale)(Vector3) | Crea una matrice che scala lungo l'asse x, l'asse y e l'asse z. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale#scale_2)(double, double, double) | Crea una matrice che scala lungo l'asse x, l'asse y e l'asse z. |
| static [Translate](../../aspose.threed.utilities/matrix4/translate#translate)(Vector3) | Crea una matrice che trasla lungo l'asse x, l'asse y e l'asse z |
| static [Translate](../../aspose.threed.utilities/matrix4/translate#translate_1)(double, double, double) | Crea una matrice che trasla lungo l'asse x, l'asse y e l'asse z |
| [Concatenate](../../aspose.threed.utilities/matrix4/concatenate)(Matrix4) | Concatena le due matrici |
| [Decompose](../../aspose.threed.utilities/matrix4/decompose)(out Vector3, out Vector3, out Quaternion) |  |
| [Inverse](../../aspose.threed.utilities/matrix4/inverse)() | Inverte questa istanza. |
| [Normalize](../../aspose.threed.utilities/matrix4/normalize)() | Normalizza questa istanza. |
| [SetTRS](../../aspose.threed.utilities/matrix4/settrs)(Vector3, Vector3, Vector3) | Inizializza la matrice con traslazione/rotazione/scala |
| [ToArray](../../aspose.threed.utilities/matrix4/toarray)() | Converte la matrice in array. |
| override [ToString](../../aspose.threed.utilities/matrix4/tostring)() | Restituisce aStringche rappresenta la corrente[`Matrix4`](../matrix4) . |
| [Transpose](../../aspose.threed.utilities/matrix4/transpose)() | Traspone questa istanza. |
| [operator *](../../aspose.threed.utilities/matrix4/op_multiply#op_multiply) | Moltiplica le due matrici (4 operators) |

## Campi

| Nome | Descrizione |
| --- | --- |
| [m00](../../aspose.threed.utilities/matrix4/m00) | Il m00. |
| [m01](../../aspose.threed.utilities/matrix4/m01) | Il m01. |
| [m02](../../aspose.threed.utilities/matrix4/m02) | Il m02. |
| [m03](../../aspose.threed.utilities/matrix4/m03) | Il m03. |
| [m10](../../aspose.threed.utilities/matrix4/m10) | Il m10. |
| [m11](../../aspose.threed.utilities/matrix4/m11) | Il m11. |
| [m12](../../aspose.threed.utilities/matrix4/m12) | Il m12. |
| [m13](../../aspose.threed.utilities/matrix4/m13) | Il m13. |
| [m20](../../aspose.threed.utilities/matrix4/m20) | Il m20. |
| [m21](../../aspose.threed.utilities/matrix4/m21) | Il m21. |
| [m22](../../aspose.threed.utilities/matrix4/m22) | Il m22. |
| [m23](../../aspose.threed.utilities/matrix4/m23) | Il m23. |
| [m30](../../aspose.threed.utilities/matrix4/m30) | Il m30. |
| [m31](../../aspose.threed.utilities/matrix4/m31) | Il m31. |
| [m32](../../aspose.threed.utilities/matrix4/m32) | Il m32. |
| [m33](../../aspose.threed.utilities/matrix4/m33) | Il m33. |

### Guarda anche

* spazio dei nomi [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assemblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
