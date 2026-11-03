---
title: "Klasse PdfSaveOptions"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.PdfSaveOptions Klasse. Die Speicheroptionen beim PDF-Export."
type: docs
weight: 1420
url: /de/net/aspose.threed.formats/pdfsaveoptions/
---
## PdfSaveOptions class

Die Speicheroptionen beim PDF-Export.

```csharp
public class PdfSaveOptions : SaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Konstruktor von `PdfSaveOptions` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AuxiliaryColor](../../aspose.threed.formats/pdfsaveoptions/auxiliarycolor/) { get; set; } | Gibt die Hilfsfarbe an, die beim Rendern des 3D-Inhalts verwendet wird, oder legt sie fest. Die Interpretation dieser Farbe hängt vom [`RenderMode`](./rendermode/) ab. |
| [BackgroundColor](../../aspose.threed.formats/pdfsaveoptions/backgroundcolor/) { get; set; } | Hintergrundfarbe der 3D-Ansicht in der PDF-Datei. |
| [EmbedTextures](../../aspose.threed.formats/pdfsaveoptions/embedtextures/) { get; set; } | Betten Sie die externen Texturen in die PDF-Datei ein, Standardwert ist false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Versucht, Texturen, die in der Szene verwendet werden, in das Ausgabeverzeichnis zu kopieren. |
| [FaceColor](../../aspose.threed.formats/pdfsaveoptions/facecolor/) { get; set; } | Gibt die Flächenfarbe an, die beim Rendern des 3D-Inhalts verwendet wird, oder legt sie fest. Dies ist nur relevant, wenn der [`RenderMode`](./rendermode/) den Wert Illustration hat. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden. |
| [FlipCoordinateSystem](../../aspose.threed.formats/pdfsaveoptions/flipcoordinatesystem/) { get; set; } | Gibt an, ob das Koordinatensystem der Szene beim Export umgekehrt wird, oder legt dies fest. |
| [LightingScheme](../../aspose.threed.formats/pdfsaveoptions/lightingscheme/) { get; set; } | LightingScheme gibt die Beleuchtung an, die auf 3D-Arbeiten angewendet wird. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |
| [RenderMode](../../aspose.threed.formats/pdfsaveoptions/rendermode/) { get; set; } | Rendermodus gibt den Stil an, in dem das 3D‑Werk gerendert wird. |

### Siehe auch

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


