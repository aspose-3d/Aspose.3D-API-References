---
title: "UsdSaveOptions"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

Spara alternativ för USD/USDZ-format.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny UsdSaveOptions med formatet FileFormat.USD |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(fileFormat) | Initierar en ny UsdSaveOptions med angivet USD/USDZ-format. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| Namn | Beskrivning |
| --- | --- |
| getPrimitiveToMesh() | Konvertera de primitiva enheterna till mesh under exporten. Eller koda direkt primitiva till utdatafilen (kommer att använda Aspose's extensionsdefinition för inofficiella primitiva som Dish, Torus). Standardvärdet är true. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| Namn | Beskrivning |
| --- | --- |
| setPrimitiveToMesh(value) | Konvertera de primitiva enheterna till mesh under exporten. Eller koda direkt primitiva till utdatafilen (kommer att använda Aspose's extensionsdefinition för inofficiella primitiva som Dish, Torus). Standardvärdet är true. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| Namn | Beskrivning |
| --- | --- |
| getExportMetaData() | Exportera nodens egenskaper via USD:s customData-fält. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| Namn | Beskrivning |
| --- | --- |
| setExportMetaData(value) | Exportera nodens egenskaper via USD:s customData-fält. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Namn | Beskrivning |
| --- | --- |
| getMaterialConverter() | Anpassad konverterare för att konvertera geometrins material till PBR-material. Om detta är odefinierat kommer USD-exportören automatiskt att konvertera standardmaterialet till PBR-material. Standardvärdet är null. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Namn | Beskrivning |
| --- | --- |
| setMaterialConverter(value) | Anpassad konverterare för att konvertera geometrins material till PBR-material. Om detta är odefinierat kommer USD-exportören automatiskt att konvertera standardmaterialet till PBR-material. Standardvärdet är null. |

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



