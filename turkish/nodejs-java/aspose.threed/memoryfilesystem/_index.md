---
title: "MemoryFileSystem"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

MemoryFileSystem, okuma/yazma işlemlerini belleğe eşleyecektir.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| Ad | Açıklama |
| --- | --- |
| getFileNames() | Bu bellek dosya sistemindeki dosya adları. |

 **Result:**



---


### getFileContent{#getFileContent}

| Ad | Açıklama |
| --- | --- |
| getFileContent(fileName) | Belirtilen dosyanın ham içeriğini döndürür. Belirtilen dosya mevcut değilse System.IO.FileNotFoundException fırlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| Ad | Açıklama |
| --- | --- |
| readFile(fileName, options) | Bağımlılıkları okumak için bir akış oluşturun. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileNam | String | null |
| option | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| Ad | Açıklama |
| --- | --- |
| writeFile(fileName, options) | Bağımlılıkları yazmak için bir akış oluşturun. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileNam | String | null |
| option | IOConfig | null |

 **Result:**
Stream


---



