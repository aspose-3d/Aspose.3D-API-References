---
title: "Matrix4.Matrix4"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Matrix4 कंस्ट्रक्टर। 4 पंक्तियों से मैट्रिक्स बनाता है"
type: docs
weight: 10
url: /hi/net/aspose.threed.utilities/matrix4/matrix4/
---
## Matrix4(Vector4, Vector4, Vector4, Vector4) {#constructor_1}

4 पंक्तियों से मैट्रिक्स बनाता है।

```csharp
public Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

### देखें भी

* struct [Vector4](../../vector4/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

एक नया इंस्टेंस प्रारंभ करता है [`Matrix4`](../) स्ट्रक्ट का।

```csharp
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, 
    double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, 
    double m33)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| m00 | डबल | M00. |
| m01 | डबल | M01. |
| m02 | डबल | M02. |
| m03 | डबल | M03. |
| m10 | डबल | M10. |
| m11 | डबल | M11. |
| m12 | डबल | M12. |
| m13 | डबल | M13. |
| m20 | डबल | M20. |
| m21 | डबल | M21. |
| m22 | डबल | M22. |
| m23 | डबल | M23. |
| m30 | डबल | M30. |
| m31 | डबल | M31. |
| m32 | डबल | M32. |
| m33 | डबल | M33. |

## उदाहरण

```csharp
var mat = new Matrix4(
    1, 0, 0, 0,
    0, 1, 0, 0,
    0, 0, 1, 0,
    10, 20, 0, 1);
var pos = new Vector3(10, 0, -1);
var transformed = mat * pos;
```

### देखें भी

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(FMatrix4) {#constructor}

एक [`FMatrix4`](../../fmatrix4/) इंस्टेंस से [`Matrix4`](../) बनाएं

```csharp
public Matrix4(FMatrix4 m)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| m | FMatrix4 |  |

### देखें भी

* struct [FMatrix4](../../fmatrix4/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(double[]) {#constructor_3}

एक नया इंस्टेंस प्रारंभ करता है [`Matrix4`](../) स्ट्रक्ट का।

```csharp
public Matrix4(double[] m)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| m | Double[] | M. |

### देखें भी

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


