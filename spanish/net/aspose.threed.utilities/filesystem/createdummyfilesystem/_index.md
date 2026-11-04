---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método de FileSystem. Crea un sistema de archivos ficticio; las operaciones de lectura/escritura son operaciones ficticias"
type: docs
weight: 10
url: /es/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

Crear un sistema de archivos ficticio, las operaciones de lectura/escritura son operaciones ficticias.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### Valor de retorno

Un sistema de archivos ficticio

## Ejemplos

El siguiente código muestra cómo exportar el archivo a memoria y omitir toda la generación de archivos dependientes.

```csharp
//crear una escena con material
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//crear una opción de guardado y especificar el sistema de archivos, de modo que el archivo dependiente se escriba en memoria
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//El nombre del archivo de material del obj está asociado con el nombre del archivo del obj, por lo que necesitamos un nombre explícito.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Ver también

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


