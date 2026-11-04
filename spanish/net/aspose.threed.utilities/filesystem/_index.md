---
title: "Clase FileSystem"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Utilities.FileSystem. Encapsulación del sistema de archivos. Aspose.3D usará esto para leer/escribir dependencias"
type: docs
weight: 2750
url: /es/net/aspose.threed.utilities/filesystem/
---
## FileSystem class

Encapsulación del sistema de archivos. Aspose.3D usará esto para leer/escribir dependencias.

```csharp
public abstract class FileSystem : IDisposable
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateDummyFileSystem](../../aspose.threed.utilities/filesystem/createdummyfilesystem/)() | Crear un sistema de archivos ficticio, las operaciones de lectura/escritura son operaciones ficticias. |
| static [CreateLocalFileSystem](../../aspose.threed.utilities/filesystem/createlocalfilesystem/)(string) | Inicializar un nuevo `FileSystem` que solo acceda al directorio local. Todas las lecturas/escrituras de archivos en esta instancia de FileSystem se mapearán al directorio especificado. |
| static [CreateMemoryFileSystem](../../aspose.threed.utilities/filesystem/creatememoryfilesystem/)(Dictionary&lt;string, MemoryStream&gt;) |  |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem_1)(string) | Sistema de archivos que proporciona acceso de solo lectura al archivo zip o flujo zip especificado. El sistema de archivos se eliminará después de la operación de abrir/guardar. |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem)(Stream, string) | Crear un sistema de archivos para proporcionar acceso de solo lectura a un archivo zip o flujo zip especificado. El sistema de archivos se eliminará después de la operación de abrir/guardar. |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose/)() | Libere el sistema de archivos y libere sus recursos. |
| abstract [ReadFile](../../aspose.threed.utilities/filesystem/readfile/)(string, IOConfig) | Cree un flujo para leer dependencias. |
| abstract [WriteFile](../../aspose.threed.utilities/filesystem/writefile/)(string, IOConfig) | Cree un flujo para escribir dependencias. |

## Ejemplos

El siguiente código muestra cómo importar un archivo y proporcionar archivos dependientes en un directorio dado

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//crear una instancia de opciones de carga y especificar un sistema de archivos zip
var opt = format.CreateLoadOptions();
opt.FileSystem = new LocalFileSystem("textures/");
//cargar el archivo
var scene = Scene.FromFile(inputFile, opt);
```

### Ver también

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


