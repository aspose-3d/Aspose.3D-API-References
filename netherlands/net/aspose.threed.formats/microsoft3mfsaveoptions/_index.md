---
title: "Klasse Microsoft3MFSaveOptions"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Aspose.ThreeD.Formats.Microsoft3MFSaveOptions class. Opslagopties voor Microsoft 3MF-bestand"
type: docs
weight: 1350
url: /nl/net/aspose.threed.formats/microsoft3mfsaveoptions/
---
## Microsoft3MFSaveOptions class

Opslagopties voor Microsoft 3MF-bestand.

```csharp
public class Microsoft3MFSaveOptions : SaveOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Microsoft3MFSaveOptions](microsoft3mfsaveoptions/)() | Construeer een `Microsoft3MFSaveOptions` |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BuildAll](../../aspose.threed.formats/microsoft3mfsaveoptions/buildall/) { get; set; } | Markeer alle geometrieën in de scène als afdrukbaar. Of u kunt handmatig een knooppunt markeren als afdrukbaar via [`SetBuildable`](../microsoft3mfformat/setbuildable/). Standaardwaarde is true |
| [EnableCompression](../../aspose.threed.formats/microsoft3mfsaveoptions/enablecompression/) { get; set; } | Schakel compressie in op het uitvoer-3mf-bestand. Standaardwaarde is true |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Haalt op of stelt de standaardcodering in voor tekstgebaseerde bestanden. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Probeer texturen die in de scène worden gebruikt te kopiëren naar de uitvoermap. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Haalt het bestandsformaat op dat is gespecificeerd in de huidige Opslaan/Laden-optie. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | De bestandsnaam van de exporterende/importerende scène. Dit is optioneel, maar nuttig bij het serialiseren van externe assets zoals het materiaal van OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Sommige bestanden, zoals OBJ, zijn afhankelijk van een extern bestand; de zoekpaden stellen Aspose.3D in staat om naar het externe bestand te zoeken om te laden. |

### Zie ook

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


