---
title: "Matrix4.Matrix4"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "منشئ Matrix4. يبني مصفوفة من 4 صفوف"
type: docs
weight: 10
url: /ar/net/aspose.threed.utilities/matrix4/matrix4/
---
## Matrix4(Vector4, Vector4, Vector4, Vector4) {#constructor_1}

يبني مصفوفة من 4 صفوف.

```csharp
public Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

### انظر أيضًا

* struct [Vector4](../../vector4/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

يُنشئ نسخة جديدة من البنية [`Matrix4`](../).

```csharp
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, 
    double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, 
    double m33)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| m00 | مضاعف | M00. |
| m01 | مضاعف | M01. |
| m02 | مضاعف | M02. |
| m03 | مضاعف | M03. |
| m10 | مضاعف | M10. |
| m11 | مضاعف | M11. |
| m12 | مضاعف | M12. |
| m13 | مضاعف | M13. |
| m20 | مضاعف | M20. |
| m21 | مضاعف | M21. |
| m22 | مضاعف | M22. |
| m23 | مضاعف | M23. |
| m30 | مضاعف | M30. |
| m31 | مضاعف | M31. |
| m32 | مضاعف | M32. |
| m33 | مضاعف | M33. |

## أمثلة

```csharp
var mat = new Matrix4(
    1, 0, 0, 0,
    0, 1, 0, 0,
    0, 0, 1, 0,
    10, 20, 0, 1);
var pos = new Vector3(10, 0, -1);
var transformed = mat * pos;
```

### انظر أيضًا

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(FMatrix4) {#constructor}

إنشاء [`Matrix4`](../) من كائن [`FMatrix4`](../../fmatrix4/)

```csharp
public Matrix4(FMatrix4 m)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| m | FMatrix4 |  |

### انظر أيضًا

* struct [FMatrix4](../../fmatrix4/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(double[]) {#constructor_3}

يُنشئ نسخة جديدة من البنية [`Matrix4`](../).

```csharp
public Matrix4(double[] m)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| m | Double[] | M. |

### انظر أيضًا

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


