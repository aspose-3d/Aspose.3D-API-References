---
title: "Clase ZipArchiveFileSystem"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Utilities.ZipArchiveFileSystem. Sistema de archivos que proporciona acceso de solo lectura al archivo zip o flujo zip especificado. El sistema de archivos se eliminará después de la operación de abrir/guardar."
type: docs
weight: 2830
url: /es/net/aspose.threed.utilities/ziparchivefilesystem/
---
## ZipArchiveFileSystem class

Sistema de archivos que proporciona acceso de solo lectura al archivo zip o flujo zip especificado. El sistema de archivos se eliminará después de la operación de abrir/guardar.

```csharp
public class ZipArchiveFileSystem : FileSystem
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Dispose](../../aspose.threed.utilities/ziparchivefilesystem/dispose/)() | Elimina el ZipArchiveFileSystem y libera sus recursos internos. |
| override [ReadFile](../../aspose.threed.utilities/ziparchivefilesystem/readfile/)(string, IOConfig) | Abrir archivo para lectura |
| override [WriteFile](../../aspose.threed.utilities/ziparchivefilesystem/writefile/)(string, IOConfig) | Abrir archivo para escritura, no implementado en esta clase. |

### Ejemplos

El siguiente código muestra cómo importar un archivo y proporcionar archivos dependientes en un archivo zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//crear una instancia de opciones de carga y especificar un sistema de archivos zip
var opt = format.CreateLoadOptions();
opt.FileSystem = new ZipArchiveFileSystem("textures.zip");
//cargar el archivo
var scene = Scene.FromFile(inputFile, opt);
```

### Ver también

* class [FileSystem](../filesystem/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


