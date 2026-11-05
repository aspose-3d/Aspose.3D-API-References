---
title: "Klass Microsoft3MFSaveOptions"
second_title: "Aspose.3D för .NET API‑referens"
description: "Aspose.ThreeD.Formats.Microsoft3MFSaveOptions-klass. Spara alternativ för Microsoft 3MF-fil"
type: docs
weight: 1350
url: /sv/net/aspose.threed.formats/microsoft3mfsaveoptions/
---
## Microsoft3MFSaveOptions class

Spara alternativ för Microsoft 3MF-fil.

```csharp
public class Microsoft3MFSaveOptions : SaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Microsoft3MFSaveOptions](microsoft3mfsaveoptions/)() | Skapa en `Microsoft3MFSaveOptions` |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BuildAll](../../aspose.threed.formats/microsoft3mfsaveoptions/buildall/) { get; set; } | Markera alla geometrier i scenen som utskrivbara. Eller så kan du manuellt markera en nod som utskrivbar med [`SetBuildable`](../microsoft3mfformat/setbuildable/) Standardvärdet är true |
| [EnableCompression](../../aspose.threed.formats/microsoft3mfsaveoptions/enablecompression/) { get; set; } | Aktivera komprimering på den utgående 3mf-filen Standardvärdet är true |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Hämtar eller anger standardkodning för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören bestämmer vilken kodning som ska användas. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Försök att kopiera texturer som används i scenen till utdata katalogen. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Hämtar filformatet som anges i aktuellt Spara/Ladda-alternativ. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Filnamnet för den exporterande/importerande scenen. Detta är valfritt, men användbart när man serialiserar externa resurser som OBJ:s material. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Tillåt användaren att hantera hur externa beroenden ska hanteras under laddning/lagring. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. |

### Se även

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


