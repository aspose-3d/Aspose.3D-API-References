---
title: "Klasse PdfFormat"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.PdfFormat Klasse. Adobes Portable Document Format"
type: docs
weight: 1380
url: /de/net/aspose.threed.formats/pdfformat/
---
## PdfFormat class

Adobes Portable Document Format

```csharp
public class PdfFormat : FileFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Liest, ob Aspose.3D den Export der Szene in das aktuelle Dateiformat unterstützt. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Liest, ob Aspose.3D den Import der Szene aus dem aktuellen Dateiformat unterstützt. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | Liest den Inhaltstyp des Dateiformats |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | Liest den Erweiterungsnamen dieses Typs. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | Liest die Erweiterungsnamen dieses Typs. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | Liest den Dateiformattyp |
| [Version](../../aspose.threed/fileformat/version/) { get; } | Liest die Dateiformatversion |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Erstelle Standard-Ladeoptionen für dieses Dateiformat |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Erstelle standardmäßige Speicheroptionen für dieses Dateiformat |
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract)(Stream, byte[]) | Roh-3D-Inhalt aus PDF-Stream extrahieren. |
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract_1)(string, byte[]) | Roh-3D-Inhalt aus PDF-Datei extrahieren. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_1)(string) | 3D-Szenen aus PDF-Datei extrahieren. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene)(Stream, byte[]) | Roh-3D-Inhalt aus PDF-Stream extrahieren. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_2)(string, byte[]) | 3D-Szenen aus PDF-Datei extrahieren. |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Formatiert als Zeichenkette |

## Beispiele

Der folgende Code zeigt, wie man alle unterstützten 3D-Szenen aus einer 3D-PDF-Datei extrahiert und sie im OBJ-Format speichert.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Siehe auch

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


