---
title: "Matrix4.RotateFromEuler"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Matrix4. Crea una matriz de rotación a partir del ángulo de Euler"
type: docs
weight: 40
url: /es/net/aspose.threed.utilities/matrix4/rotatefromeuler/
---
## RotateFromEuler(Vector3) {#rotatefromeuler}

Crea una matriz de rotación a partir de ángulos de Euler

```csharp
public static Matrix4 RotateFromEuler(Vector3 eul)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| eul | Vector3 | Rotación en radianes |

## Ejemplos

El siguiente código muestra cómo crear una matriz para la operación de rotación.

```csharp
var t = Matrix4.RotateFromEuler(new Vector3(0, Math.PI, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Ver también

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## RotateFromEuler(double, double, double) {#rotatefromeuler_1}

Crea una matriz de rotación a partir de ángulos de Euler

```csharp
public static Matrix4 RotateFromEuler(double rx, double ry, double rz)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rx | Doble | Rotación en el eje x en radianes |
| ry | Doble | Rotación en el eje y en radianes |
| rz | Doble | Rotación en el eje z en radianes |

## Ejemplos

El siguiente código muestra cómo crear una matriz para la operación de rotación.

```csharp
var t = Matrix4.RotateFromEuler(0, Math.PI, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Ver también

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


