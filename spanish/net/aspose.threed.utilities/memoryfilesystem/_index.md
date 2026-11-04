---
title: "MemoryFileSystem"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: 
type: docs
weight: 2680
url: /es/net/aspose.threed.utilities/memoryfilesystem/
---
## MemoryFileSystem class

El [`MemoryFileSystem`](../memoryfilesystem) mapeará las operaciones de lectura/escritura a la memoria.

```csharp
public class MemoryFileSystem : FileSystem
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MemoryFileSystem](memoryfilesystem)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FileNames](../../aspose.threed.utilities/memoryfilesystem/filenames) { get; } | Nombres de archivo que están en este sistema de archivos en memoria. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Libere el sistema de archivos y libere sus recursos. |
| [GetFileContent](../../aspose.threed.utilities/memoryfilesystem/getfilecontent)(string) | Devuelve el contenido bruto del archivo especificado. Lanza FileNotFoundException si el archivo especificado no existe. |
| override [ReadFile](../../aspose.threed.utilities/memoryfilesystem/readfile)(string, IOConfig) | Cree un flujo para leer dependencias. |
| override [WriteFile](../../aspose.threed.utilities/memoryfilesystem/writefile)(string, IOConfig) | Cree un flujo para escribir dependencias. |

### Ejemplos

El siguiente código muestra cómo exportar un archivo a memoria, incluyendo el archivo dependiente mediante MemoryFileSystem.

```csharp
//crear una escena con material
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//crear una opción de guardado y especificar el sistema de archivos, de modo que el archivo dependiente se escriba en memoria
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var mfs = new MemoryFileSystem();
opt.FileSystem = mfs;
//El nombre del archivo de material del obj está asociado con el nombre del archivo del obj, por lo que necesitamos un nombre explícito.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
//el test.obj se escribió en la variable ms, y también podemos obtener el contenido del archivo test.mtl mediante
var materialFile = mfs.GetFileContent("test.mtl");
```

### Ver también

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.3D.dll -->
