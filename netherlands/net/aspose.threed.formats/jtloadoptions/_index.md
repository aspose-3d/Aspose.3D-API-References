---
title: "Klasse JtLoadOptions"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Aspose.ThreeD.Formats.JtLoadOptions klasse. Laadopties voor Siemens JT"
type: docs
weight: 1310
url: /nl/net/aspose.threed.formats/jtloadoptions/
---
## JtLoadOptions class

Laadopties voor Siemens JT

```csharp
public class JtLoadOptions : LoadOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Haalt op of stelt de standaardcodering in voor tekstgebaseerde bestanden. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Haalt het bestandsformaat op dat is gespecificeerd in de huidige Opslaan/Laden-optie. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | De bestandsnaam van de exporterende/importerende scène. Dit is optioneel, maar nuttig bij het serialiseren van externe assets zoals het materiaal van OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [LoadPMI](../../aspose.threed.formats/jtloadoptions/loadpmi/) { get; set; } | Laad PMI-informatie uit het JT-bestand indien mogelijk; de gegevens worden opgeslagen als eigenschap "PMI" van [`AssetInfo`](../../aspose.threed/scene/assetinfo/). Standaardwaarde is false. |
| [LoadProperties](../../aspose.threed.formats/jtloadoptions/loadproperties/) { get; set; } | Laad eigenschappen uit de eigentabel van JT als Aspose.3D-eigenschappen. Standaardwaarde is false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Sommige bestanden, zoals OBJ, zijn afhankelijk van een extern bestand; de zoekpaden stellen Aspose.3D in staat om naar het externe bestand te zoeken om te laden. |

### Zie ook

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


