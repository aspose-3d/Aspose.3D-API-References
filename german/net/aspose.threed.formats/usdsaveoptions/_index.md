---
title: "Klasse UsdSaveOptions"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.UsdSaveOptions Klasse. Speicheroptionen für USD/USDZ-Formate"
type: docs
weight: 1540
url: /de/net/aspose.threed.formats/usdsaveoptions/
---
## UsdSaveOptions class

Speicheroptionen für die Formate USD/USDZ.

```csharp
public class UsdSaveOptions : SaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [UsdSaveOptions](usdsaveoptions/#constructor)() | Initialisiere ein neues `UsdSaveOptions` mit dem [`USD`](../../aspose.threed/fileformat/usd/) Format |
| [UsdSaveOptions](usdsaveoptions/#constructor_1)(FileFormat) | Initialisiere ein neues `UsdSaveOptions` mit dem angegebenen USD/USDZ-Format. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |
| [ExportMetaData](../../aspose.threed.formats/usdsaveoptions/exportmetadata/) { get; set; } | Exportiere die Eigenschaften des Knotens über das customData-Feld von USD. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Versucht, Texturen, die in der Szene verwendet werden, in das Ausgabeverzeichnis zu kopieren. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |
| [MaterialConverter](../../aspose.threed.formats/usdsaveoptions/materialconverter/) { get; set; } | Benutzerdefinierter Konverter, um das Material der Geometrie in ein PBR-Material zu konvertieren. Wenn dies nicht zugewiesen ist, konvertiert der USD-Exporter das Standardmaterial automatisch in ein PBR-Material. Standardwert ist null |
| [PrimitiveToMesh](../../aspose.threed.formats/usdsaveoptions/primitivetomesh/) { get; set; } | Konvertiere die primitiven Entitäten während des Exports in ein Mesh. Oder kodiere die Primitive direkt in die Ausgabedatei (verwendet Aspose's Erweiterungsdefinition für inoffizielle Primitive wie Dish, Torus). Standardwert ist true. |

### Siehe auch

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


