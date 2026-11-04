---
title: "Clase RvmSaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.RvmSaveOptions. Opciones de guardado para el archivo Aveva PDMS RVM"
type: docs
weight: 1480
url: /es/net/aspose.threed.formats/rvmsaveoptions/
---
## RvmSaveOptions class

Opciones de guardado para el archivo RVM de Aveva PDMS.

```csharp
public class RvmSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RvmSaveOptions](rvmsaveoptions/#constructor)() | Constructor de `RvmSaveOptions` |
| [RvmSaveOptions](rvmsaveoptions/#constructor_1)(FileContentType) | Constructor de `RvmSaveOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttributeListFile](../../aspose.threed.formats/rvmsaveoptions/attributelistfile/) { get; set; } | Obtiene o establece el nombre de archivo de la lista de atributos, el exportador generará un nombre basado en el nombre del archivo .rvm cuando esta propiedad no esté definida, el valor predeterminado es null. |
| [AttributePrefix](../../aspose.threed.formats/rvmsaveoptions/attributeprefix/) { get; set; } | Obtiene o establece el prefijo de los atributos que se exportarán, la propiedad exportada no contendrá prefijo, las propiedades personalizadas con un prefijo diferente no se exportarán, el valor predeterminado es 'rvm:'. Por ejemplo, si una propiedad es rvm:Refno=345, el atributo exportado será Refno = 345, el prefijo se elimina. |
| [Author](../../aspose.threed.formats/rvmsaveoptions/author/) { get; set; } | Información del autor, el valor predeterminado es '3d@aspose' |
| [CreationTime](../../aspose.threed.formats/rvmsaveoptions/creationtime/) { get; set; } | La marca de tiempo que exportó este archivo, el valor predeterminado es la hora actual |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportAttributes](../../aspose.threed.formats/rvmsaveoptions/exportattributes/) { get; set; } | Obtiene o establece si se exporta la lista de atributos a un archivo .att externo, el valor predeterminado es false. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileNote](../../aspose.threed.formats/rvmsaveoptions/filenote/) { get; set; } | Nota del archivo en el encabezado del archivo. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |

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

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


