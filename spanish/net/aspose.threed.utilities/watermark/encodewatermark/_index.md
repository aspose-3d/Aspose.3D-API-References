---
title: "Watermark.EncodeWatermark"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método de Watermark. Codifica un texto en una marca de agua ciega de malla"
type: docs
weight: 20
url: /es/net/aspose.threed.utilities/watermark/encodewatermark/
---
## EncodeWatermark(Mesh, string) {#encodewatermark}

Codificar un texto en la marca de agua ciega de la malla.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entrada | Malla | Malla para codificar una marca de agua ciega |
| texto | String | Texto para codificar en la malla |

### Valor de retorno

Una nueva instancia de malla con marca de agua ciega codificada

## Observaciones

Tanto `EncodeWatermark` como [`DecodeWatermark`](../decodewatermark/) realizarán la verificación de licencia. El uso en modo de prueba lanzará una excepción; puedes usar [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) para suprimir la excepción, pero no eliminará la restricción aquí. Se requiere una licencia válida para usar estas funciones sin restricciones.

## Ejemplos

El siguiente código muestra cómo codificar una marca de agua oculta en una malla y guardarla en un archivo ply.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello");
new Scene(encodedMesh).Save("test.ply");
```

### Ver también

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string) {#encodewatermark_1}

Codificar un texto en la marca de agua ciega de la malla.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entrada | Malla | Malla para codificar una marca de agua ciega |
| texto | String | Texto para codificar en la malla |
| contraseña | String | Contraseña para proteger la marca de agua, es opcional. |

### Valor de retorno

Una nueva instancia de malla con marca de agua ciega codificada

## Observaciones

Tanto `EncodeWatermark` como [`DecodeWatermark`](../decodewatermark/) realizarán la verificación de licencia. El uso en modo de prueba lanzará una excepción; puedes usar [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) para suprimir la excepción, pero no eliminará la restricción aquí. Se requiere una licencia válida para usar estas funciones sin restricciones.

## Ejemplos

El siguiente código muestra cómo codificar una marca de agua oculta en una malla y guardarla en un archivo ply.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### Ver también

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string, bool) {#encodewatermark_2}

Codificar un texto en la marca de agua ciega de la malla.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password, bool permanent)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entrada | Malla | Malla para codificar una marca de agua ciega |
| texto | String | Texto para codificar en la malla |
| contraseña | String | Contraseña para proteger la marca de agua, es opcional. |
| permanente | Boolean | La marca de agua permanente no será sobrescrita ni eliminada. |

### Valor de retorno

Una nueva instancia de malla con marca de agua ciega codificada

## Observaciones

Tanto `EncodeWatermark` como [`DecodeWatermark`](../decodewatermark/) realizarán la verificación de licencia. El uso en modo de prueba lanzará una excepción; puedes usar [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) para suprimir la excepción, pero no eliminará la restricción aquí. Se requiere una licencia válida para usar estas funciones sin restricciones.

## Ejemplos

El siguiente código muestra cómo codificar una marca de agua oculta en una malla y guardarla en un archivo ply.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### Ver también

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


