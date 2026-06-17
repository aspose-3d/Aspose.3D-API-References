---
title: "RvmLoadOptions"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/rvmloadoptions/
---
## RvmLoadOptions class

Läsalternativ för AVEVA Plant Design Management Systems RVM-fil.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(contentType) | Skapa en RvmLoadOptions-instans |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload() | Skapa en RvmLoadOptions-instans |

 **Result:**



---


### getGenerateMaterials{#getGenerateMaterials}

| Namn | Beskrivning |
| --- | --- |
| getGenerateMaterials() | Generera material med slumpmässiga färger för varje objekt i scenen om färgtabellen inte exporteras i RVM-filen. Standardvärdet är true |

 **Result:**



---


### setGenerateMaterials{#setGenerateMaterials}

| Namn | Beskrivning |
| --- | --- |
| setGenerateMaterials(value) | Generera material med slumpmässiga färger för varje objekt i scenen om färgtabellen inte exporteras i RVM-filen. Standardvärdet är true |

 **Result:**



---


### getCylinderRadialSegments{#getCylinderRadialSegments}

| Namn | Beskrivning |
| --- | --- |
| getCylinderRadialSegments() | Hämtar eller anger antalet radiala segment i cylindern, standardvärdet är 16 |

 **Result:**



---


### setCylinderRadialSegments{#setCylinderRadialSegments}

| Namn | Beskrivning |
| --- | --- |
| setCylinderRadialSegments(value) | Hämtar eller anger antalet radiala segment i cylindern, standardvärdet är 16 |

 **Result:**



---


### getDishLongitudeSegments{#getDishLongitudeSegments}

| Namn | Beskrivning |
| --- | --- |
| getDishLongitudeSegments() | Hämtar eller anger antalet longitudsegment för tallriken, standardvärdet är 12 |

 **Result:**



---


### setDishLongitudeSegments{#setDishLongitudeSegments}

| Namn | Beskrivning |
| --- | --- |
| setDishLongitudeSegments(value) | Hämtar eller anger antalet longitudsegment för tallriken, standardvärdet är 12 |

 **Result:**



---


### getDishLatitudeSegments{#getDishLatitudeSegments}

| Namn | Beskrivning |
| --- | --- |
| getDishLatitudeSegments() | Hämtar eller anger antalet latitudsegment för tallriken, standardvärdet är 8 |

 **Result:**



---


### setDishLatitudeSegments{#setDishLatitudeSegments}

| Namn | Beskrivning |
| --- | --- |
| setDishLatitudeSegments(value) | Hämtar eller anger antalet latitudsegment för tallriken, standardvärdet är 8 |

 **Result:**



---


### getTorusTubularSegments{#getTorusTubularSegments}

| Namn | Beskrivning |
| --- | --- |
| getTorusTubularSegments() | Hämtar eller anger antalet rörsegment för torusen, standardvärdet är 20 |

 **Result:**



---


### setTorusTubularSegments{#setTorusTubularSegments}

| Namn | Beskrivning |
| --- | --- |
| setTorusTubularSegments(value) | Hämtar eller anger antalet rörsegment för torusen, standardvärdet är 20 |

 **Result:**



---


### getRectangularTorusSegments{#getRectangularTorusSegments}

| Namn | Beskrivning |
| --- | --- |
| getRectangularTorusSegments() | Hämtar eller anger antalet radiala segment för den rektangulära torusen, standardvärdet är 20 |

 **Result:**



---


### setRectangularTorusSegments{#setRectangularTorusSegments}

| Namn | Beskrivning |
| --- | --- |
| setRectangularTorusSegments(value) | Hämtar eller anger antalet radiala segment för den rektangulära torusen, standardvärdet är 20 |

 **Result:**



---


### getCenterScene{#getCenterScene}

| Namn | Beskrivning |
| --- | --- |
| getCenterScene() | Centrera scenen efter att den har laddats. |

 **Result:**



---


### setCenterScene{#setCenterScene}

| Namn | Beskrivning |
| --- | --- |
| setCenterScene(value) | Centrera scenen efter att den har laddats. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Namn | Beskrivning |
| --- | --- |
| getAttributePrefix() | Hämtar eller anger prefixet för attributen som definierades i externa attributfiler. Prefixet används för att undvika namnkonflikter, standardvärdet är "rvm:" |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Namn | Beskrivning |
| --- | --- |
| setAttributePrefix(value) | Hämtar eller anger prefixet för attributen som definierades i externa attributfiler. Prefixet används för att undvika namnkonflikter, standardvärdet är "rvm:" |

 **Result:**



---


### getLookupAttributes{#getLookupAttributes}

| Namn | Beskrivning |
| --- | --- |
| getLookupAttributes() | Hämtar eller anger huruvida attribut ska läsas in från extern attributlistfil (.att/.attrib/.txt), standardvärdet är true. |

 **Result:**



---


### setLookupAttributes{#setLookupAttributes}

| Namn | Beskrivning |
| --- | --- |
| setLookupAttributes(value) | Hämtar eller anger huruvida attribut ska läsas in från extern attributlistfil (.att/.attrib/.txt), standardvärdet är true. |

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



