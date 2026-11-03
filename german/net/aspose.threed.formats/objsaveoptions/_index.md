---
title: "Klasse ObjSaveOptions"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.ObjSaveOptions Klasse. Speicheroptionen für Wavefront‑OBJ‑Dateien"
type: docs
weight: 1370
url: /de/net/aspose.threed.formats/objsaveoptions/
---
## ObjSaveOptions class

Speicheroptionen für Wavefront OBJ-Datei

```csharp
public class ObjSaveOptions : SaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ObjSaveOptions](objsaveoptions/)() | Konstruktor von `ObjSaveOptions` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/objsaveoptions/applyunitscale/) { get; set; } | Wende [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) auf das Mesh an. Standardwert ist false. |
| [AxisSystem](../../aspose.threed.formats/objsaveoptions/axissystem/) { get; set; } | Liest oder setzt das Achsensystem in der exportierten Datei. |
| [EnableMaterials](../../aspose.threed.formats/objsaveoptions/enablematerials/) { get; set; } | Liest oder setzt, ob Materialien für jedes Objekt importiert/exportiert werden |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Versucht, Texturen, die in der Szene verwendet werden, in das Ausgabeverzeichnis zu kopieren. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden. |
| [FlipCoordinateSystem](../../aspose.threed.formats/objsaveoptions/flipcoordinatesystem/) { get; set; } | Gibt an, ob das Koordinatensystem von Kontrollpunkten/Normale beim Import/Export umgekehrt wird, oder legt es fest. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |
| [PointCloud](../../aspose.threed.formats/objsaveoptions/pointcloud/) { get; set; } | Liest oder setzt das Flag, ob der Exporter die Szene als Punktwolke (ohne topologische Struktur) exportieren soll, Standardwert ist false |
| [SerializeW](../../aspose.threed.formats/objsaveoptions/serializew/) { get; set; } | Liest oder setzt, ob die W‑Komponente in den Vertex‑Positionen des Modells serialisiert wird. |
| [Verbose](../../aspose.threed.formats/objsaveoptions/verbose/) { get; set; } | Liest oder setzt, ob für jeden Abschnitt Kommentare generiert werden |

### Siehe auch

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


