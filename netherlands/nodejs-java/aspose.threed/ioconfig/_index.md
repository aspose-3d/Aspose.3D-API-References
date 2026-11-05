---
title: "IOConfig"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/ioconfig/
---
## IOConfig class

IO-configuratie voor serialisatie/deserialisatie.  Gebruiker kan gedetailleerde configuraties opgeven, zoals het pad voor afhankelijkheidsopzoeking of formatgerelateerde configuraties hier @hideconstructor


## Methoden

### getFileSystemFactory{#getFileSystemFactory}

| Naam | Beschrijving |
| --- | --- |
| getFileSystemFactory() | Haalt of stelt de fabrieksklasse voor FileSystem. De standaardfabriek maakt LocalFileSystem aan, die niet geschikt is voor een serveromgeving. |

 **Result:**



---


### setFileSystemFactory{#setFileSystemFactory}

| Naam | Beschrijving |
| --- | --- |
| setFileSystemFactory(value) | Haalt of stelt de fabrieksklasse voor FileSystem. De standaardfabriek maakt LocalFileSystem aan, die niet geschikt is voor een serveromgeving. |

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



