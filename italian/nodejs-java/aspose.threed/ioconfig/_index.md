---
title: "IOConfig"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/ioconfig/
---
## IOConfig class

Configurazione IO per serializzazione/deserializzazione.  L'utente può specificare configurazioni dettagliate come il percorso di ricerca delle dipendenze  O configurazioni correlate al formato qui  @hideconstructor


## Metodi

### getFileSystemFactory{#getFileSystemFactory}

| Nome | Descrizione |
| --- | --- |
| getFileSystemFactory() | Ottiene o imposta la classe factory per FileSystem. La factory predefinita creerà LocalFileSystem, che non è adatta per un ambiente server. |

 **Result:**



---


### setFileSystemFactory{#setFileSystemFactory}

| Nome | Descrizione |
| --- | --- |
| setFileSystemFactory(value) | Ottiene o imposta la classe factory per FileSystem. La factory predefinita creerà LocalFileSystem, che non è adatta per un ambiente server. |

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



