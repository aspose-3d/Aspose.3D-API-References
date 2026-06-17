---
title: "UsdSaveOptions"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

Opslaanopties voor USD/USDZ-formaten.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseer een nieuwe UsdSaveOptions met het FileFormat.USD-formaat |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(fileFormat) | Initialiseer een nieuwe UsdSaveOptions met het opgegeven USD/USDZ-formaat. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| Naam | Beschrijving |
| --- | --- |
| getPrimitiveToMesh() | Converteer de primitieve entiteiten naar een mesh tijdens het exporteren. Of codeer de primitieve direct naar het uitvoerbestand (maakt gebruik van Aspose's extensiedefinitie voor niet‑officiële primitieve zoals Dish, Torus). Standaardwaarde is true. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| Naam | Beschrijving |
| --- | --- |
| setPrimitiveToMesh(value) | Converteer de primitieve entiteiten naar een mesh tijdens het exporteren. Of codeer de primitieve direct naar het uitvoerbestand (maakt gebruik van Aspose's extensiedefinitie voor niet‑officiële primitieve zoals Dish, Torus). Standaardwaarde is true. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| Naam | Beschrijving |
| --- | --- |
| getExportMetaData() | Exporteer de eigenschappen van het knooppunt via het customData-veld van USD. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| Naam | Beschrijving |
| --- | --- |
| setExportMetaData(value) | Exporteer de eigenschappen van het knooppunt via het customData-veld van USD. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Naam | Beschrijving |
| --- | --- |
| getMaterialConverter() | Aangepaste converter om het materiaal van de geometrie te converteren naar PBR-materiaal. Als deze niet is toegewezen, zal de USD-exporter automatisch het standaardmateriaal omzetten naar PBR-materiaal. Standaardwaarde is null |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Naam | Beschrijving |
| --- | --- |
| setMaterialConverter(value) | Aangepaste converter om het materiaal van de geometrie te converteren naar PBR-materiaal. Als deze niet is toegewezen, zal de USD-exporter automatisch het standaardmateriaal omzetten naar PBR-materiaal. Standaardwaarde is null |

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



