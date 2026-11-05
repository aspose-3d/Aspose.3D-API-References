---
title: "MemoryFileSystem"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

Il MemoryFileSystem mapperà le operazioni di lettura/scrittura alla memoria.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| Nome | Descrizione |
| --- | --- |
| getFileNames() | Nomi dei file presenti in questo file system in memoria. |

 **Result:**



---


### getFileContent{#getFileContent}

| Nome | Descrizione |
| --- | --- |
| getFileContent(fileName) | Restituisce il contenuto grezzo del file specificato. Lancia System.IO.FileNotFoundException se il file specificato non esiste. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| Nome | Descrizione |
| --- | --- |
| readFile(fileName, options) | Crea uno stream per leggere le dipendenze. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileNam | String | null |
| opzione | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| Nome | Descrizione |
| --- | --- |
| writeFile(fileName, options) | Crea un flusso per scrivere le dipendenze. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileNam | String | null |
| opzione | IOConfig | null |

 **Result:**
Stream


---



