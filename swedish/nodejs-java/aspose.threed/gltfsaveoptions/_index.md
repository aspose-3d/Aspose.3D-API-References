---
title: "GltfSaveOptions"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

Sparaalternativ för glTF-format.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(contentType) | Konstruktor för GltfSaveOptions |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(format) | Konstruktor för GltfSaveOptions |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| form | Filformat | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| Namn | Beskrivning |
| --- | --- |
| getPrettyPrint() | JSON-innehållet i GLTF-filen är indenterat för mänsklig läsning, standardvärdet är false |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| Namn | Beskrivning |
| --- | --- |
| setPrettyPrint(value) | JSON-innehållet i GLTF-filen är indenterat för mänsklig läsning, standardvärdet är false |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| Namn | Beskrivning |
| --- | --- |
| getFallbackNormal() | När GLTF2-exportören upptäcker en ogiltig normal, kommer detta att användas istället för dess ursprungliga värde för att kringgå valideringen. Standardvärdet är (0, 1, 0) |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| Namn | Beskrivning |
| --- | --- |
| getEmbedAssets() | Bädda in alla externa resurser som base64 i en enda fil i ASCII-läge, standardvärdet är false. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| Namn | Beskrivning |
| --- | --- |
| setEmbedAssets(value) | Bädda in alla externa resurser som base64 i en enda fil i ASCII-läge, standardvärdet är false. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| Namn | Beskrivning |
| --- | --- |
| getImageFormat() | Standard glTF stöder endast PNG/JPG som sitt texturformat, detta alternativ kommer att vägleda hur Aspose.3D konverterar de icke‑standardiserade bilderna till ett stödformat under exporten. Standardvärdet är GltfEmbeddedImageFormat.PNG Värdet på egenskapen är GltfEmbeddedImageFormat heltalskonstant. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| Namn | Beskrivning |
| --- | --- |
| setImageFormat(value) | Standard glTF stöder endast PNG/JPG som sitt texturformat, detta alternativ kommer att vägleda hur Aspose.3D konverterar de icke‑standardiserade bilderna till ett stödformat under exporten. Standardvärdet är GltfEmbeddedImageFormat.PNG Värdet på egenskapen är GltfEmbeddedImageFormat heltalskonstant. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Namn | Beskrivning |
| --- | --- |
| getMaterialConverter() | Anpassad konverterare för att konvertera geometriens material till PBR‑material. Om detta är odefinierat kommer glTF 2.0‑exportören automatiskt att konvertera standardmaterialet till PBR‑material. Standardvärdet är null. Denna egenskap används vid export av en scen till en glTF 2.0‑fil. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Namn | Beskrivning |
| --- | --- |
| setMaterialConverter(value) | Anpassad konverterare för att konvertera geometriens material till PBR‑material. Om detta är odefinierat kommer glTF 2.0‑exportören automatiskt att konvertera standardmaterialet till PBR‑material. Standardvärdet är null. Denna egenskap används vid export av en scen till en glTF 2.0‑fil. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| Namn | Beskrivning |
| --- | --- |
| getUseCommonMaterials() | Serialisera material med KHR‑gemensamma material‑tillägg, standardvärdet är false. Att sätta detta till false kommer att få Aspose.3D att exportera en uppsättning vertex/fragment‑shader om #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| Namn | Beskrivning |
| --- | --- |
| setUseCommonMaterials(value) | Serialisera material med KHR‑gemensamma material‑tillägg, standardvärdet är false. Att sätta detta till false kommer att få Aspose.3D att exportera en uppsättning vertex/fragment‑shader om #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| Namn | Beskrivning |
| --- | --- |
| getExternalDracoEncoder() | Använd extern draco‑kodare för att påskynda draco‑komprimeringshastigheten. Aspose.3D kommer att skapa en ny underprocess för att koda meshen till draco‑formatet, använd den på egen risk. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| Namn | Beskrivning |
| --- | --- |
| setExternalDracoEncoder(value) | Använd extern draco‑kodare för att påskynda draco‑komprimeringshastigheten. Aspose.3D kommer att skapa en ny underprocess för att koda meshen till draco‑formatet, använd den på egen risk. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| Namn | Beskrivning |
| --- | --- |
| getFlipTexCoordV() | Vänd texturkoordinatens v(t)-komponent, standardvärdet är true. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| Namn | Beskrivning |
| --- | --- |
| setFlipTexCoordV(value) | Vänd texturkoordinatens v(t)-komponent, standardvärdet är true. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| Namn | Beskrivning |
| --- | --- |
| getBufferFile() | Filnamnet på den externa bufferfilen som används för att lagra binär data. Om denna fil inte specificeras kommer Aspose.3D att generera ett namn åt dig. Detta ignoreras när glTF exporteras i binärt läge. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| Namn | Beskrivning |
| --- | --- |
| setBufferFile(value) | Filnamnet på den externa bufferfilen som används för att lagra binär data. Om denna fil inte specificeras kommer Aspose.3D att generera ett namn åt dig. Detta ignoreras när glTF exporteras i binärt läge. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| Namn | Beskrivning |
| --- | --- |
| getSaveExtras() | Spara scenobjektets dynamiska egenskaper i 'extra'-fält i den genererade glTF‑filen. Detta är användbart för att tillhandahålla applikationsspecifika data. Standardvärdet är false. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| Namn | Beskrivning |
| --- | --- |
| setSaveExtras(value) | Spara scenobjektets dynamiska egenskaper i 'extra'-fält i den genererade glTF‑filen. Detta är användbart för att tillhandahålla applikationsspecifika data. Standardvärdet är false. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| Namn | Beskrivning |
| --- | --- |
| getApplyUnitScale() | Tillämpa AssetInfo.UnitScaleFactor på meshen. Standardvärdet är falskt. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| Namn | Beskrivning |
| --- | --- |
| setApplyUnitScale(value) | Tillämpa AssetInfo.UnitScaleFactor på meshen. Standardvärdet är falskt. |

 **Result:**



---


### getDracoCompression{#getDracoCompression}

| Namn | Beskrivning |
| --- | --- |
| getDracoCompression() | Hämtar eller anger om draco‑komprimering ska aktiveras |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| Namn | Beskrivning |
| --- | --- |
| setDracoCompression(value) | Hämtar eller anger om draco‑komprimering ska aktiveras |

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



