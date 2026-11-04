---
title: "Clase JtLoadOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions. Opciones de carga para Siemens JT"
type: docs
weight: 1380
url: /es/net/aspose.threed.formats.siemensjt/jtloadoptions/
---
## JtLoadOptions class

Opciones de carga para Siemens JT

```csharp
public class JtLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar.(Heredado de [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar.(Heredado de [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena de exportación/importación. Es opcional, pero útil al serializar recursos externos como el material de OBJ.(Heredado de [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado.(Heredado de [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | Cargar información PMI del archivo JT si es posible, los datos se guardarán como la propiedad "PMI" de [`AssetInfo`](../../aspose.threed/scene/assetinfo/). El valor predeterminado es false. |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | Cargar propiedades de la tabla de propiedades de JT como propiedades de Aspose.3D. El valor predeterminado es false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar archivos externos para cargar.(Heredado de [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |

### Ver también

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)


