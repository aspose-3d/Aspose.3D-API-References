---
title: "PlySaveOptions"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

Sparaalternativ för att exportera scen som PLY-fil.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Konstruktor för PlySaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(contentType) | Konstruktor för PlySaveOptions |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getPointCloud{#getPointCloud}

| Namn | Beskrivning |
| --- | --- |
| getPointCloud() | Exportera scenen som punktmoln, standardvärdet är false. |

 **Result:**



---


### setPointCloud{#setPointCloud}

| Namn | Beskrivning |
| --- | --- |
| setPointCloud(value) | Exportera scenen som punktmoln, standardvärdet är false. |

 **Result:**



---


### getFlipCoordinate{#getFlipCoordinate}

| Namn | Beskrivning |
| --- | --- |
| getFlipCoordinate() | Vänd koordinaten vid sparande av scenen, standardvärdet är true |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| Namn | Beskrivning |
| --- | --- |
| setFlipCoordinate(value) | Vänd koordinaten vid sparande av scenen, standardvärdet är true |

 **Result:**



---


### getVertexElement{#getVertexElement}

| Namn | Beskrivning |
| --- | --- |
| getVertexElement() | Elementnamnet för vertex‑data, standardvärdet är "vertex" |

 **Result:**



---


### setVertexElement{#setVertexElement}

| Namn | Beskrivning |
| --- | --- |
| setVertexElement(value) | Elementnamnet för vertex‑data, standardvärdet är "vertex" |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| Namn | Beskrivning |
| --- | --- |
| getPositionComponents() | Komponentnamnen för positionsdata, standardvärdet är ("x", "y", "z") |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| Namn | Beskrivning |
| --- | --- |
| getNormalComponents() | Komponentnamnen för normaldata, standardvärdet är ("nx", "ny", "nz") |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| Namn | Beskrivning |
| --- | --- |
| getTextureCoordinateComponents() | Komponentnamnen för texturkoordinatdata, standardvärdet är ("u", "v") |

 **Result:**



---


### getColorComponents{#getColorComponents}

| Namn | Beskrivning |
| --- | --- |
| getColorComponents() | Komponentnamnen för vertexfärg, standardvärdet är ("red", "green", "blue") |

 **Result:**



---


### getFaceElement{#getFaceElement}

| Namn | Beskrivning |
| --- | --- |
| getFaceElement() | Elementnamnet för ansiktsdata, standardvärdet är "face" |

 **Result:**



---


### setFaceElement{#setFaceElement}

| Namn | Beskrivning |
| --- | --- |
| setFaceElement(value) | Elementnamnet för ansiktsdata, standardvärdet är "face" |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| Namn | Beskrivning |
| --- | --- |
| getFaceProperty() | Egenskapsnamnet för ansiktsdata, standardvärdet är "vertex_index" |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| Namn | Beskrivning |
| --- | --- |
| setFaceProperty(value) | Egenskapsnamnet för ansiktsdata, standardvärdet är "vertex_index" |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Namn | Beskrivning |
| --- | --- |
| getExportTextures() | Försök att kopiera texturer som används i scenen till utdatamappen. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Namn | Beskrivning |
| --- | --- |
| setExportTextures(value) | Försök att kopiera texturer som används i scenen till utdatamappen. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Namn | Beskrivning |
| --- | --- |
| getFileFormat() | Hämtar filformatet som anges i aktuellt Spara/Ladda-alternativ. |

 **Result:**



---


### getEncoding{#getEncoding}

| Namn | Beskrivning |
| --- | --- |
| getEncoding() | Hämtar eller anger standardkodning för textbaserade filer. Standardvärdet är null, vilket betyder att importören/exportören bestämmer vilken kodning som ska användas. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Namn | Beskrivning |
| --- | --- |
| getFileSystem() | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Namn | Beskrivning |
| --- | --- |
| setFileSystem(value) | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Namn | Beskrivning |
| --- | --- |
| getLookupPaths() | Vissa filer, som OBJ, är beroende av externa filer; sökvägarna gör det möjligt för Aspose.3D att leta efter externa filer att ladda. |

 **Result:**



---


### getFileName{#getFileName}

| Namn | Beskrivning |
| --- | --- |
| getFileName() | Filnamnet för den exporterade/importerade scenen. Detta är valfritt, men användbart när externa resurser som OBJ:s material serialiseras. |

 **Result:**



---


### setFileName{#setFileName}

| Namn | Beskrivning |
| --- | --- |
| setFileName(value) | Filnamnet för den exporterade/importerade scenen. Detta är valfritt, men användbart när externa resurser som OBJ:s material serialiseras. |

 **Result:**



---



