---
title: "Scene.FromStream"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Scene. Abre la escena desde el flujo proporcionado usando el formato de archivo especificado"
type: docs
weight: 30
url: /es/net/aspose.threed/scene/fromstream/
---
## FromStream(Stream, FileFormat, CancellationToken) {#fromstream}

Abre la escena desde el flujo especificado usando el formato de archivo especificado.

```csharp
public static Scene FromStream(Stream stream, FileFormat format, 
    CancellationToken cancellationToken = default)
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

El siguiente código muestra cómo crear una escena a partir de un flujo

```csharp
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream);
}
```

### Ver también

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, LoadOptions, CancellationToken) {#fromstream_1}

Abre la escena desde el flujo especificado usando la configuración de E/S especificada.

```csharp
public static Scene FromStream(Stream stream, LoadOptions options, 
    CancellationToken cancellationToken = default)
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

El siguiente código muestra cómo crear una escena a partir de un flujo con opciones de carga

```csharp
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, opts);
}
```

### Ver también

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, CancellationToken) {#fromstream_2}

Abre la escena desde el flujo especificado

```csharp
public static Scene FromStream(Stream stream, CancellationToken cancellationToken = default)
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

El siguiente código muestra cómo crear una escena a partir de un flujo con una fuente de token de cancelación

```csharp
var cts = new CancellationTokenSource();
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, cts.Token);
}
```

### Ver también

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


