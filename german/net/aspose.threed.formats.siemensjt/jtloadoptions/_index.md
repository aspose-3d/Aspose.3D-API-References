---
title: "Klasse JtLoadOptions"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Klasse Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions. Ladeoptionen für Siemens JT"
type: docs
weight: 1380
url: /de/net/aspose.threed.formats.siemensjt/jtloadoptions/
---
## JtLoadOptions class

Ladeoptionen für Siemens JT

```csharp
public class JtLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. (Vererbt von [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. (Vererbt von [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/ importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material einer OBJ-Datei. (Vererbt von [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer, zu steuern, wie die externen Abhängigkeiten beim Laden/Speichern verwaltet werden. (Vererbt von [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | Lädt PMI-Informationen aus einer JT-Datei, falls möglich; die Daten werden als Eigenschaft "PMI" von [`AssetInfo`](../../aspose.threed/scene/assetinfo/) gespeichert. Der Standardwert ist false. |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | Lädt Eigenschaften aus der Eigenschaftstabelle von JT als Aspose.3D‑Eigenschaften. Der Standardwert ist false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab; die Suchpfade ermöglichen Aspose.3D, nach externen Dateien zum Laden zu suchen. (Vererbt von [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |

### Siehe auch

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)


