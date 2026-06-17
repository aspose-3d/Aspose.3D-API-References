---
title: "ZipArchiveFileSystem"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/ziparchivefilesystem/
---
## ZipArchiveFileSystem class

Файловая система, предоставляющая только чтение к указанному zip‑файлу или zip‑потоку.  Файловая система будет освобождена после операции открытия/сохранения.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(fileName) | Создать ZipArchiveFileSystem по имени файла. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**



---


### readFile{#readFile}

| Имя | Описание |
| --- | --- |
| readFile(fileName, options) | Открыть файл для чтения |

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
| writeFile(fileName, options) | Открыть файл для записи, не реализовано в этом классе. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileNam | String | null |
| опция | IOConfig | null |

 **Result:**
Stream


---



