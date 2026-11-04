---
title: "IOConfig.FileSystemFactory"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad IOConfig. Obtiene o establece la clase fábrica para FileSystem. La fábrica predeterminada creará LocalFileSystem, que no es adecuada para entornos de servidor"
type: docs
weight: 60
url: /es/net/aspose.threed.formats/ioconfig/filesystemfactory/
---
## IOConfig.FileSystemFactory property

Obtiene o establece la clase de fábrica para FileSystem. La fábrica predeterminada creará LocalFileSystem, que no es adecuada para entornos de servidor.

```csharp
public static FileSystemFactory FileSystemFactory { get; set; }
```

## Ejemplos

El FileSystem predeterminado en SaveOptions/LoadOptions es un sistema de archivos basado en directorios. Puede sobrescribir la implementación predeterminada especificándola a través de IOConfig.FileSystemFactory:

```csharp
IOConfig.FileSystemFactory = () => {
    return FileSystem.CreateDummyFileSystem();
};

Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

//opt.FileSystem será ahora un sistema de archivos ficticio
var opt = new ObjSaveOptions();
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//El archivo de material output.mtl no se escribirá en ningún lugar porque hemos configurado un sistema de archivos ficticio como implementación predeterminada.
```

### Ver también

* delegate [FileSystemFactory](../../filesystemfactory/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


