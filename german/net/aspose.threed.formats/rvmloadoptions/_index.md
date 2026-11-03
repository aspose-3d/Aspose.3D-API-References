---
title: "Klasse RvmLoadOptions"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.RvmLoadOptions Klasse. Ladeoptionen für AVEVA Plant Design Management Systems RVM-Datei"
type: docs
weight: 1470
url: /de/net/aspose.threed.formats/rvmloadoptions/
---
## RvmLoadOptions class

Ladeoptionen für die RVM-Datei des AVEVA Plant Design Management Systems.

```csharp
public class RvmLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RvmLoadOptions](rvmloadoptions/#constructor)() | Erstelle eine `RvmLoadOptions`-Instanz |
| [RvmLoadOptions](rvmloadoptions/#constructor_1)(FileContentType) | Erstelle eine `RvmLoadOptions`-Instanz |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AttributePrefix](../../aspose.threed.formats/rvmloadoptions/attributeprefix/) { get; set; } | Liest oder setzt das Präfix der Attribute, die in externen Attributdateien definiert wurden. Das Präfix wird verwendet, um Namenskonflikte zu vermeiden, Standardwert ist "rvm:" |
| [CenterScene](../../aspose.threed.formats/rvmloadoptions/centerscene/) { get; set; } | Zentriere die Szene, nachdem sie geladen wurde. |
| [CylinderRadialSegments](../../aspose.threed.formats/rvmloadoptions/cylinderradialsegments/) { get; set; } | Liest oder setzt die Anzahl der radialen Segmente des Zylinders, Standardwert ist 16 |
| [DishLatitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlatitudesegments/) { get; set; } | Liest oder setzt die Anzahl der Breitengradsegmente der Schüssel, Standardwert ist 8 |
| [DishLongitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlongitudesegments/) { get; set; } | Liest oder setzt die Anzahl der Längengradsegmente der Schüssel, Standardwert ist 12 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden. |
| [GenerateMaterials](../../aspose.threed.formats/rvmloadoptions/generatematerials/) { get; set; } | Erzeugt Materialien mit zufälligen Farben für jedes Objekt in der Szene, wenn die Farbpalette nicht im RVM-File exportiert wird. Standardwert ist true |
| [LookupAttributes](../../aspose.threed.formats/rvmloadoptions/lookupattributes/) { get; set; } | Liest oder setzt, ob Attribute aus einer externen Attributlistendatei (.att/.attrib/.txt) geladen werden sollen, Standardwert ist true. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |
| [RectangularTorusSegments](../../aspose.threed.formats/rvmloadoptions/rectangulartorussegments/) { get; set; } | Liest oder setzt die Anzahl der radialen Segmente des rechteckigen Torus, Standardwert ist 20 |
| [TorusTubularSegments](../../aspose.threed.formats/rvmloadoptions/torustubularsegments/) { get; set; } | Liest oder setzt die Anzahl der röhrenförmigen Segmente des Torus, Standardwert ist 20 |

## Beispiele

Der folgende Code zeigt, wie man die Tessellationsparameter für primitive Geometrien, die aus einer RVM-Datei mit RvmLoadOptions importiert wurden, anpasst.

```csharp
RvmLoadOptions opt = new RvmLoadOptions();
opt.RectangularTorusSegments = 30;
opt.CylinderRadialSegments = 20;
opt.DishLatitudeSegments = 20;
opt.DishLongitudeSegments = 20;
opt.CenterScene = true;
var scene = Scene.FromFile("input.rvm", opt);
scene.Save("output.obj");
```

### Siehe auch

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


