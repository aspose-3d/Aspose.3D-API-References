---
title: "Clase PdfFormat"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.PdfFormat. Formato de Documento Portátil de Adobe"
type: docs
weight: 1380
url: /es/net/aspose.threed.formats/pdfformat/
---
## PdfFormat class

Formato de Documento Portátil de Adobe

```csharp
public class PdfFormat : FileFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Obtiene si Aspose.3D admite la exportación de la escena al formato de archivo actual. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Obtiene si Aspose.3D admite la importación de la escena desde el formato de archivo actual. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | Obtiene el tipo de contenido del formato de archivo |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | Obtiene el nombre de la extensión de este tipo. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | Obtiene los nombres de las extensiones de este tipo. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | Obtiene el tipo de formato de archivo |
| [Version](../../aspose.threed/fileformat/version/) { get; } | Obtiene la versión del formato de archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Crea opciones de carga predeterminadas para este formato de archivo |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Crea opciones de guardado predeterminadas para este formato de archivo |
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract)(Stream, byte[]) | Extrae contenido 3D sin procesar del flujo PDF. |
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract_1)(string, byte[]) | Extrae contenido 3D sin procesar del archivo PDF. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_1)(string) | Extrae escenas 3D del archivo PDF. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene)(Stream, byte[]) | Extrae contenido 3D sin procesar del flujo PDF. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_2)(string, byte[]) | Extrae escenas 3D del archivo PDF. |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Formatea a cadena |

## Ejemplos

El siguiente código muestra cómo extraer todas las escenas 3D compatibles de un archivo PDF 3D y escribirlas en formato obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Ver también

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


