---
title: "GltfSaveOptions"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

Opzioni di salvataggio per il formato glTF.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(contentType) | Costruttore di GltfSaveOptions |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(format) | Costruttore di GltfSaveOptions |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| forma | FormatoFile | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| Nome | Descrizione |
| --- | --- |
| getPrettyPrint() | Il contenuto JSON del file GLTF è indentato per la lettura umana, il valore predefinito è false |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| Nome | Descrizione |
| --- | --- |
| setPrettyPrint(value) | Il contenuto JSON del file GLTF è indentato per la lettura umana, il valore predefinito è false |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| Nome | Descrizione |
| --- | --- |
| getFallbackNormal() | Quando l'esportatore GLTF2 rileva una normale non valida, questa verrà utilizzata al posto del valore originale per bypassare la convalida. Il valore predefinito è (0, 1, 0) |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| Nome | Descrizione |
| --- | --- |
| getEmbedAssets() | Incorpora tutti gli asset esterni come base64 in un unico file in modalità ASCII, il valore predefinito è false. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| Nome | Descrizione |
| --- | --- |
| setEmbedAssets(value) | Incorpora tutti gli asset esterni come base64 in un unico file in modalità ASCII, il valore predefinito è false. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| Nome | Descrizione |
| --- | --- |
| getImageFormat() | Lo standard glTF supporta solo PNG/JPG come formato texture; questa opzione indicherà come Aspose.3D converte le immagini non standard nel formato supportato durante l'esportazione. Il valore predefinito è GltfEmbeddedImageFormat.PNG. Il valore della proprietà è la costante intera GltfEmbeddedImageFormat. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| Nome | Descrizione |
| --- | --- |
| setImageFormat(value) | Lo standard glTF supporta solo PNG/JPG come formato texture; questa opzione indicherà come Aspose.3D converte le immagini non standard nel formato supportato durante l'esportazione. Il valore predefinito è GltfEmbeddedImageFormat.PNG. Il valore della proprietà è la costante intera GltfEmbeddedImageFormat. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Nome | Descrizione |
| --- | --- |
| getMaterialConverter() | Convertitore personalizzato per convertire il materiale della geometria in materiale PBR. Se non assegnato, l'esportatore glTF 2.0 convertirà automaticamente il materiale standard in materiale PBR. Il valore predefinito è null. Questa proprietà è utilizzata durante l'esportazione di una scena in un file glTF 2.0. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Nome | Descrizione |
| --- | --- |
| setMaterialConverter(value) | Convertitore personalizzato per convertire il materiale della geometria in materiale PBR. Se non assegnato, l'esportatore glTF 2.0 convertirà automaticamente il materiale standard in materiale PBR. Il valore predefinito è null. Questa proprietà è utilizzata durante l'esportazione di una scena in un file glTF 2.0. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| Nome | Descrizione |
| --- | --- |
| getUseCommonMaterials() | Serializza i materiali usando le estensioni KHR common material, valore predefinito è false. Impostare questo a false farà sì che Aspose.3D esporti un set di shader vertex/fragment se #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| Nome | Descrizione |
| --- | --- |
| setUseCommonMaterials(value) | Serializza i materiali usando le estensioni KHR common material, valore predefinito è false. Impostare questo a false farà sì che Aspose.3D esporti un set di shader vertex/fragment se #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| Nome | Descrizione |
| --- | --- |
| getExternalDracoEncoder() | Utilizza un encoder draco esterno per accelerare la velocità di compressione draco. Aspose.3D creerà un nuovo sottoprocesso per codificare la mesh nel formato draco; usalo a tuo rischio. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| Nome | Descrizione |
| --- | --- |
| setExternalDracoEncoder(value) | Utilizza un encoder draco esterno per accelerare la velocità di compressione draco. Aspose.3D creerà un nuovo sottoprocesso per codificare la mesh nel formato draco; usalo a tuo rischio. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| Nome | Descrizione |
| --- | --- |
| getFlipTexCoordV() | Inverti la componente v(t) della coordinata texture, valore predefinito è true. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| Nome | Descrizione |
| --- | --- |
| setFlipTexCoordV(value) | Inverti la componente v(t) della coordinata texture, valore predefinito è true. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| Nome | Descrizione |
| --- | --- |
| getBufferFile() | Il nome del file del buffer esterno utilizzato per memorizzare i dati binari. Se questo file non è specificato, Aspose.3D genererà un nome per te. Questo viene ignorato quando si esporta glTF in modalità binaria. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| Nome | Descrizione |
| --- | --- |
| setBufferFile(value) | Il nome del file del buffer esterno utilizzato per memorizzare i dati binari. Se questo file non è specificato, Aspose.3D genererà un nome per te. Questo viene ignorato quando si esporta glTF in modalità binaria. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| Nome | Descrizione |
| --- | --- |
| getSaveExtras() | Salva le proprietà dinamiche dell'oggetto scena nei campi 'extra' del file glTF generato. Questo è utile per fornire dati specifici dell'applicazione. Il valore predefinito è false. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| Nome | Descrizione |
| --- | --- |
| setSaveExtras(value) | Salva le proprietà dinamiche dell'oggetto scena nei campi 'extra' del file glTF generato. Questo è utile per fornire dati specifici dell'applicazione. Il valore predefinito è false. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| Nome | Descrizione |
| --- | --- |
| getApplyUnitScale() | Applica AssetInfo.UnitScaleFactor alla mesh. Il valore predefinito è false. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| Nome | Descrizione |
| --- | --- |
| setApplyUnitScale(value) | Applica AssetInfo.UnitScaleFactor alla mesh. Il valore predefinito è false. |

 **Result:**



---


### getDracoCompression{#getDracoCompression}

| Nome | Descrizione |
| --- | --- |
| getDracoCompression() | Ottiene o imposta se abilitare la compressione draco |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| Nome | Descrizione |
| --- | --- |
| setDracoCompression(value) | Ottiene o imposta se abilitare la compressione draco |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Nome | Descrizione |
| --- | --- |
| getExportTextures() | Prova a copiare le texture utilizzate nella scena nella directory di output. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Nome | Descrizione |
| --- | --- |
| setExportTextures(value) | Prova a copiare le texture utilizzate nella scena nella directory di output. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Nome | Descrizione |
| --- | --- |
| getFileFormat() | Ottiene il formato file specificato nell'opzione Salva/Carica corrente. |

 **Result:**



---


### getEncoding{#getEncoding}

| Nome | Descrizione |
| --- | --- |
| getEncoding() | Ottiene o imposta la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Nome | Descrizione |
| --- | --- |
| getFileSystem() | Consente all'utente di gestire come amministrare le dipendenze esterne durante il caricamento/salvataggio. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Nome | Descrizione |
| --- | --- |
| setFileSystem(value) | Consente all'utente di gestire come amministrare le dipendenze esterne durante il caricamento/salvataggio. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Nome | Descrizione |
| --- | --- |
| getLookupPaths() | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare i file esterni da caricare. |

 **Result:**



---


### getFileName{#getFileName}

| Nome | Descrizione |
| --- | --- |
| getFileName() | Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Nome | Descrizione |
| --- | --- |
| setFileName(value) | Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ. |

 **Result:**



---



