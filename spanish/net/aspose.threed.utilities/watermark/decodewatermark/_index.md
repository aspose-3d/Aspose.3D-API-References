---
title: "Watermark.DecodeWatermark"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método de Watermark. Decodifica la marca de agua de una malla"
type: docs
weight: 10
url: /es/net/aspose.threed.utilities/watermark/decodewatermark/
---
## DecodeWatermark(Mesh) {#decodewatermark}

Decodificar la marca de agua de una malla

```csharp
public static string DecodeWatermark(Mesh input)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entrada | Malla | La malla para extraer la marca de agua |

### Valor de retorno

Marca de agua ciega o nulo si no se decodifica ninguna marca de agua.

### Excepciones

| excepción | condición |
| --- | --- |
| UnauthorizedAccessException | La malla está protegida por contraseña, y la contraseña proporcionada es incorrecta. |

## Observaciones

Ambos [`EncodeWatermark`](../encodewatermark/) y `DecodeWatermark` realizarán la verificación de licencia. El uso en modo de prueba lanzará una excepción, puedes usar [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) para suprimir la excepción, pero no eliminará la restricción aquí. Se requiere una licencia válida para usar estas funciones sin restricciones.

## Ejemplos

El siguiente código muestra cómo decodificar una marca de agua ciega de una malla guardada en un archivo 3D

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh);
```

### Ver también

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## DecodeWatermark(Mesh, string) {#decodewatermark_1}

Decodificar la marca de agua de una malla

```csharp
public static string DecodeWatermark(Mesh input, string password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entrada | Malla | La malla para extraer la marca de agua |
| contraseña | String | La contraseña para descifrar la marca de agua |

### Valor de retorno

Marca de agua ciega o nulo si no se decodifica ninguna marca de agua.

### Excepciones

| excepción | condición |
| --- | --- |
| UnauthorizedAccessException | La malla está protegida por contraseña, y la contraseña proporcionada es incorrecta. |

## Ejemplos

El siguiente código muestra cómo decodificar una marca de agua ciega de una malla guardada en un archivo 3D

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh, "password");
```

### Ver también

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


