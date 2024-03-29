---
title: StlLoadOptions
second_title: Aspose.3D för .NET API-referens
description: Ladda alternativ för STL
type: docs
weight: 1350
url: /sv/net/aspose.threed.formats/stlloadoptions/
---
## StlLoadOptions class

Ladda alternativ för STL

```csharp
public class StlLoadOptions : LoadOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [StlLoadOptions](stlloadoptions#constructor)() | Initierar en ny[`StlLoadOptions`](../stlloadoptions) instans. |
| [StlLoadOptions](stlloadoptions#constructor_1)(FileContentType) | Initierar en ny[`StlLoadOptions`](../stlloadoptions) instans. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Hämtar eller ställer in standardkodningen för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören kommer att bestämma vilken kodning som ska användas. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Hämtar filformatet som anges i det aktuella alternativet Spara/Ladda. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | Filnamnet på den exporterande/importerande scenen. Detta är valfritt, men användbart när man serialiserar externa tillgångar som OBJ:s material. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Tillåt användaren att hantera hur de externa beroenden ska hanteras under laddning/spara. |
| [FlipCoordinateSystem](../../aspose.threed.formats/stlloadoptions/flipcoordinatesystem) { get; set; } | Hämtar eller ställer in om koordinatsystemet för kontrollpunkter/normalt ska vändas under import. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | Vissa filer som OBJ beror på extern fil, sökvägarna gör det möjligt för Aspose.3D att leta efter extern fil att ladda. |
| [RecalculateNormal](../../aspose.threed.formats/stlloadoptions/recalculatenormal) { get; set; } | Ignorera normala data som lagras i STL-filen och beräkna om normala data baserat på vertexpositionen. Standardvärdet är false |

### Se även

* class [LoadOptions](../loadoptions)
* namnutrymme [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
