---
title: "Klasse IOConfig"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.IOConfig Klasse. IO-Konfiguration für Serialisierung/Deserialisierung. Der Benutzer kann detaillierte Konfigurationen wie den Pfad für die Abhängigkeitssuche oder formatbezogene Einstellungen hier angeben."
type: docs
weight: 1300
url: /de/net/aspose.threed.formats/ioconfig/
---
## IOConfig class

IO-Konfiguration für Serialisierung/Deserialisierung. Der Benutzer kann hier detaillierte Konfigurationen wie den Abhängigkeitsnachschlagepfad oder formatbezogene Einstellungen angeben.

```csharp
public class IOConfig
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |
| static [FileSystemFactory](../../aspose.threed.formats/ioconfig/filesystemfactory/) { get; set; } | Liest oder setzt die Fabrikklasse für das Dateisystem. Die Standardfabrik erstellt LocalFileSystem, das für Serverumgebungen nicht geeignet ist. |

### Siehe auch

* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


