---
title: "FbxSaveOptions"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Opzioni di salvataggio per file Fbx.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| costruttore(format) | Inizializza un FbxSaveOptions |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| forma | FormatoFile | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(contentType) | Inizializza un FbxSaveOptions usando l'ultima versione supportata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| Nome | Descrizione |
| --- | --- |
| getReusePrimitiveMesh() | Riutilizza la mesh per le primitive con gli stessi parametri, questo ridurrà significativamente le dimensioni dell'output FBX quando la scena è costruita da un grande insieme di forme primitive (come importate da file CAD). Il valore predefinito è false |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| Nome | Descrizione |
| --- | --- |
| setReusePrimitiveMesh(value) | Riutilizza la mesh per le primitive con gli stessi parametri, questo ridurrà significativamente le dimensioni dell'output FBX quando la scena è costruita da un grande insieme di forme primitive (come importate da file CAD). Il valore predefinito è false |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| Nome | Descrizione |
| --- | --- |
| getEnableCompression() | Compressione dei dati binari di grandi dimensioni nel file FBX (ad es. dati di animazione, punti di controllo, dati degli elementi dei vertici, indici), il valore predefinito è true. |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| Nome | Descrizione |
| --- | --- |
| setEnableCompression(value) | Compressione dei dati binari di grandi dimensioni nel file FBX (ad es. dati di animazione, punti di controllo, dati degli elementi dei vertici, indici), il valore predefinito è true. |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| Nome | Descrizione |
| --- | --- |
| getFoldRepeatedCurveData() | Ottiene o imposta se riutilizzare i dati di curva ripetuti incrementando il conteggio di riferimento dell'ultimo dato; true se si comprimono i dati di curva ripetuti, altrimenti false. |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| Nome | Descrizione |
| --- | --- |
| getExportLegacyMaterialProperties() | Ottiene o imposta se esportare le proprietà dei materiali legacy, utilizzate per la retrocompatibilità. Questa opzione è attiva per impostazione predefinita. |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| Nome | Descrizione |
| --- | --- |
| setExportLegacyMaterialProperties(value) | Ottiene o imposta se esportare le proprietà dei materiali legacy, utilizzate per la retrocompatibilità. Questa opzione è attiva per impostazione predefinita. |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| Nome | Descrizione |
| --- | --- |
| getVideoForTexture() | Ottiene o imposta se generare un'istanza Video per la Texture durante l'esportazione come FBX. |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| Nome | Descrizione |
| --- | --- |
| setVideoForTexture(value) | Ottiene o imposta se generare un'istanza Video per la Texture durante l'esportazione come FBX. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Nome | Descrizione |
| --- | --- |
| getEmbedTextures() | Ottiene o imposta se incorporare la texture nel file di output finale. L'Esportatore FBX cercherà i dati grezzi della texture nel FileSystem e incorporerà il file nel file FBX finale. Il valore predefinito è false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Nome | Descrizione |
| --- | --- |
| setEmbedTextures(value) | Ottiene o imposta se incorporare la texture nel file di output finale. L'Esportatore FBX cercherà i dati grezzi della texture nel FileSystem e incorporerà il file nel file FBX finale. Il valore predefinito è false. |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| Nome | Descrizione |
| --- | --- |
| getGenerateVertexElementMaterial() | Ottiene o imposta se generare sempre un VertexElementMaterial per le geometrie se il nodo collegato contiene materiali. Questa opzione è disattivata per impostazione predefinita. |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| Nome | Descrizione |
| --- | --- |
| setGenerateVertexElementMaterial(value) | Ottiene o imposta se generare sempre un VertexElementMaterial per le geometrie se il nodo collegato contiene materiali. Questa opzione è disattivata per impostazione predefinita. |

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



