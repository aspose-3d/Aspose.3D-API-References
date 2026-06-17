---
title: "RvmSaveOptions"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Opslaanopties voor Aveva PDMS RVM‑bestand.


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
| getAttributePrefix() | Haalt op of stelt het voorvoegsel in van de attributen die geëxporteerd zullen worden, de geëxporteerde eigenschap zal geen voorvoegsel bevatten, aangepaste eigenschappen met een ander voorvoegsel worden niet geëxporteerd, standaardwaarde is 'rvm:'. Bijvoorbeeld als een eigenschap rvm:Refno=345 is, zal het geëxporteerde attribuut Refno = 345 zijn, het voorvoegsel wordt verwijderd. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Naam | Beschrijving |
| --- | --- |
| setAttributePrefix(value) | Haalt op of stelt het voorvoegsel in van de attributen die geëxporteerd zullen worden, de geëxporteerde eigenschap zal geen voorvoegsel bevatten, aangepaste eigenschappen met een ander voorvoegsel worden niet geëxporteerd, standaardwaarde is 'rvm:'. Bijvoorbeeld als een eigenschap rvm:Refno=345 is, zal het geëxporteerde attribuut Refno = 345 zijn, het voorvoegsel wordt verwijderd. |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| Naam | Beschrijving |
| --- | --- |
| getAttributeListFile() | Haalt of stelt de bestandsnaam van het attribuutlijstbestand in, de exporter genereert een naam op basis van de .rvm-bestandsnaam wanneer deze eigenschap niet is gedefinieerd, standaardwaarde is null. |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| Naam | Beschrijving |
| --- | --- |
| setAttributeListFile(value) | Haalt of stelt de bestandsnaam van het attribuutlijstbestand in, de exporter genereert een naam op basis van de .rvm-bestandsnaam wanneer deze eigenschap niet is gedefinieerd, standaardwaarde is null. |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| Naam | Beschrijving |
| --- | --- |
| getExportAttributes() | Haalt of stelt in of de attribuutlijst moet worden geëxporteerd naar een extern .att-bestand, standaardwaarde is false. |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| Naam | Beschrijving |
| --- | --- |
| setExportAttributes(value) | Haalt of stelt in of de attribuutlijst moet worden geëxporteerd naar een extern .att-bestand, standaardwaarde is false. |

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
| getFileFormat() | Geeft het bestandsformaat terug dat is opgegeven in de huidige opslaan/laden-optie. |

 **Result:**



---


### getEncoding{#getEncoding}

| Naam | Beschrijving |
| --- | --- |
| getEncoding() | Geeft de standaardcodering voor tekstbestanden terug of stelt deze in. Standaardwaarde is null, wat betekent dat de importeur/exporteur bepaalt welke codering te gebruiken. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Naam | Beschrijving |
| --- | --- |
| getFileSystem() | Staat de gebruiker toe te bepalen hoe externe afhankelijkheden tijdens laden/opslaan worden beheerd. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Naam | Beschrijving |
| --- | --- |
| setFileSystem(value) | Staat de gebruiker toe te bepalen hoe externe afhankelijkheden tijdens laden/opslaan worden beheerd. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Naam | Beschrijving |
| --- | --- |
| getLookupPaths() | Sommige bestanden, zoals OBJ, zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te vinden voor het laden. |

 **Result:**



---


### getFileName{#getFileName}

| Naam | Beschrijving |
| --- | --- |
| getFileName() | De bestandsnaam van de te exporteren/importeren scène. Dit is optioneel, maar handig bij het serialiseren van externe assets zoals het materiaal van OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Naam | Beschrijving |
| --- | --- |
| setFileName(value) | De bestandsnaam van de te exporteren/importeren scène. Dit is optioneel, maar handig bij het serialiseren van externe assets zoals het materiaal van OBJ. |

 **Result:**



---



