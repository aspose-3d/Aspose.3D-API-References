---
title: "PdfSaveOptions"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/pdfsaveoptions/
---
## PdfSaveOptions class

De opslaanopties bij het exporteren van PDF.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Constructor van PdfSaveOptions |

 **Result:**



---


### getRenderMode{#getRenderMode}

| Naam | Beschrijving |
| --- | --- |
| getRenderMode() | Render-modus geeft de stijl aan waarin het 3D-werk wordt gerenderd. De waarde van de eigenschap is de PdfRenderMode integer-constante. |

 **Result:**



---


### setRenderMode{#setRenderMode}

| Naam | Beschrijving |
| --- | --- |
| setRenderMode(value) | Render-modus geeft de stijl aan waarin het 3D-werk wordt gerenderd. De waarde van de eigenschap is de PdfRenderMode integer-constante. |

 **Result:**



---


### getLightingScheme{#getLightingScheme}

| Naam | Beschrijving |
| --- | --- |
| getLightingScheme() | LightingScheme geeft de verlichting aan die op 3D-werk moet worden toegepast. De waarde van de eigenschap is de PdfLightingScheme integer-constante. |

 **Result:**



---


### setLightingScheme{#setLightingScheme}

| Naam | Beschrijving |
| --- | --- |
| setLightingScheme(value) | LightingScheme geeft de verlichting aan die op 3D-werk moet worden toegepast. De waarde van de eigenschap is de PdfLightingScheme integer-constante. |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| Naam | Beschrijving |
| --- | --- |
| getBackgroundColor() | Achtergrondkleur van de 3D-weergave in PDF-bestand. |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| Naam | Beschrijving |
| --- | --- |
| setBackgroundColor(value) | Achtergrondkleur van de 3D-weergave in PDF-bestand. |

 **Result:**



---


### getFaceColor{#getFaceColor}

| Naam | Beschrijving |
| --- | --- |
| getFaceColor() | Haalt op of stelt de face color in die gebruikt wordt bij het renderen van de 3D-inhoud. Dit is alleen relevant wanneer RenderMode de waarde Illustration heeft. |

 **Result:**



---


### setFaceColor{#setFaceColor}

| Naam | Beschrijving |
| --- | --- |
| setFaceColor(value) | Haalt op of stelt de face color in die gebruikt wordt bij het renderen van de 3D-inhoud. Dit is alleen relevant wanneer RenderMode de waarde Illustration heeft. |

 **Result:**



---


### getAuxiliaryColor{#getAuxiliaryColor}

| Naam | Beschrijving |
| --- | --- |
| getAuxiliaryColor() | Haalt op of stelt de hulpkleur in die wordt gebruikt bij het renderen van de 3D-inhoud. De interpretatie van deze kleur hangt af van de RenderMode |

 **Result:**



---


### setAuxiliaryColor{#setAuxiliaryColor}

| Naam | Beschrijving |
| --- | --- |
| setAuxiliaryColor(value) | Haalt op of stelt de hulpkleur in die wordt gebruikt bij het renderen van de 3D-inhoud. De interpretatie van deze kleur hangt af van de RenderMode |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Naam | Beschrijving |
| --- | --- |
| getFlipCoordinateSystem() | Haalt op of stelt in om het coördinatensysteem van de scène tijdens het exporteren te draaien. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Naam | Beschrijving |
| --- | --- |
| setFlipCoordinateSystem(value) | Haalt op of stelt in om het coördinatensysteem van de scène tijdens het exporteren te draaien. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Naam | Beschrijving |
| --- | --- |
| getEmbedTextures() | Integreer de externe texturen in het PDF-bestand, standaardwaarde is false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Naam | Beschrijving |
| --- | --- |
| setEmbedTextures(value) | Integreer de externe texturen in het PDF-bestand, standaardwaarde is false. |

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



