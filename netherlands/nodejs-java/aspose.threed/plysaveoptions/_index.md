---
title: "PlySaveOptions"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

Opslaanopties voor het exporteren van de scène als PLY-bestand.


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
| getFlipCoordinate() | Keer de coördinaat om tijdens het opslaan van de scène, standaardwaarde is true. |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| Naam | Beschrijving |
| --- | --- |
| setFlipCoordinate(value) | Keer de coördinaat om tijdens het opslaan van de scène, standaardwaarde is true. |

 **Result:**



---


### getVertexElement{#getVertexElement}

| Naam | Beschrijving |
| --- | --- |
| getVertexElement() | De elementnaam voor de vertex‑gegevens, standaardwaarde is "vertex". |

 **Result:**



---


### setVertexElement{#setVertexElement}

| Naam | Beschrijving |
| --- | --- |
| setVertexElement(value) | De elementnaam voor de vertex‑gegevens, standaardwaarde is "vertex". |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| Naam | Beschrijving |
| --- | --- |
| getPositionComponents() | De componentnamen voor positiedata, standaardwaarde is ("x", "y", "z"). |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| Naam | Beschrijving |
| --- | --- |
| getNormalComponents() | De componentnamen voor normaledata, standaardwaarde is ("nx", "ny", "nz"). |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| Naam | Beschrijving |
| --- | --- |
| getTextureCoordinateComponents() | De componentnamen voor textuurcoördinaatgegevens, standaardwaarde is ("u", "v") |

 **Result:**



---


### getColorComponents{#getColorComponents}

| Naam | Beschrijving |
| --- | --- |
| getColorComponents() | De componentnamen voor vertexkleur, standaardwaarde is ("rood", "groen", "blauw") |

 **Result:**



---


### getFaceElement{#getFaceElement}

| Naam | Beschrijving |
| --- | --- |
| getFaceElement() | De elementnaam voor de gezichtsgegevens, standaardwaarde is "face" |

 **Result:**



---


### setFaceElement{#setFaceElement}

| Naam | Beschrijving |
| --- | --- |
| setFaceElement(value) | De elementnaam voor de gezichtsgegevens, standaardwaarde is "face" |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| Naam | Beschrijving |
| --- | --- |
| getFaceProperty() | De eigenschapsnaam voor de gezichtsgegevens, standaardwaarde is "vertex_index" |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| Naam | Beschrijving |
| --- | --- |
| setFaceProperty(value) | De eigenschapsnaam voor de gezichtsgegevens, standaardwaarde is "vertex_index" |

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



