---
title: "Klass JtLoadOptions"
second_title: "Aspose.3D för .NET API‑referens"
description: "Aspose.ThreeD.Formats.JtLoadOptions-klass. Laddningsalternativ för Siemens JT"
type: docs
weight: 1310
url: /sv/net/aspose.threed.formats/jtloadoptions/
---
## JtLoadOptions class

Laddningsalternativ för Siemens JT

```csharp
public class JtLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Hämtar eller anger standardkodning för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören bestämmer vilken kodning som ska användas. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Hämtar filformatet som anges i aktuellt Spara/Ladda-alternativ. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Filnamnet för den exporterande/importerande scenen. Detta är valfritt, men användbart när man serialiserar externa resurser som OBJ:s material. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Tillåt användaren att hantera hur externa beroenden ska hanteras under laddning/lagring. |
| [LoadPMI](../../aspose.threed.formats/jtloadoptions/loadpmi/) { get; set; } | Läs in PMI‑information från JT‑filen om möjligt, data kommer att sparas som egenskapen "PMI" i [`AssetInfo`](../../aspose.threed/scene/assetinfo/). Standardvärdet är falskt. |
| [LoadProperties](../../aspose.threed.formats/jtloadoptions/loadproperties/) { get; set; } | Läs in egenskaper från JTs egenskapstabell som Aspose.3D‑egenskaper. Standardvärdet är falskt. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. |

### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


