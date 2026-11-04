---
title: "Clase A3dwSaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.A3dwSaveOptions. Opciones de guardado para el formato A3DW"
type: docs
weight: 1080
url: /es/net/aspose.threed.formats/a3dwsaveoptions/
---
## A3dwSaveOptions class

Opciones de guardado para el formato A3DW.

```csharp
public class A3dwSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [A3dwSaveOptions](a3dwsaveoptions/)() | Constructor de `A3dwSaveOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportMetaData](../../aspose.threed.formats/a3dwsaveoptions/exportmetadata/) { get; set; } | Exporta los metadatos asociados con Scene/Node al cliente. El valor predeterminado es true |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [MetaDataPrefix](../../aspose.threed.formats/a3dwsaveoptions/metadataprefix/) { get; set; } | Si esta propiedad no es nula, solo se exportarán las propiedades de Scene/Node que comiencen con este prefijo, y el prefijo será eliminado. |

### Ver también

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


