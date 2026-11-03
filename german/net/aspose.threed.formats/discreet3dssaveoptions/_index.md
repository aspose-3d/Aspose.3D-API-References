---
title: "Klasse Discreet3dsSaveOptions"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.Discreet3dsSaveOptions Klasse. Speicheroptionen für 3DS-Dateien"
type: docs
weight: 1130
url: /de/net/aspose.threed.formats/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Speicheroptionen für 3DS-Datei.

```csharp
public class Discreet3dsSaveOptions : SaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Discreet3dsSaveOptions](discreet3dssaveoptions/)() | Konstruktor von `Discreet3dsSaveOptions` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DuplicatedNameCounterBase](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterbase/) { get; set; } | Der Zähler, der zum Erzeugen neuer Namen für duplizierte Namen verwendet wird, Standardwert ist 2. |
| [DuplicatedNameCounterFormat](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterformat/) { get; set; } | Das Format des duplizierten Zählers, Standardwert ist ein leerer String. |
| [DuplicatedNameSeparator](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednameseparator/) { get; set; } | Der Trenner zwischen dem Objektnamen und dem duplizierten Zähler, Standardwert ist "_". Wenn die Szene Objekte enthält, die denselben Namen verwenden, erzeugt der Aspose.3D 3DS-Exporter einen anderen Namen für das Objekt. Zum Beispiel gibt es zwei Knoten mit dem Namen "Box"; der erste Knoten hat den Namen "Box", und der zweite Knoten erhält mit der Standardkonfiguration den neuen Namen "Box_2". |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |
| [ExportCamera](../../aspose.threed.formats/discreet3dssaveoptions/exportcamera/) { get; set; } | Liest oder setzt, ob alle Kameras in der Szene exportiert werden. |
| [ExportLight](../../aspose.threed.formats/discreet3dssaveoptions/exportlight/) { get; set; } | Liest oder setzt, ob alle Lichter in der Szene exportiert werden. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Versucht, Texturen, die in der Szene verwendet werden, in das Ausgabeverzeichnis zu kopieren. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dssaveoptions/flipcoordinatesystem/) { get; set; } | Liest oder setzt das Umkehren des Koordinatensystems von Kontrollpunkten/Normale während des Importierens/Exportierens. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dssaveoptions/gammacorrectedcolor/) { get; set; } | Eine 3ds-Datei kann für dasselbe Attribut Originalfarbe und gamma‑korrigierte Farbe enthalten. Wenn dies auf true gesetzt wird, wird nach Möglichkeit die gamma‑korrigierte Farbe verwendet, andernfalls versucht Aspose.3D, die Originalfarbe zu verwenden. |
| [HighPreciseColor](../../aspose.threed.formats/discreet3dssaveoptions/highprecisecolor/) { get; set; } | Wenn dies true ist, verwendet die erzeugte 3ds-Datei hochpräzise Farben, d.h. jeder Rot‑/Grün‑/Blau‑Kanal ist ein 32‑Bit‑Float. Andernfalls verwendet die erzeugte Datei 24‑Bit‑Farben, wobei jeder Kanal ein 8‑Bit‑Byte ist. Der Standardwert ist false, weil nicht alle Anwendungen hochpräzise Farben unterstützen. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |
| [MasterScale](../../aspose.threed.formats/discreet3dssaveoptions/masterscale/) { get; set; } | Liest oder setzt den beim Export verwendeten Master‑Skalierungsfaktor. |

### Siehe auch

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


