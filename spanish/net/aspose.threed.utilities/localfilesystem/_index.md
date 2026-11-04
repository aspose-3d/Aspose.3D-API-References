---
title: "LocalFileSystem"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: 
type: docs
weight: 2650
url: /es/net/aspose.threed.utilities/localfilesystem/
---
## LocalFileSystem class

El [`LocalFileSystem`](../localfilesystem) asignará las operaciones de lectura/escritura al directorio local.

```csharp
public class LocalFileSystem : FileSystem
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LocalFileSystem](localfilesystem)(string) | Inicializar un nuevo [`LocalFileSystem`](../localfilesystem) con el directorio base especificado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Libere el sistema de archivos y libere sus recursos. |
| override [ReadFile](../../aspose.threed.utilities/localfilesystem/readfile)(string, IOConfig) | Cree un flujo para leer dependencias. |
| override [WriteFile](../../aspose.threed.utilities/localfilesystem/writefile)(string, IOConfig) | Cree un flujo para escribir dependencias. |

### Ejemplos

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

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.3D.dll -->
