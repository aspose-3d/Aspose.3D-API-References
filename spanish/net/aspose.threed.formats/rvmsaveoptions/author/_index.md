---
title: "RvmSaveOptions.Author"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "RvmSaveOptions propiedad. Información del autor valor predeterminado es 3daspose"
type: docs
weight: 40
url: /es/net/aspose.threed.formats/rvmsaveoptions/author/
---
## RvmSaveOptions.Author property

Información del autor, el valor predeterminado es '3d@aspose'

```csharp
public string Author { get; set; }
```

## Ejemplos

El siguiente código muestra cómo exportar atributos en RVM.

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//Se requiere el nombre del nodo para exportar atributos
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//Las propiedades con el prefijo rvm: se exportarán.
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### Ver también

* class [RvmSaveOptions](../)
* namespace [Aspose.ThreeD.Formats](../../rvmsaveoptions/)
* assembly [Aspose.3D](../../../)


