---
title: "RvmSaveOptions"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Opzioni di salvataggio per il file RVM di Aveva PDMS.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Costruttore di RvmSaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(contentType) | Costruttore di RvmSaveOptions |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| Nome | Descrizione |
| --- | --- |
| getFileNote() | Nota del file nell'intestazione del file. |

 **Result:**



---


### setFileNote{#setFileNote}

| Nome | Descrizione |
| --- | --- |
| setFileNote(value) | Nota del file nell'intestazione del file. |

 **Result:**



---


### getAuthor{#getAuthor}

| Nome | Descrizione |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| Nome | Descrizione |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| Nome | Descrizione |
| --- | --- |
| getCreationTime() | Il timestamp che ha esportato questo file, il valore predefinito è l'ora corrente |

 **Result:**



---


### setCreationTime{#setCreationTime}

| Nome | Descrizione |
| --- | --- |
| setCreationTime(value) | Il timestamp che ha esportato questo file, il valore predefinito è l'ora corrente |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Nome | Descrizione |
| --- | --- |
| getAttributePrefix() | Ottiene o imposta il prefisso degli attributi che verranno esportati; la proprietà esportata non conterrà alcun prefisso, le proprietà personalizzate con prefisso diverso non saranno esportate, il valore predefinito è 'rvm:'. Ad esempio, se una proprietà è rvm:Refno=345, l'attributo esportato sarà Refno = 345, il prefisso viene rimosso. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Nome | Descrizione |
| --- | --- |
| setAttributePrefix(value) | Ottiene o imposta il prefisso degli attributi che verranno esportati; la proprietà esportata non conterrà alcun prefisso, le proprietà personalizzate con prefisso diverso non saranno esportate, il valore predefinito è 'rvm:'. Ad esempio, se una proprietà è rvm:Refno=345, l'attributo esportato sarà Refno = 345, il prefisso viene rimosso. |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| Nome | Descrizione |
| --- | --- |
| getAttributeListFile() | Ottiene o imposta il nome file dell'elenco degli attributi; l'esportatore genererà un nome basato sul nome del file .rvm quando questa proprietà è indefinita, il valore predefinito è null. |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| Nome | Descrizione |
| --- | --- |
| setAttributeListFile(value) | Ottiene o imposta il nome file dell'elenco degli attributi; l'esportatore genererà un nome basato sul nome del file .rvm quando questa proprietà è indefinita, il valore predefinito è null. |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| Nome | Descrizione |
| --- | --- |
| getExportAttributes() | Ottiene o imposta se esportare l'elenco degli attributi in un file .att esterno, il valore predefinito è false. |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| Nome | Descrizione |
| --- | --- |
| setExportAttributes(value) | Ottiene o imposta se esportare l'elenco degli attributi in un file .att esterno, il valore predefinito è false. |

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



