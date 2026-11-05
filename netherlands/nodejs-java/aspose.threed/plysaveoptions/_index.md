---
title: "PlySaveOptions"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

Opslaanopties voor het exporteren van een scène als PLY‑bestand.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Constructor van PlySaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(contentType) | Constructor van PlySaveOptions |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getPointCloud{#getPointCloud}

| Naam | Beschrijving |
| --- | --- |
| getPointCloud() | Exporteer de scène als point cloud, de standaardwaarde is false. |

 **Result:**



---


### setPointCloud{#setPointCloud}

| Naam | Beschrijving |
| --- | --- |
| setPointCloud(value) | Exporteer de scène als point cloud, de standaardwaarde is false. |

 **Result:**



---


### getFlipCoordinate{#getFlipCoordinate}

| Naam | Beschrijving |
| --- | --- |
| getFlipCoordinate() | Keer de coördinaat om tijdens het opslaan van de scène, standaardwaarde is true |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| Naam | Beschrijving |
| --- | --- |
| setFlipCoordinate(value) | Keer de coördinaat om tijdens het opslaan van de scène, standaardwaarde is true |

 **Result:**



---


### getVertexElement{#getVertexElement}

| Naam | Beschrijving |
| --- | --- |
| getVertexElement() | De elementnaam voor de vertex‑gegevens, standaardwaarde is "vertex" |

 **Result:**



---


### setVertexElement{#setVertexElement}

| Naam | Beschrijving |
| --- | --- |
| setVertexElement(value) | De elementnaam voor de vertex‑gegevens, standaardwaarde is "vertex" |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| Naam | Beschrijving |
| --- | --- |
| getPositionComponents() | De componentnamen voor positiedata, standaardwaarde is ("x", "y", "z") |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| Naam | Beschrijving |
| --- | --- |
| getNormalComponents() | De componentnamen voor normaaldata, standaardwaarde is ("nx", "ny", "nz") |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| Naam | Beschrijving |
| --- | --- |
| getTextureCoordinateComponents() | De componentnamen voor textuurcoördinaatdata, standaardwaarde is ("u", "v") |

 **Result:**



---


### getColorComponents{#getColorComponents}

| Naam | Beschrijving |
| --- | --- |
| getColorComponents() | De componentnamen voor vertexkleur, standaardwaarde is ("red", "green", "blue") |

 **Result:**



---


### getFaceElement{#getFaceElement}

| Naam | Beschrijving |
| --- | --- |
| getFaceElement() | De elementnaam voor de gezichtsdata, standaardwaarde is "face" |

 **Result:**



---


### setFaceElement{#setFaceElement}

| Naam | Beschrijving |
| --- | --- |
| setFaceElement(value) | De elementnaam voor de gezichtsdata, standaardwaarde is "face" |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| Naam | Beschrijving |
| --- | --- |
| getFaceProperty() | De eigenschapsnaam voor de gezichtsdata, standaardwaarde is "vertex_index" |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| Naam | Beschrijving |
| --- | --- |
| setFaceProperty(value) | De eigenschapsnaam voor de gezichtsdata, standaardwaarde is "vertex_index" |

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



