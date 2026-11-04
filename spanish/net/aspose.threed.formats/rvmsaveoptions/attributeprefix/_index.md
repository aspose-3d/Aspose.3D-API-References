---
title: "RvmSaveOptions.AttributePrefix"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "RvmSaveOptions propiedad. Obtiene o establece el prefijo de los atributos que se exportarán; la propiedad exportada no contendrá prefijo; las propiedades personalizadas con un prefijo diferente no se exportarán; valor predeterminado es rvm. Por ejemplo, si una propiedad es rvmRefno345, el atributo exportado será Refno 345; el prefijo se elimina"
type: docs
weight: 30
url: /es/net/aspose.threed.formats/rvmsaveoptions/attributeprefix/
---
## RvmSaveOptions.AttributePrefix property

Obtiene o establece el prefijo de los atributos que se exportarán, la propiedad exportada no contendrá prefijo, las propiedades personalizadas con un prefijo diferente no se exportarán, el valor predeterminado es 'rvm:'. Por ejemplo, si una propiedad es rvm:Refno=345, el atributo exportado será Refno = 345, el prefijo se elimina.

```csharp
public string AttributePrefix { get; set; }
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


