---
title: "FbxSaveOptions"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Opslaanopties voor Fbx-bestand.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(format) | Initialiseert een FbxSaveOptions |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| forma | Bestandsformaat | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(contentType) | Initialiseer een FbxSaveOptions met de nieuwste ondersteunde versie. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| Naam | Beschrijving |
| --- | --- |
| getReusePrimitiveMesh() | Herbruik de mesh voor de primitieve objecten met dezelfde parameters, dit zal de grootte van de FBX-uitvoer aanzienlijk verkleinen wanneer de scène is opgebouwd uit een grote set primitieve vormen (zoals geïmporteerd uit CAD-bestanden). Standaardwaarde is false |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| Naam | Beschrijving |
| --- | --- |
| setReusePrimitiveMesh(value) | Herbruik de mesh voor de primitieve objecten met dezelfde parameters, dit zal de grootte van de FBX-uitvoer aanzienlijk verkleinen wanneer de scène is opgebouwd uit een grote set primitieve vormen (zoals geïmporteerd uit CAD-bestanden). Standaardwaarde is false |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| Naam | Beschrijving |
| --- | --- |
| getEnableCompression() | Compressie van grote binaire gegevens in het FBX-bestand (bijv. animatiegegevens, controlepunten, vertex-elementgegevens, indexen), standaardwaarde is true. |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| Naam | Beschrijving |
| --- | --- |
| setEnableCompression(value) | Compressie van grote binaire gegevens in het FBX-bestand (bijv. animatiegegevens, controlepunten, vertex-elementgegevens, indexen), standaardwaarde is true. |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| Naam | Beschrijving |
| --- | --- |
| getFoldRepeatedCurveData() | Haalt op of stelt in of herhaald curve‑data moet worden hergebruikt door de referentietelling van de laatste data te verhogen; true als herhaalde curve‑data moet worden samengevouwen; anders false. |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| Naam | Beschrijving |
| --- | --- |
| getExportLegacyMaterialProperties() | Haalt op of stelt in of legacy-materiaal‑eigenschappen moeten worden geëxporteerd, gebruikt voor achterwaartse compatibiliteit. Deze optie is standaard ingeschakeld. |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| Naam | Beschrijving |
| --- | --- |
| setExportLegacyMaterialProperties(value) | Haalt op of stelt in of legacy-materiaal‑eigenschappen moeten worden geëxporteerd, gebruikt voor achterwaartse compatibiliteit. Deze optie is standaard ingeschakeld. |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| Naam | Beschrijving |
| --- | --- |
| getVideoForTexture() | Haalt op of stelt in of er een Video‑instantie moet worden gegenereerd voor Texture bij het exporteren als FBX. |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| Naam | Beschrijving |
| --- | --- |
| setVideoForTexture(value) | Haalt op of stelt in of er een Video‑instantie moet worden gegenereerd voor Texture bij het exporteren als FBX. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Naam | Beschrijving |
| --- | --- |
| getEmbedTextures() | Haalt op of stelt in of de texture moet worden ingebed in het uiteindelijke uitvoerbestand. FBX Exporter zal proberen de ruwe gegevens van de texture te vinden in het bestandssysteem en het bestand in het uiteindelijke FBX‑bestand inbedden. Standaardwaarde is false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Naam | Beschrijving |
| --- | --- |
| setEmbedTextures(value) | Haalt op of stelt in of de texture moet worden ingebed in het uiteindelijke uitvoerbestand. FBX Exporter zal proberen de ruwe gegevens van de texture te vinden in het bestandssysteem en het bestand in het uiteindelijke FBX‑bestand inbedden. Standaardwaarde is false. |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| Naam | Beschrijving |
| --- | --- |
| getGenerateVertexElementMaterial() | Haalt op of stelt in of er altijd een VertexElementMaterial moet worden gegenereerd voor geometrieën als het gekoppelde knooppunt materialen bevat. Dit is standaard uitgeschakeld. |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| Naam | Beschrijving |
| --- | --- |
| setGenerateVertexElementMaterial(value) | Haalt op of stelt in of er altijd een VertexElementMaterial moet worden gegenereerd voor geometrieën als het gekoppelde knooppunt materialen bevat. Dit is standaard uitgeschakeld. |

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



