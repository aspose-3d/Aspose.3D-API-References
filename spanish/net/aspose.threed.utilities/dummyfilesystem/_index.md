---
title: "DummyFileSystem"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: 
type: docs
weight: 2570
url: /es/net/aspose.threed.utilities/dummyfilesystem/
---
## DummyFileSystem class

Las operaciones de lectura/escritura son operaciones ficticias.

```csharp
public class DummyFileSystem : FileSystem
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DummyFileSystem](dummyfilesystem)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Libere el sistema de archivos y libere sus recursos. |
| override [ReadFile](../../aspose.threed.utilities/dummyfilesystem/readfile)(string, IOConfig) | Cree un flujo para leer dependencias. |
| override [WriteFile](../../aspose.threed.utilities/dummyfilesystem/writefile)(string, IOConfig) | Cree un flujo para escribir dependencias. |

### Ejemplos

El siguiente código muestra cómo exportar el archivo a memoria y omitir toda la generación de archivos dependientes.

```csharp
//crear una escena con material
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//crear una opción de guardado y especificar el sistema de archivos, de modo que el archivo dependiente se escriba en memoria
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = new DummyFileSystem();
opt.FileSystem = dfs;
//El nombre del archivo de material del obj está asociado con el nombre del archivo del obj, por lo que necesitamos un nombre explícito.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Ver también

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.3D.dll -->
