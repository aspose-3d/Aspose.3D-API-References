---
title: "Scene.Save"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Scene. Guarda la escena en un flujo usando el formato de archivo especificado"
type: docs
weight: 160
url: /es/net/aspose.threed/scene/save/
---
## Save(Stream, FileFormat) {#save}

Guarda la escena en un flujo usando el formato de archivo especificado.

```csharp
public void Save(Stream stream, FileFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| formato | FileFormat | Formato. |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ExportException](../../exportexception/) | Se lanza cuando falla la exportación de la escena al formato 3D especificado |

## Ejemplos

El siguiente código muestra cómo guardar la escena

```csharp
Scene scene = Scene.FromFile("input.fbx");
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ);
}
```

### Ver también

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, FileFormat, CancellationToken) {#save_1}

Guarda la escena en un flujo usando el formato de archivo especificado.

```csharp
public void Save(Stream stream, FileFormat format, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| formato | FileFormat | Formato. |
| cancellationToken | CancellationToken | Token de cancelación para la tarea de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ExportException](../../exportexception/) | Se lanza cuando falla la exportación de la escena al formato 3D especificado |

## Ejemplos

El siguiente código muestra cómo guardar la escena

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ, cts.Token);
}
```

### Ver también

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions) {#save_2}

Guarda la escena en un flujo usando el formato de archivo especificado.

```csharp
public void Save(Stream stream, SaveOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| opciones | SaveOptions | Configuración más detallada para guardar el flujo. |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ExportException](../../exportexception/) | Se lanza cuando falla la exportación de la escena al formato 3D especificado |

## Ejemplos

El siguiente código muestra cómo guardar la escena

```csharp
Scene scene = Scene.FromFile("input.fbx");
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Ver también

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions, CancellationToken) {#save_3}

Guarda la escena en un flujo usando el formato de archivo especificado.

```csharp
public void Save(Stream stream, SaveOptions options, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| opciones | SaveOptions | Configuración más detallada para guardar el flujo. |
| cancellationToken | CancellationToken | Token de cancelación para la tarea de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ExportException](../../exportexception/) | Se lanza cuando falla la exportación de la escena al formato 3D especificado |

## Ejemplos

El siguiente código muestra cómo guardar la escena

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt, cts.Token);
}
```

### Ver también

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string) {#save_4}

Guarda la escena en la ruta especificada usando el formato de archivo especificado.

```csharp
public void Save(string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo. |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ExportException](../../exportexception/) | Se lanza cuando falla la exportación de la escena al formato 3D especificado |

## Ejemplos

El siguiente código muestra cómo guardar la escena

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz");
```

### Ver también

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat) {#save_5}

Guarda la escena en la ruta especificada usando el formato de archivo especificado.

```csharp
public void Save(string fileName, FileFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo. |
| formato | FileFormat | Formato. |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ExportException](../../exportexception/) | Se lanza cuando falla la exportación de la escena al formato 3D especificado |

## Ejemplos

El siguiente código muestra cómo guardar la escena

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ);
```

### Ver también

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat, CancellationToken) {#save_6}

Guarda la escena en la ruta especificada usando el formato de archivo especificado.

```csharp
public void Save(string fileName, FileFormat format, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo. |
| formato | FileFormat | Formato. |
| cancellationToken | CancellationToken | Token de cancelación para la tarea de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ExportException](../../exportexception/) | Se lanza cuando falla la exportación de la escena al formato 3D especificado |

## Ejemplos

El siguiente código muestra cómo guardar la escena

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ, cts.Token);
```

### Ver también

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions) {#save_7}

Guarda la escena en la ruta especificada usando el formato de archivo especificado.

```csharp
public void Save(string fileName, SaveOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo. |
| opciones | SaveOptions | Configuración más detallada para guardar el flujo. |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ExportException](../../exportexception/) | Se lanza cuando falla la exportación de la escena al formato 3D especificado |

## Ejemplos

El siguiente código muestra cómo guardar la escena

```csharp
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts);
```

### Ver también

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions, CancellationToken) {#save_8}

Guarda la escena en la ruta especificada usando el formato de archivo especificado.

```csharp
public void Save(string fileName, SaveOptions options, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo. |
| opciones | SaveOptions | Configuración más detallada para guardar el flujo. |
| cancellationToken | CancellationToken | Token de cancelación para la tarea de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ExportException](../../exportexception/) | Se lanza cuando falla la exportación de la escena al formato 3D especificado |

## Ejemplos

El siguiente código muestra cómo guardar la escena

```csharp
var cts = new CancellationTokenSource();
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts, cts.Token);
```

### Ver también

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


