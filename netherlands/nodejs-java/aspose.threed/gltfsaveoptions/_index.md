---
title: "GltfSaveOptions"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

Opslaanopties voor glTF-formaat.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(contentType) | Constructor van GltfSaveOptions |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(format) | Constructor van GltfSaveOptions |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| forma | FileFormat | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| Naam | Beschrijving |
| --- | --- |
| getPrettyPrint() | De JSON-inhoud van het GLTF-bestand is ingesprongen voor menselijke leesbaarheid, standaardwaarde is false |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| Naam | Beschrijving |
| --- | --- |
| setPrettyPrint(value) | De JSON-inhoud van het GLTF-bestand is ingesprongen voor menselijke leesbaarheid, standaardwaarde is false |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| Naam | Beschrijving |
| --- | --- |
| getFallbackNormal() | Wanneer GLTF2 exporter een ongeldige normaal detecteerde, wordt dit gebruikt in plaats van de oorspronkelijke waarde om de validatie te omzeilen. Standaardwaarde is (0, 1, 0) |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| Naam | Beschrijving |
| --- | --- |
| getEmbedAssets() | Alle externe assets als base64 in één bestand in ASCII-modus insluiten, standaardwaarde is false. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| Naam | Beschrijving |
| --- | --- |
| setEmbedAssets(value) | Alle externe assets als base64 in één bestand in ASCII-modus insluiten, standaardwaarde is false. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| Naam | Beschrijving |
| --- | --- |
| getImageFormat() | Standaard glTF ondersteunt alleen PNG/JPG als textuurformaat; deze optie bepaalt hoe Aspose.3D de niet-standaard afbeeldingen converteert naar een ondersteund formaat tijdens het exporteren. Standaardwaarde is GltfEmbeddedImageFormat.PNG De waarde van de eigenschap is de GltfEmbeddedImageFormat integerconstante. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| Naam | Beschrijving |
| --- | --- |
| setImageFormat(value) | Standaard glTF ondersteunt alleen PNG/JPG als textuurformaat; deze optie bepaalt hoe Aspose.3D de niet-standaard afbeeldingen converteert naar een ondersteund formaat tijdens het exporteren. Standaardwaarde is GltfEmbeddedImageFormat.PNG De waarde van de eigenschap is de GltfEmbeddedImageFormat integerconstante. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Naam | Beschrijving |
| --- | --- |
| getMaterialConverter() | Aangepaste converter om het materiaal van de geometrie te converteren naar PBR‑materiaal. Als dit niet is toegewezen, zal de glTF 2.0 exporter automatisch het standaardmateriaal converteren naar PBR‑materiaal. Standaardwaarde is null. Deze eigenschap wordt gebruikt bij het exporteren van een scène naar een glTF 2.0‑bestand. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Naam | Beschrijving |
| --- | --- |
| setMaterialConverter(value) | Aangepaste converter om het materiaal van de geometrie te converteren naar PBR‑materiaal. Als dit niet is toegewezen, zal de glTF 2.0 exporter automatisch het standaardmateriaal converteren naar PBR‑materiaal. Standaardwaarde is null. Deze eigenschap wordt gebruikt bij het exporteren van een scène naar een glTF 2.0‑bestand. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| Naam | Beschrijving |
| --- | --- |
| getUseCommonMaterials() | Materialen serialiseren met KHR‑common‑material‑extensies, standaardwaarde is false. Als dit op false wordt gezet, zal Aspose.3D een set vertex/fragment‑shaders exporteren als #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| Naam | Beschrijving |
| --- | --- |
| setUseCommonMaterials(value) | Materialen serialiseren met KHR‑common‑material‑extensies, standaardwaarde is false. Als dit op false wordt gezet, zal Aspose.3D een set vertex/fragment‑shaders exporteren als #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| Naam | Beschrijving |
| --- | --- |
| getExternalDracoEncoder() | Gebruik een externe draco‑encoder om de draco‑compressiesnelheid te versnellen. Aspose.3D zal een nieuw subproces aanmaken om het mesh te coderen naar het draco‑formaat; gebruik dit op eigen risico. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| Naam | Beschrijving |
| --- | --- |
| setExternalDracoEncoder(value) | Gebruik een externe draco‑encoder om de draco‑compressiesnelheid te versnellen. Aspose.3D zal een nieuw subproces aanmaken om het mesh te coderen naar het draco‑formaat; gebruik dit op eigen risico. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| Naam | Beschrijving |
| --- | --- |
| getFlipTexCoordV() | Draai de v(t)-component van de textuurcoördinaat om, standaardwaarde is true. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| Naam | Beschrijving |
| --- | --- |
| setFlipTexCoordV(value) | Draai de v(t)-component van de textuurcoördinaat om, standaardwaarde is true. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| Naam | Beschrijving |
| --- | --- |
| getBufferFile() | De bestandsnaam van het externe bufferbestand dat wordt gebruikt om binaire gegevens op te slaan. Als dit bestand niet is opgegeven, genereert Aspose.3D een naam voor u. Dit wordt genegeerd bij het exporteren van glTF in binaire modus. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| Naam | Beschrijving |
| --- | --- |
| setBufferFile(value) | De bestandsnaam van het externe bufferbestand dat wordt gebruikt om binaire gegevens op te slaan. Als dit bestand niet is opgegeven, genereert Aspose.3D een naam voor u. Dit wordt genegeerd bij het exporteren van glTF in binaire modus. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| Naam | Beschrijving |
| --- | --- |
| getSaveExtras() | Sla de dynamische eigenschappen van scene‑objecten op in 'extra'-velden in het gegenereerde glTF‑bestand. Dit is handig om toepassingsspecifieke gegevens te leveren. Standaardwaarde is false. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| Naam | Beschrijving |
| --- | --- |
| setSaveExtras(value) | Sla de dynamische eigenschappen van scene‑objecten op in 'extra'-velden in het gegenereerde glTF‑bestand. Dit is handig om toepassingsspecifieke gegevens te leveren. Standaardwaarde is false. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| Naam | Beschrijving |
| --- | --- |
| getApplyUnitScale() | Pas AssetInfo.UnitScaleFactor toe op het mesh. Standaardwaarde is false. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| Naam | Beschrijving |
| --- | --- |
| setApplyUnitScale(value) | Pas AssetInfo.UnitScaleFactor toe op het mesh. Standaardwaarde is false. |

 **Result:**



---


### getDracoCompression{#getDracoCompression}

| Naam | Beschrijving |
| --- | --- |
| getDracoCompression() | Haalt op of stelt in of draco‑compressie moet worden ingeschakeld |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| Naam | Beschrijving |
| --- | --- |
| setDracoCompression(value) | Haalt op of stelt in of draco‑compressie moet worden ingeschakeld |

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



