---
title: "Matrix4.Translate"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Matrix4. Crea una matriz que traslada a lo largo del eje x, el eje y y el eje z"
type: docs
weight: 60
url: /es/net/aspose.threed.utilities/matrix4/translate/
---
## Translate(Vector3) {#translate}

Crea una matriz que traslada a lo largo del eje x, el eje y y el eje z

```csharp
public static Matrix4 Translate(Vector3 t)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| t | Vector3 | Desplazamiento de traducción |

## Ejemplos

El siguiente código muestra cómo crear una matriz para la operación de traducción.

```csharp
var t = Matrix4.Translate(new Vector3(10, 0, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Ver también

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Translate(double, double, double) {#translate_1}

Crea una matriz que traslada a lo largo del eje x, el eje y y el eje z

```csharp
public static Matrix4 Translate(double tx, double ty, double tz)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tx | Doble | Desplazamiento de la coordenada X |
| ty | Doble | Desplazamiento de la coordenada Y |
| tz | Doble | Desplazamiento de la coordenada Z |

## Ejemplos

El siguiente código muestra cómo crear una matriz para la operación de traducción.

```csharp
var t = Matrix4.Translate(10, 0, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Ver también

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


