---
title: "FileSystem.CreateZipFileSystem"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método de FileSystem. Crea un sistema de archivos para proporcionar acceso de solo lectura al archivo zip o flujo zip especificado. El sistema de archivos se eliminará después de la operación de abrir/guardar"
type: docs
weight: 40
url: /es/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

Crear un sistema de archivos para proporcionar acceso de solo lectura a un archivo zip o flujo zip especificado. El sistema de archivos se eliminará después de la operación de abrir/guardar.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo para acceder al archivo zip |
| baseDir | String | El directorio base dentro del archivo zip. |

### Valor de retorno

Un sistema de archivos zip

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura del flujo. |

## Observaciones

Este es un sistema de archivos de solo lectura, por lo que no se admiten operaciones de escritura.

## Ejemplos

El siguiente código muestra cómo importar un archivo y proporcionar archivos dependientes en un archivo zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//crear una instancia de opciones de carga y especificar un sistema de archivos zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//cargar el archivo
var scene = Scene.FromFile(inputFile, opt);
```

### Ver también

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

Sistema de archivos que proporciona acceso de solo lectura al archivo zip o flujo zip especificado. El sistema de archivos se eliminará después de la operación de abrir/guardar.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre del archivo del zip. |

### Valor de retorno

Un sistema de archivos zip

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Lanzado cuando falla la lectura del flujo. |

## Ejemplos

El siguiente código muestra cómo importar un archivo y proporcionar archivos dependientes en un archivo zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//crear una instancia de opciones de carga y especificar un sistema de archivos zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//cargar el archivo
var scene = Scene.FromFile(inputFile, opt);
```

### Ver también

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


