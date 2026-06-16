---
title: "DracoFormat"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Formato Google Draco  @hideconstructor


## Metodi

### getVersion{#getVersion}

| Nome | Descrizione |
| --- | --- |
| getVersion() | Ottiene la versione del formato file |

 **Result:**



---


### getExtension{#getExtension}

| Nome | Descrizione |
| --- | --- |
| getExtension() | Ottiene il nome dell'estensione di questo tipo. |

 **Result:**



---


### getExtensions{#getExtensions}

| Nome | Descrizione |
| --- | --- |
| getExtensions() | Ottiene i nomi delle estensioni di questo tipo. |

 **Result:**



---


### getContentType{#getContentType}

| Nome | Descrizione |
| --- | --- |
| getContentType() | Ottiene il tipo di contenuto del formato file. Il valore della proprietà è la costante intera FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Nome | Descrizione |
| --- | --- |
| getFileFormatType() | Ottiene il tipo di formato file |

 **Result:**



---


### decode{#decode}

| Nome | Descrizione |
| --- | --- |
| decode(fileName) | Decodifica la nuvola di punti o la mesh dal nome file specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | Stringa | Il nome file contiene il file drc |

 **Result:**
Geometry


---


### decode{#decode}

| Nome | Descrizione |
| --- | --- |
| decode(data) | Decodifica la nuvola di punti o la mesh dai dati in memoria |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| data | byte[] | I byte grezzi drc |

 **Result:**
Geometry


---


### encode{#encode}

| Nome | Descrizione |
| --- | --- |
| encode(entity, fileName, options) | Codifica l'entità nel file specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| entity | Entità | L'entità da codificare |
| fileName | Stringa | Il nome file da scrivere |
| opzioni | DracoSaveOptions | Opzioni extra per la codifica della nuvola di punti |

 **Result:**
Geometry


---


### encode{#encode}

| Nome | Descrizione |
| --- | --- |
| encode(entity, options) | Codifica l'entità nei dati grezzi Draco |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| entity | Entità | L'entità da codificare |
| opzioni | DracoSaveOptions | Opzioni extra per la codifica della nuvola di punti |

 **Result:**
byte[]


---


### createLoadOptions{#createLoadOptions}

| Nome | Descrizione |
| --- | --- |
| createLoadOptions() | Crea le opzioni di caricamento predefinite per questo formato file |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Nome | Descrizione |
| --- | --- |
| createSaveOptions() | Crea le opzioni di salvataggio predefinite per questo formato file |

 **Result:**
SaveOptions


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Formati in stringa |

 **Result:**
Stringa


---



