---
title: "IOConfig"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/ioconfig/
---
## IOConfig class

IO-configuratie voor serialisatie/deserialisatie.  Gebruiker kan gedetailleerde configuraties opgeven, zoals het pad voor afhankelijkheidsopzoeking, of hier formatgerelateerde configuraties @hideconstructor


## Methoden

### getFileSystemFactory{#getFileSystemFactory}

| Naam | Beschrijving |
| --- | --- |
| getFileSystemFactory() | Haalt op of stelt de fabriekklasse voor FileSystem in. De standaardfabriek maakt LocalFileSystem aan, wat niet geschikt is voor serveromgevingen. |

 **Result:**



---


### setFileSystemFactory{#setFileSystemFactory}

| Naam | Beschrijving |
| --- | --- |
| setFileSystemFactory(value) | Haalt op of stelt de fabriekklasse voor FileSystem in. De standaardfabriek maakt LocalFileSystem aan, wat niet geschikt is voor serveromgevingen. |

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



