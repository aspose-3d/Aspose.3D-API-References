---
title: "Klass JtLoadOptions"
second_title: "Aspose.3D för .NET API‑referens"
description: "Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions‑klass. Laddningsalternativ för Siemens JT"
type: docs
weight: 1380
url: /sv/net/aspose.threed.formats.siemensjt/jtloadoptions/
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
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Hämtar eller anger standardkodningen för textbaserade filer. Standardvärdet är null, vilket betyder att importören/exportören bestämmer vilken kodning som ska användas.(Ärvd från [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Hämtar filformatet som anges i aktuellt Spara/Ladda‑alternativ.(Ärvd från [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Filnamnet för den exporterande/importerande scenen. Detta är valfritt, men användbart när man serialiserar externa tillgångar som OBJ:s material.(Ärvd från [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Tillåt användaren att hantera hur externa beroenden ska hanteras under laddning/sparning.(Ärvd från [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | Läs in PMI‑information från JT‑filen om möjligt, data kommer att sparas som egenskapen "PMI" i [`AssetInfo`](../../aspose.threed/scene/assetinfo/). Standardvärdet är falskt. |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | Läs in egenskaper från JTs egenskapstabell som Aspose.3D‑egenskaper. Standardvärdet är falskt. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Vissa filer, som OBJ, är beroende av externa filer; sökvägarna gör att Aspose.3D kan leta efter externa filer att läsa in.(Ärvd från [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |

### Se även

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)


