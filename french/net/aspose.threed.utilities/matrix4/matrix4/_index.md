---
title: "Matrix4.Matrix4"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Matrix4 constructeur. Construit la matrice à partir de 4 lignes"
type: docs
weight: 10
url: /fr/net/aspose.threed.utilities/matrix4/matrix4/
---
## Matrix4(Vector4, Vector4, Vector4, Vector4) {#constructor_1}

Construit une matrice à partir de 4 lignes.

```csharp
public Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

### Voir aussi

* struct [Vector4](../../vector4/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Initialise une nouvelle instance de la structure [`Matrix4`](../).

```csharp
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, 
    double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, 
    double m33)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| m00 | Double | M00. |
| m01 | Double | M01. |
| m02 | Double | M02. |
| m03 | Double | M03. |
| m10 | Double | M10. |
| m11 | Double | M11. |
| m12 | Double | M12. |
| m13 | Double | M13. |
| m20 | Double | M20. |
| m21 | Double | M21. |
| m22 | Double | M22. |
| m23 | Double | M23. |
| m30 | Double | M30. |
| m31 | Double | M31. |
| m32 | Double | M32. |
| m33 | Double | M33. |

## Exemples

```csharp
var mat = new Matrix4(
    1, 0, 0, 0,
    0, 1, 0, 0,
    0, 0, 1, 0,
    10, 20, 0, 1);
var pos = new Vector3(10, 0, -1);
var transformed = mat * pos;
```

### Voir aussi

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(FMatrix4) {#constructor}

Construire [`Matrix4`](../) à partir d'une instance de [`FMatrix4`](../../fmatrix4/)

```csharp
public Matrix4(FMatrix4 m)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| m | FMatrix4 |  |

### Voir aussi

* struct [FMatrix4](../../fmatrix4/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(double[]) {#constructor_3}

Initialise une nouvelle instance de la structure [`Matrix4`](../).

```csharp
public Matrix4(double[] m)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| m | Double[] | M. |

### Voir aussi

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


