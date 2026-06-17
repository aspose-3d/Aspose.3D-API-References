---
title: "StlLoadOptions"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/stlloadoptions/
---
## StlLoadOptions class

Параметры загрузки для STL


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый экземпляр StlLoadOptions. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(contentType) | Инициализирует новый экземпляр StlLoadOptions. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Имя | Описание |
| --- | --- |
| getFlipCoordinateSystem() | Получает или задает, следует ли инвертировать систему координат контрольных точек/нормалей при импорте. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Имя | Описание |
| --- | --- |
| setFlipCoordinateSystem(value) | Получает или задает, следует ли инвертировать систему координат контрольных точек/нормалей при импорте. |

 **Result:**



---


### getRecalculateNormal{#getRecalculateNormal}

| Имя | Описание |
| --- | --- |
| getRecalculateNormal() | Игнорировать данные нормалей, хранящиеся в файле STL, и пересчитать данные нормалей на основе положения вершин. Значение по умолчанию — false. |

 **Result:**



---


### setRecalculateNormal{#setRecalculateNormal}

| Имя | Описание |
| --- | --- |
| setRecalculateNormal(value) | Игнорировать данные нормалей, хранящиеся в файле STL, и пересчитать данные нормалей на основе положения вершин. Значение по умолчанию — false. |

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



