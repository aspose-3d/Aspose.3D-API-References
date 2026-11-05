---
title: "PlyFormat"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

Il formato PLY.  @hideconstructor


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


### encode{#encode}

| Nome | Descrizione |
| --- | --- |
| encode(entity, fileName) | Codifica l'entità e salva il risultato in un file esterno. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| entità | Entità | L'entità da codificare |
| fileName | String | Il file su cui scrivere |

 **Result:**



---


### encode{#encode}

| Nome | Descrizione |
| --- | --- |
| encode(entity, fileName, opt) | Codifica l'entità e salva il risultato in un file esterno. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| entità | Entità | L'entità da codificare |
| fileName | String | Il file su cui scrivere |
| opt | PlySaveOptions | Opzioni di salvataggio |

 **Result:**



---


### decode{#decode}

| Nome | Descrizione |
| --- | --- |
| decode(fileName) | Decodifica una nuvola di punti o una mesh dallo stream specificato. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Lo stream di input |

 **Result:**
Geometry


---


### decode{#decode}

| Nome | Descrizione |
| --- | --- |
| decode(fileName, opt) | Decodifica una nuvola di punti o una mesh dallo stream specificato. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Lo stream di input |
| opt | PlyLoadOptions | L'opzione di caricamento del formato PLY |

 **Result:**
Geometry


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



