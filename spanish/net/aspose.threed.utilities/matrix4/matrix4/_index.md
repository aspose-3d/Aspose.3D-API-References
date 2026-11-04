---
title: "Matrix4.Matrix4"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Matrix4 constructor. Construye la matriz a partir de 4 filas"
type: docs
weight: 10
url: /es/net/aspose.threed.utilities/matrix4/matrix4/
---
## Matrix4(Vector4, Vector4, Vector4, Vector4) {#constructor_1}

Construye la matriz a partir de 4 filas.

```csharp
public Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

### Ver también

* struct [Vector4](../../vector4/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Inicializa una nueva instancia de la estructura [`Matrix4`](../).

```csharp
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, 
    double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, 
    double m33)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| m00 | Doble | M00. |
| m01 | Doble | M01. |
| m02 | Doble | M02. |
| m03 | Doble | M03. |
| m10 | Doble | M10. |
| m11 | Doble | M11. |
| m12 | Doble | M12. |
| m13 | Doble | M13. |
| m20 | Doble | M20. |
| m21 | Doble | M21. |
| m22 | Doble | M22. |
| m23 | Doble | M23. |
| m30 | Doble | M30. |
| m31 | Doble | M31. |
| m32 | Doble | M32. |
| m33 | Doble | M33. |

## Ejemplos

```csharp
var mat = new Matrix4(
    1, 0, 0, 0,
    0, 1, 0, 0,
    0, 0, 1, 0,
    10, 20, 0, 1);
var pos = new Vector3(10, 0, -1);
var transformed = mat * pos;
```

### Ver también

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(FMatrix4) {#constructor}

Construir [`Matrix4`](../) a partir de una instancia de [`FMatrix4`](../../fmatrix4/)

```csharp
public Matrix4(FMatrix4 m)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| m | FMatrix4 |  |

### Ver también

* struct [FMatrix4](../../fmatrix4/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Matrix4(double[]) {#constructor_3}

Inicializa una nueva instancia de la estructura [`Matrix4`](../).

```csharp
public Matrix4(double[] m)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| m | Double[] | M. |

### Ver también

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


