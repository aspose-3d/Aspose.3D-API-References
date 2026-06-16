---
title: "UsdSaveOptions"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

Opzioni di salvataggio per i formati USD/USDZ.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza un nuovo UsdSaveOptions con il formato FileFormat.USD |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(fileFormat) | Inizializza un nuovo UsdSaveOptions con il formato USD/USDZ specificato. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| Nome | Descrizione |
| --- | --- |
| getPrimitiveToMesh() | Converti le entità primitive in mesh durante l'esportazione. Oppure codifica direttamente le primitive nel file di output (verrà utilizzata la definizione di estensione di Aspose per primitive non ufficiali come Dish, Torus). Il valore predefinito è true. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| Nome | Descrizione |
| --- | --- |
| setPrimitiveToMesh(value) | Converti le entità primitive in mesh durante l'esportazione. Oppure codifica direttamente le primitive nel file di output (verrà utilizzata la definizione di estensione di Aspose per primitive non ufficiali come Dish, Torus). Il valore predefinito è true. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| Nome | Descrizione |
| --- | --- |
| getExportMetaData() | Esporta le proprietà del nodo tramite il campo customData di USD. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| Nome | Descrizione |
| --- | --- |
| setExportMetaData(value) | Esporta le proprietà del nodo tramite il campo customData di USD. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Nome | Descrizione |
| --- | --- |
| getMaterialConverter() | Convertitore personalizzato per convertire il materiale della geometria in materiale PBR. Se non assegnato, l'esportatore USD convertirà automaticamente il materiale standard in materiale PBR. Il valore predefinito è null |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Nome | Descrizione |
| --- | --- |
| setMaterialConverter(value) | Convertitore personalizzato per convertire il materiale della geometria in materiale PBR. Se non assegnato, l'esportatore USD convertirà automaticamente il materiale standard in materiale PBR. Il valore predefinito è null |

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



