---
title: "Matrix4.Matrix4"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Matrix4 κατασκευαστής. Δημιουργεί πίνακα από 4 σειρές"
type: docs
weight: 10
url: /el/net/aspose.threed.utilities/matrix4/matrix4/
---
## Matrix4(Vector4, Vector4, Vector4, Vector4) {#constructor_1}

Δημιουργεί πίνακα από 4 σειρές.

```csharp
public Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

### Δείτε επίσης

* struct [Vector4](../../vector4/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία του [`Matrix4`](../) struct.

```csharp
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, 
    double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, 
    double m33)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| m00 | Διπλό | M00. |
| m01 | Διπλό | M01. |
| m02 | Διπλό | M02. |
| m03 | Διπλό | M03. |
| m10 | Διπλό | M10. |
| m11 | Διπλό | M11. |
| m12 | Διπλό | M12. |
| m13 | Διπλό | M13. |
| m20 | Διπλό | M20. |
| m21 | Διπλό | M21. |
| m22 | Διπλό | M22. |
| m23 | Διπλό | M23. |
| m30 | Διπλό | M30. |
| m31 | Διπλό | M31. |
| m32 | Διπλό | M32. |
| m33 | Διπλό | M33. |

## Παραδείγματα

```csharp
var mat = new Matrix4(
    1, 0, 0, 0,
    0, 1, 0, 0,
    0, 0, 1, 0,
    10, 20, 0, 1);
var pos = new Vector3(10, 0, -1);
var transformed = mat * pos;
```

### Δείτε επίσης

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(FMatrix4) {#constructor}

Δημιουργήστε το [`Matrix4`](../) από ένα αντικείμενο [`FMatrix4`](../../fmatrix4/)

```csharp
public Matrix4(FMatrix4 m)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| m | FMatrix4 |  |

### Δείτε επίσης

* struct [FMatrix4](../../fmatrix4/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(double[]) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία του [`Matrix4`](../) struct.

```csharp
public Matrix4(double[] m)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| m | Double[] | M. |

### Δείτε επίσης

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


