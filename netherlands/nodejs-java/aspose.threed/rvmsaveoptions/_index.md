---
title: "RvmSaveOptions"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Opslagopties voor Aveva PDMS RVM‑bestand.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Constructor van RvmSaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(contentType) | Constructor van RvmSaveOptions |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| Naam | Beschrijving |
| --- | --- |
| getFileNote() | Bestandsnotitie in de bestandsheader. |

 **Result:**



---


### setFileNote{#setFileNote}

| Naam | Beschrijving |
| --- | --- |
| setFileNote(value) | Bestandsnotitie in de bestandsheader. |

 **Result:**



---


### getAuthor{#getAuthor}

| Naam | Beschrijving |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| Naam | Beschrijving |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| Naam | Beschrijving |
| --- | --- |
| getCreationTime() | De tijdstempel die dit bestand heeft geëxporteerd, standaardwaarde is de huidige tijd |

 **Result:**



---


### setCreationTime{#setCreationTime}

| Naam | Beschrijving |
| --- | --- |
| setCreationTime(value) | De tijdstempel die dit bestand heeft geëxporteerd, standaardwaarde is de huidige tijd |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Naam | Beschrijving |
| --- | --- |
| getAttributePrefix() | Haalt op of stelt het voorvoegsel in van de attributen die geëxporteerd zullen worden, de geëxporteerde eigenschap bevat geen voorvoegsel, aangepaste eigenschappen met een ander voorvoegsel worden niet geëxporteerd, standaardwaarde is 'rvm:'. Bijvoorbeeld als een eigenschap rvm:Refno=345 is, wordt het geëxporteerde attribuut Refno = 345, het voorvoegsel wordt verwijderd. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Naam | Beschrijving |
| --- | --- |
| setAttributePrefix(value) | Haalt op of stelt het voorvoegsel in van de attributen die geëxporteerd zullen worden, de geëxporteerde eigenschap bevat geen voorvoegsel, aangepaste eigenschappen met een ander voorvoegsel worden niet geëxporteerd, standaardwaarde is 'rvm:'. Bijvoorbeeld als een eigenschap rvm:Refno=345 is, wordt het geëxporteerde attribuut Refno = 345, het voorvoegsel wordt verwijderd. |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| Naam | Beschrijving |
| --- | --- |
| getAttributeListFile() | Haalt op of stelt de bestandsnaam van het attribuutlijstbestand in, de exporter genereert een naam op basis van de .rvm-bestandsnaam wanneer deze eigenschap niet is gedefinieerd, standaardwaarde is null. |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| Naam | Beschrijving |
| --- | --- |
| setAttributeListFile(value) | Haalt op of stelt de bestandsnaam van het attribuutlijstbestand in, de exporter genereert een naam op basis van de .rvm-bestandsnaam wanneer deze eigenschap niet is gedefinieerd, standaardwaarde is null. |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| Naam | Beschrijving |
| --- | --- |
| getExportAttributes() | Haalt op of stelt in of de attribuutlijst moet worden geëxporteerd naar een extern .att-bestand, standaardwaarde is false. |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| Naam | Beschrijving |
| --- | --- |
| setExportAttributes(value) | Haalt op of stelt in of de attribuutlijst moet worden geëxporteerd naar een extern .att-bestand, standaardwaarde is false. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Naam | Beschrijving |
| --- | --- |
| getExportTextures() | Probeer de in de scène gebruikte textures te kopiëren naar de uitvoermap. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Naam | Beschrijving |
| --- | --- |
| setExportTextures(value) | Probeer de in de scène gebruikte textures te kopiëren naar de uitvoermap. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Naam | Beschrijving |
| --- | --- |
| getFileFormat() | Haalt het bestandsformaat op dat is gespecificeerd in de huidige Opslaan/Laden-optie. |

 **Result:**



---


### getEncoding{#getEncoding}

| Naam | Beschrijving |
| --- | --- |
| getEncoding() | Haalt op of stelt de standaardcodering voor tekstgebaseerde bestanden in. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Naam | Beschrijving |
| --- | --- |
| getFileSystem() | Sta de gebruiker toe om te bepalen hoe externe afhankelijkheden te beheren tijdens laden/opslaan. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Naam | Beschrijving |
| --- | --- |
| setFileSystem(value) | Sta de gebruiker toe om te bepalen hoe externe afhankelijkheden te beheren tijdens laden/opslaan. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Naam | Beschrijving |
| --- | --- |
| getLookupPaths() | Sommige bestanden, zoals OBJ, zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. |

 **Result:**



---


### getFileName{#getFileName}

| Naam | Beschrijving |
| --- | --- |
| getFileName() | De bestandsnaam van de exporterende/importerende scène. Dit is optioneel, maar nuttig bij het serialiseren van externe assets zoals het materiaal van OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Naam | Beschrijving |
| --- | --- |
| setFileName(value) | De bestandsnaam van de exporterende/importerende scène. Dit is optioneel, maar nuttig bij het serialiseren van externe assets zoals het materiaal van OBJ. |

 **Result:**



---



