---
title: "Matrix4.Rotate"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Matrix4 método. Crea una matriz de rotación mediante ángulo de rotación y eje"
type: docs
weight: 30
url: /es/net/aspose.threed.utilities/matrix4/rotate/
---
## Rotate(double, Vector3) {#rotate_1}

Crea una matriz de rotación mediante ángulo de rotación y eje

```csharp
public static Matrix4 Rotate(double angle, Vector3 axis)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | Doble | Ángulo de rotación en radianes |
| eje | Vector3 | Eje de rotación |

## Ejemplos

El siguiente código muestra cómo crear una matriz para la operación de rotación.

```csharp
var t = Matrix4.Rotate(Math.PI, new Vector3(0, 1, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Ver también

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Rotate(Quaternion) {#rotate}

Crea una matriz de rotación a partir de un cuaternión

```csharp
public static Matrix4 Rotate(Quaternion q)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| q | Cuaternión | Cuaternión de rotación |

## Ejemplos

El siguiente código muestra cómo crear una matriz para la operación de rotación.

```csharp
var t = Matrix4.Rotate(Quaternion.FromAngleAxis(Math.PI, Vector3.YAxis));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Ver también

* struct [Quaternion](../../quaternion/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


