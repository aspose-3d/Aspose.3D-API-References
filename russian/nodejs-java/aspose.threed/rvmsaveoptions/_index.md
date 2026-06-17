---
title: "RvmSaveOptions"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Параметры сохранения RVM‑файла Aveva PDMS.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Конструктор RvmSaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(contentType) | Конструктор RvmSaveOptions |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| Имя | Описание |
| --- | --- |
| getFileNote() | Примечание к файлу в заголовке файла. |

 **Result:**



---


### setFileNote{#setFileNote}

| Имя | Описание |
| --- | --- |
| setFileNote(value) | Примечание к файлу в заголовке файла. |

 **Result:**



---


### getAuthor{#getAuthor}

| Имя | Описание |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| Имя | Описание |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| Имя | Описание |
| --- | --- |
| getCreationTime() | Метка времени, которая экспортировала этот файл; значение по умолчанию — текущее время. |

 **Result:**



---


### setCreationTime{#setCreationTime}

| Имя | Описание |
| --- | --- |
| setCreationTime(value) | Метка времени, которая экспортировала этот файл; значение по умолчанию — текущее время. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Имя | Описание |
| --- | --- |
| getAttributePrefix() | Получает или задает префикс атрибутов, которые будут экспортированы; экспортируемое свойство будет без префикса, пользовательские свойства с другим префиксом экспортированы не будут; значение по умолчанию — 'rvm:'. Например, если свойство имеет вид rvm:Refno=345, экспортируемый атрибут будет Refno = 345, префикс будет удалён. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Имя | Описание |
| --- | --- |
| setAttributePrefix(value) | Получает или задает префикс атрибутов, которые будут экспортированы; экспортируемое свойство будет без префикса, пользовательские свойства с другим префиксом экспортированы не будут; значение по умолчанию — 'rvm:'. Например, если свойство имеет вид rvm:Refno=345, экспортируемый атрибут будет Refno = 345, префикс будет удалён. |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| Имя | Описание |
| --- | --- |
| getAttributeListFile() | Получает или задает имя файла списка атрибутов, экспортёр сгенерирует имя на основе имени файла .rvm, если это свойство не определено, значение по умолчанию — null. |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| Имя | Описание |
| --- | --- |
| setAttributeListFile(value) | Получает или задает имя файла списка атрибутов, экспортёр сгенерирует имя на основе имени файла .rvm, если это свойство не определено, значение по умолчанию — null. |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| Имя | Описание |
| --- | --- |
| getExportAttributes() | Получает или задает, следует ли экспортировать список атрибутов во внешний файл .att, значение по умолчанию — false. |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| Имя | Описание |
| --- | --- |
| setExportAttributes(value) | Получает или задает, следует ли экспортировать список атрибутов во внешний файл .att, значение по умолчанию — false. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Имя | Описание |
| --- | --- |
| getExportTextures() | Попробовать скопировать текстуры, используемые в сцене, в выходной каталог. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Имя | Описание |
| --- | --- |
| setExportTextures(value) | Попробовать скопировать текстуры, используемые в сцене, в выходной каталог. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Имя | Описание |
| --- | --- |
| getFileFormat() | Получает формат файла, указанный в текущей опции Сохранить/Загрузить. |

 **Result:**



---


### getEncoding{#getEncoding}

| Имя | Описание |
| --- | --- |
| getEncoding() | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Имя | Описание |
| --- | --- |
| getFileSystem() | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Имя | Описание |
| --- | --- |
| setFileSystem(value) | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Имя | Описание |
| --- | --- |
| getLookupPaths() | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |

 **Result:**



---


### getFileName{#getFileName}

| Имя | Описание |
| --- | --- |
| getFileName() | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Имя | Описание |
| --- | --- |
| setFileName(value) | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |

 **Result:**



---



