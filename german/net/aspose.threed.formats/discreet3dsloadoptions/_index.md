---
title: "Klasse Discreet3dsLoadOptions"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.Discreet3dsLoadOptions Klasse. Ladeoptionen für 3DS‑Dateien"
type: docs
weight: 1120
url: /de/net/aspose.threed.formats/discreet3dsloadoptions/
---
## Discreet3dsLoadOptions class

Ladeoptionen für 3DS-Datei.

```csharp
public class Discreet3dsLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Discreet3dsLoadOptions](discreet3dsloadoptions/)() | Konstruktor von `Discreet3dsLoadOptions` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ApplyAnimationTransform](../../aspose.threed.formats/discreet3dsloadoptions/applyanimationtransform/) { get; set; } | Liest oder setzt, ob die im ersten Frame der Animationsspur definierte Transformation verwendet werden soll. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dsloadoptions/flipcoordinatesystem/) { get; set; } | Liest oder setzt das Umkehren des Koordinatensystems von Kontrollpunkten/Normale während des Importierens/Exportierens. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dsloadoptions/gammacorrectedcolor/) { get; set; } | Eine 3ds-Datei kann für dasselbe Attribut Originalfarbe und gamma‑korrigierte Farbe enthalten. Wenn dies auf true gesetzt wird, wird nach Möglichkeit die gamma‑korrigierte Farbe verwendet, andernfalls versucht Aspose.3D, die Originalfarbe zu verwenden. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |

### Siehe auch

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


