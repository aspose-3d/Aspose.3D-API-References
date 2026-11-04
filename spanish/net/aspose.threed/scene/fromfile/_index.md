---
title: "Scene.FromFile"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Scene. Abre la escena desde la ruta especificada usando el formato de archivo indicado"
type: docs
weight: 20
url: /es/net/aspose.threed/scene/fromfile/
---
## FromFile(string, FileFormat, CancellationToken) {#fromfile_1}

Abre la escena desde la ruta especificada usando el formato de archivo especificado.

```csharp
public static Scene FromFile(string fileName, FileFormat format, 
    CancellationToken cancellationToken = default)
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

El siguiente código muestra cómo crear una escena desde un archivo

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", FileFormat.FBX7400ASCII, cts.Token);
```

### Ver también

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, LoadOptions, CancellationToken) {#fromfile_2}

Abre la escena desde la ruta especificada usando el formato de archivo especificado.

```csharp
public static Scene FromFile(string fileName, LoadOptions options, 
    CancellationToken cancellationToken = default)
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

El siguiente código muestra cómo crear una escena desde un archivo

```csharp
var cts = new CancellationTokenSource();
var opt = new FbxLoadOptions();
opt.LookupPaths.Add("textures");
Scene scene = Scene.FromFile("input.fbx", opt, cts.Token);
```

### Ver también

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string) {#fromfile}

Abre la escena desde la ruta especificada

```csharp
public static Scene FromFile(string fileName)
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

El siguiente código muestra cómo crear una escena desde un archivo

```csharp
Scene scene = Scene.FromFile("input.fbx");
```

### Ver también

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, CancellationToken) {#fromfile_3}

Abre la escena desde la ruta especificada

```csharp
public static Scene FromFile(string fileName, CancellationToken cancellationToken)
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

El siguiente código muestra cómo crear una escena desde un archivo

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", cts.Token);
```

### Ver también

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


