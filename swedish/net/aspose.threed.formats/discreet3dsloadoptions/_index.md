---
title: Discreet3dsLoadOptions
second_title: Aspose.3D för .NET API-referens
description: Ladda alternativ för 3DSfil.
type: docs
weight: 1060
url: /sv/net/aspose.threed.formats/discreet3dsloadoptions/
---
## Discreet3dsLoadOptions class

Ladda alternativ för 3DS-fil.

```csharp
public class Discreet3dsLoadOptions : LoadOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Discreet3dsLoadOptions](discreet3dsloadoptions)() | Konstruktör av[`Discreet3dsLoadOptions`](../discreet3dsloadoptions) |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ApplyAnimationTransform](../../aspose.threed.formats/discreet3dsloadoptions/applyanimationtransform) { get; set; } | Hämtar eller ställer in om transformationen som definieras i den första bilden av animationsspåret ska användas. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Hämtar eller ställer in standardkodningen för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören kommer att bestämma vilken kodning som ska användas. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Hämtar filformatet som anges i det aktuella alternativet Spara/Ladda. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | Filnamnet på den exporterande/importerande scenen. Detta är valfritt, men användbart när man serialiserar externa tillgångar som OBJ:s material. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Tillåt användaren att hantera hur de externa beroenden ska hanteras under laddning/spara. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dsloadoptions/flipcoordinatesystem) { get; set; } | Hämtar eller ställer in flip-koordinatsystem för kontrollpunkter/normalt under import/export. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dsloadoptions/gammacorrectedcolor) { get; set; } | En 3ds-fil kan innehålla originalfärg och gammakorrigerad färg för samma attribut, Om du ställer in detta på sant kommer den gammakorrigerade färgen att användas om möjligt, annars kommer Aspose.3D att försöka använda den ursprungliga färgen. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | Vissa filer som OBJ beror på extern fil, sökvägarna gör det möjligt för Aspose.3D att leta efter extern fil att ladda. |

### Se även

* class [LoadOptions](../loadoptions)
* namnutrymme [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->