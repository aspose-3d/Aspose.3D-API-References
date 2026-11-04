---
title: "Scene.Open"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Scene. Abre la escena desde el flujo proporcionado usando el formato de archivo especificado"
type: docs
weight: 140
url: /es/net/aspose.threed/scene/open/
---
## Open(Stream, FileFormat, CancellationToken) {#open_1}

Abre la escena desde el flujo especificado usando el formato de archivo especificado.

```csharp
public void Open(Stream stream, FileFormat format, CancellationToken cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| formato | FileFormat | Formato de archivo. |
| cancellationToken | CancellationToken | Token de cancelación para la tarea de carga |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ImportException](../../importexception/) | Lanzado cuando la entrada no es un formato 3D válido |

## Ejemplos

El siguiente código muestra cómo abrir una escena desde un flujo

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, FileFormat.GLTF2);
}
```

### Ver también

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, LoadOptions, CancellationToken) {#open_2}

Abre la escena desde el flujo especificado usando la configuración de E/S especificada.

```csharp
public void Open(Stream stream, LoadOptions options, CancellationToken cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| opciones | LoadOptions | Configuración más detallada para abrir el flujo. |
| cancellationToken | CancellationToken | Token de cancelación para la tarea de carga |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ImportException](../../importexception/) | Lanzado cuando la entrada no es un formato 3D válido |

## Ejemplos

El siguiente código muestra cómo abrir una escena desde un flujo con opciones de carga adicionales

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    var opt = new FbxLoadOptions();
    opt.LookupPaths.Add("textures");
    scene.Open(stream, opt);
}
```

### Ver también

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream) {#open}

Abre la escena desde el flujo especificado

```csharp
public void Open(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ImportException](../../importexception/) | Lanzado cuando la entrada no es un formato 3D válido |

## Ejemplos

El siguiente código muestra cómo abrir una escena desde un flujo

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream);
}
```

### Ver también

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, CancellationToken) {#open_3}

Abre la escena desde el flujo especificado

```csharp
public void Open(Stream stream, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| cancellationToken | CancellationToken | Token de cancelación para la tarea de carga |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ImportException](../../importexception/) | Lanzado cuando la entrada no es un formato 3D válido |

## Ejemplos

El siguiente código muestra cómo abrir una escena desde un flujo con un token de cancelación

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, cts.Token);
}
```

### Ver también

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, FileFormat, CancellationToken) {#open_5}

Abre la escena desde la ruta especificada usando el formato de archivo especificado.

```csharp
public void Open(string fileName, FileFormat format, CancellationToken cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo. |
| formato | FileFormat | Formato de archivo. |
| cancellationToken | CancellationToken | Token de cancelación para la tarea de carga |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ImportException](../../importexception/) | Lanzado cuando la entrada no es un formato 3D válido |

## Ejemplos

El siguiente código muestra cómo abrir una escena desde un nombre de archivo con un token de cancelación

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
scene.Open("input.fbx", FileFormat.FBX7400ASCII, cts.Token);

```

### Ver también

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions) {#open_6}

Abre la escena desde la ruta especificada usando el formato de archivo especificado.

```csharp
public void Open(string fileName, LoadOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo. |
| opciones | LoadOptions | Configuración más detallada para abrir el flujo. |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ImportException](../../importexception/) | Lanzado cuando la entrada no es un formato 3D válido |

## Ejemplos

El siguiente código muestra cómo abrir una escena desde un nombre de archivo con opciones de carga adicionales

```csharp
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts);
```

### Ver también

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions, CancellationToken) {#open_7}

Abre la escena desde la ruta especificada usando el formato de archivo especificado.

```csharp
public void Open(string fileName, LoadOptions options, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo. |
| opciones | LoadOptions | Configuración más detallada para abrir el flujo. |
| cancellationToken | CancellationToken | Token de cancelación para la tarea de carga |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ImportException](../../importexception/) | Lanzado cuando la entrada no es un formato 3D válido |

## Ejemplos

El siguiente código muestra cómo abrir una escena desde un nombre de archivo con opciones de carga adicionales y token de cancelación

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts, cts.Token);
```

### Ver también

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string) {#open_4}

Abre la escena desde la ruta especificada

```csharp
public void Open(string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo. |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ImportException](../../importexception/) | Lanzado cuando la entrada no es un formato 3D válido |

## Ejemplos

El siguiente código muestra cómo abrir una escena desde un nombre de archivo

```csharp
Scene scene = new Scene();
scene.Open("input.fbx");
```

### Ver también

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, CancellationToken) {#open_8}

Abre la escena desde la ruta especificada

```csharp
public void Open(string fileName, CancellationToken cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo. |
| cancellationToken | CancellationToken | Token de cancelación para la tarea de carga |

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura de la entrada |
| [ImportException](../../importexception/) | Lanzado cuando la entrada no es un formato 3D válido |

## Ejemplos

El siguiente código muestra cómo abrir una escena desde un nombre de archivo y una fuente de token de cancelación

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
scene.Open("input.fbx", cts.Token);
```

### Ver también

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


