---
title: "PlyFormat"
second_title: "Aspose.3D per Node.js via Java API Reference"
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


### encode{#encode}

| Nome | Descrizione |
| --- | --- |
| encode(entity, fileName) | Codifica l'entità e salva il risultato in un file esterno. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| entity | Entità | L'entità da codificare |
| fileName | Stringa | Il file su cui scrivere |

 **Result:**



---


### encode{#encode}

| Nome | Descrizione |
| --- | --- |
| encode(entity, fileName, opt) | Codifica l'entità e salva il risultato in un file esterno. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| entity | Entità | L'entità da codificare |
| fileName | Stringa | Il file su cui scrivere |
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
| fileName | Stringa | Lo stream di input |

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
| fileName | Stringa | Lo stream di input |
| opt | PlyLoadOptions | L'opzione di caricamento del formato PLY |

 **Result:**
Geometry


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



