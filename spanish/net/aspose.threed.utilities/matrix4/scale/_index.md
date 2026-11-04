---
title: "Matrix4.Scale"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Matrix4. Crea una matriz que escala a lo largo del eje x, el eje y y el eje z"
type: docs
weight: 50
url: /es/net/aspose.threed.utilities/matrix4/scale/
---
## Scale(Vector3) {#scale}

Crea una matriz que escala a lo largo del eje x, el eje y y el eje z.

```csharp
public static Matrix4 Scale(Vector3 s)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | Vector3 | Las fábricas de escalado se aplican al eje x, al eje y y al eje z |

## Ejemplos

El siguiente código muestra cómo crear una matriz para la operación de escala.

```csharp
var t = Matrix4.Scale(new Vector3(10, 10, 10));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Ver también

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double) {#scale_1}

Crea una matriz que escala a lo largo del eje x, el eje y y el eje z.

```csharp
public static Matrix4 Scale(double s)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | Doble | Las fábricas de escalado se aplican a todos los ejes |

## Ejemplos

El siguiente código muestra cómo crear una matriz para la operación de escala.

```csharp
var t = Matrix4.Scale(10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Ver también

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

Crea una matriz que escala a lo largo del eje x, el eje y y el eje z.

```csharp
public static Matrix4 Scale(double sx, double sy, double sz)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | Doble | Los factores de escala se aplican al eje x |
| sy | Doble | Los factores de escala se aplican al eje y |
| sz | Doble | Los factores de escala se aplican al eje z |

## Ejemplos

El siguiente código muestra cómo crear una matriz para la operación de escala.

```csharp
var t = Matrix4.Scale(10, 20, 10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Ver también

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


