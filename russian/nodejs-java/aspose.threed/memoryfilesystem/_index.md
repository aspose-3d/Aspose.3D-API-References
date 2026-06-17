---
title: "MemoryFileSystem"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

MemoryFileSystem будет сопоставлять операции чтения/записи с памятью.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| Имя | Описание |
| --- | --- |
| getFileNames() | Имена файлов в этой файловой системе в памяти. |

 **Result:**



---


### getFileContent{#getFileContent}

| Имя | Описание |
| --- | --- |
| getFileContent(fileName) | Возвращает необработанное содержимое указанного файла. Выбрасывает System.IO.FileNotFoundException, если указанный файл не существует. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| Имя | Описание |
| --- | --- |
| readFile(fileName, options) | Создайте поток для чтения зависимостей. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileNam | String | null |
| опция | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| Имя | Описание |
| --- | --- |
| writeFile(fileName, options) | Создайте поток для записи зависимостей. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileNam | String | null |
| опция | IOConfig | null |

 **Result:**
Stream


---



