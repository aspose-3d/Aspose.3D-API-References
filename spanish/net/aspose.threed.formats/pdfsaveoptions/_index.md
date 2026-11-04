---
title: "Clase PdfSaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.PdfSaveOptions. Las opciones de guardado al exportar a PDF"
type: docs
weight: 1420
url: /es/net/aspose.threed.formats/pdfsaveoptions/
---
## PdfSaveOptions class

Las opciones de guardado en la exportación de PDF.

```csharp
public class PdfSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Constructor de `PdfSaveOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AuxiliaryColor](../../aspose.threed.formats/pdfsaveoptions/auxiliarycolor/) { get; set; } | Obtiene o establece el color auxiliar que se usará al renderizar el contenido 3D. La interpretación de este color depende del [`RenderMode`](./rendermode/) |
| [BackgroundColor](../../aspose.threed.formats/pdfsaveoptions/backgroundcolor/) { get; set; } | Color de fondo de la vista 3D en el archivo PDF. |
| [EmbedTextures](../../aspose.threed.formats/pdfsaveoptions/embedtextures/) { get; set; } | Incrusta las texturas externas en el archivo PDF, el valor predeterminado es false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [FaceColor](../../aspose.threed.formats/pdfsaveoptions/facecolor/) { get; set; } | Obtiene o establece el color de cara que se usará al renderizar el contenido 3D. Esto solo es relevante cuando el [`RenderMode`](./rendermode/) tiene el valor Illustration. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [FlipCoordinateSystem](../../aspose.threed.formats/pdfsaveoptions/flipcoordinatesystem/) { get; set; } | Obtiene o establece si se invierte el sistema de coordenadas de la escena durante la exportación. |
| [LightingScheme](../../aspose.threed.formats/pdfsaveoptions/lightingscheme/) { get; set; } | LightingScheme especifica la iluminación a aplicar al arte 3D. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [RenderMode](../../aspose.threed.formats/pdfsaveoptions/rendermode/) { get; set; } | El modo de renderizado especifica el estilo en que se renderiza el arte 3D. |

### Ver también

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


