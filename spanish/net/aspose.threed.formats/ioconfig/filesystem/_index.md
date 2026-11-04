---
title: "IOConfig.FileSystem"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad IOConfig. Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado"
type: docs
weight: 40
url: /es/net/aspose.threed.formats/ioconfig/filesystem/
---
## IOConfig.FileSystem property

Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado.

```csharp
public FileSystem FileSystem { get; set; }
```

## Ejemplos

El FileSystem predeterminado es LocalFileSystem, no es seguro en entornos como el lado del servidor, pero puede sobrescribir el acceso al sistema de archivos especificando una implementación diferente. Aspose.3D proporciona diferentes implementaciones de FileSystem como: sistema de archivos basado en memoria, sistema de archivos basado en directorios, sistema de archivos ficticio, sistema de archivos Zip y también puede usar su propia implementación.

```csharp
Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

var opt = new ObjSaveOptions();
var memFs = new Dictionary<string, MemoryStream>();
opt.FileSystem = FileSystem.CreateMemoryFileSystem(memFs);
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//El material se escribirá en la variable memFs llamada output.mtl
var materialInBytes = memFs["output.mtl"].ToArray();
```

### Ver también

* class [FileSystem](../../../aspose.threed.utilities/filesystem/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


