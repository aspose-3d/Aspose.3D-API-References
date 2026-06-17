---
title: "FbxSaveOptions"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Sparaalternativ för Fbx-fil.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| konstruktor(format) | Initierar en FbxSaveOptions |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| form | Filformat | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(contentType) | Initiera en FbxSaveOptions med den senaste stödda versionen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| Namn | Beskrivning |
| --- | --- |
| getReusePrimitiveMesh() | Återanvänd nätet för primitivorna med samma parametrar, detta kommer avsevärt minska storleken på FBX-utdata när scenen är konstruerad av en stor mängd primitiva former (t.ex. importerade från CAD-filer). Standardvärdet är falskt. |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| Namn | Beskrivning |
| --- | --- |
| setReusePrimitiveMesh(value) | Återanvänd nätet för primitivorna med samma parametrar, detta kommer avsevärt minska storleken på FBX-utdata när scenen är konstruerad av en stor mängd primitiva former (t.ex. importerade från CAD-filer). Standardvärdet är falskt. |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| Namn | Beskrivning |
| --- | --- |
| getEnableCompression() | Komprimering av stora binära data i FBX-filen (t.ex. animationsdata, kontrollpunkter, vertex-elementdata, index), standardvärdet är sant. |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| Namn | Beskrivning |
| --- | --- |
| setEnableCompression(value) | Komprimering av stora binära data i FBX-filen (t.ex. animationsdata, kontrollpunkter, vertex-elementdata, index), standardvärdet är sant. |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| Namn | Beskrivning |
| --- | --- |
| getFoldRepeatedCurveData() | Hämtar eller anger om upprepad kurvdata ska återanvändas genom att öka den sista datans referensräkning, true om upprepad kurvdata ska fällas; annars false. |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| Namn | Beskrivning |
| --- | --- |
| getExportLegacyMaterialProperties() | Hämtar eller anger om äldre materialegenskaper ska exporteras, används för bakåtkompatibilitet. Detta alternativ är aktiverat som standard. |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| Namn | Beskrivning |
| --- | --- |
| setExportLegacyMaterialProperties(value) | Hämtar eller anger om äldre materialegenskaper ska exporteras, används för bakåtkompatibilitet. Detta alternativ är aktiverat som standard. |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| Namn | Beskrivning |
| --- | --- |
| getVideoForTexture() | Hämtar eller anger om en Video-instans ska genereras för Textur vid export som FBX. |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| Namn | Beskrivning |
| --- | --- |
| setVideoForTexture(value) | Hämtar eller anger om en Video-instans ska genereras för Textur vid export som FBX. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Namn | Beskrivning |
| --- | --- |
| getEmbedTextures() | Hämtar eller anger om texturen ska bäddas in i den slutliga utdatafilen. FBX Exporter kommer att försöka hitta texturens rådata från filsystemet och bädda in filen i den slutliga FBX-filen. Standardvärdet är falskt. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Namn | Beskrivning |
| --- | --- |
| setEmbedTextures(value) | Hämtar eller anger om texturen ska bäddas in i den slutliga utdatafilen. FBX Exporter kommer att försöka hitta texturens rådata från filsystemet och bädda in filen i den slutliga FBX-filen. Standardvärdet är falskt. |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| Namn | Beskrivning |
| --- | --- |
| getGenerateVertexElementMaterial() | Hämtar eller anger om ett VertexElementMaterial alltid ska genereras för geometrier om den bifogade noden innehåller material. Detta är avstängt som standard. |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| Namn | Beskrivning |
| --- | --- |
| setGenerateVertexElementMaterial(value) | Hämtar eller anger om ett VertexElementMaterial alltid ska genereras för geometrier om den bifogade noden innehåller material. Detta är avstängt som standard. |

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



