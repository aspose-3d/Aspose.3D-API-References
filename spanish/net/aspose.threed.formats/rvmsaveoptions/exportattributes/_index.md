---
title: "RvmSaveOptions.ExportAttributes"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "RvmSaveOptions propiedad. Obtiene o establece si exportar la lista de atributos a un archivo .att externo valor predeterminado es false"
type: docs
weight: 60
url: /es/net/aspose.threed.formats/rvmsaveoptions/exportattributes/
---
## RvmSaveOptions.ExportAttributes property

Obtiene o establece si se exporta la lista de atributos a un archivo .att externo, el valor predeterminado es false.

```csharp
public bool ExportAttributes { get; set; }
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


