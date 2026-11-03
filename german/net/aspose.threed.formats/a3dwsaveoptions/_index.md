---
title: "Klasse A3dwSaveOptions"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.A3dwSaveOptions Klasse. Speicheroptionen für das A3DW-Format"
type: docs
weight: 1080
url: /de/net/aspose.threed.formats/a3dwsaveoptions/
---
## A3dwSaveOptions class

Speicheroptionen für das A3DW-Format.

```csharp
public class A3dwSaveOptions : SaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [A3dwSaveOptions](a3dwsaveoptions/)() | Konstruktor von `A3dwSaveOptions` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |
| [ExportMetaData](../../aspose.threed.formats/a3dwsaveoptions/exportmetadata/) { get; set; } | Exportiere Metadaten, die mit Scene/Node verknüpft sind, zum Client. Standardwert ist true |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Versucht, Texturen, die in der Szene verwendet werden, in das Ausgabeverzeichnis zu kopieren. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |
| [MetaDataPrefix](../../aspose.threed.formats/a3dwsaveoptions/metadataprefix/) { get; set; } | Wenn diese Eigenschaft nicht null ist, werden nur die Eigenschaften von Scene/Node, die mit diesem Präfix beginnen, exportiert, und das Präfix wird entfernt. |

### Siehe auch

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


