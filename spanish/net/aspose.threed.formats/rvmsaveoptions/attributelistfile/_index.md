---
title: "RvmSaveOptions.AttributeListFile"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad RvmSaveOptions. Obtiene o establece el nombre de archivo de la lista de atributos; el exportador generará un nombre basado en el nombre del archivo .rvm cuando esta propiedad no esté definida. El valor predeterminado es null"
type: docs
weight: 20
url: /es/net/aspose.threed.formats/rvmsaveoptions/attributelistfile/
---
## RvmSaveOptions.AttributeListFile property

Obtiene o establece el nombre de archivo de la lista de atributos, el exportador generará un nombre basado en el nombre del archivo .rvm cuando esta propiedad no esté definida, el valor predeterminado es null.

```csharp
public string AttributeListFile { get; set; }
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


