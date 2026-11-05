---
title: "DracoFormat"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
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
| getVersion() | Restituisce la versione del formato file |

 **Result:**



---


### getExtension{#getExtension}

| Nome | Descrizione |
| --- | --- |
| getExtension() | Restituisce il nome dell'estensione di questo tipo. |

 **Result:**



---


### getExtensions{#getExtensions}

| Nome | Descrizione |
| --- | --- |
| getExtensions() | Restituisce i nomi delle estensioni di questo tipo. |

 **Result:**



---


### getContentType{#getContentType}

| Nome | Descrizione |
| --- | --- |
| getContentType() | Restituisce il tipo di contenuto del formato file. Il valore della proprietà è la costante intera FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Nome | Descrizione |
| --- | --- |
| getFileFormatType() | Restituisce il tipo di formato file |

 **Result:**



---


### decode{#decode}

| Nome | Descrizione |
| --- | --- |
| decode(fileName) | Decodifica la nuvola di punti o la mesh dal nome file specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Il nome del file contiene il file drc |

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
| entità | Entità | L'entità da codificare |
| fileName | String | Il nome del file da scrivere |
| opzioni | DracoSaveOptions | Opzioni extra per la codifica della nuvola di punti |

 **Result:**
Geometry


---


### encode{#encode}

| Nome | Descrizione |
| --- | --- |
| encode(entity, options) | Codifica l'entità nei dati raw di Draco |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| entità | Entità | L'entità da codificare |
| opzioni | DracoSaveOptions | Opzioni extra per la codifica della nuvola di punti |

 **Result:**
byte[]


---


### createLoadOptions{#createLoadOptions}

| Nome | Descrizione |
| --- | --- |
| createLoadOptions() | Crea un'opzione di caricamento predefinita per questo formato file |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Nome | Descrizione |
| --- | --- |
| createSaveOptions() | Crea un'opzione di salvataggio predefinita per questo formato file |

 **Result:**
SaveOptions


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Formati in stringa |

 **Result:**
String


---



