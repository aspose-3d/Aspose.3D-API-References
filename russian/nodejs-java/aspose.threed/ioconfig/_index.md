---
title: "IOConfig"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/ioconfig/
---
## IOConfig class

Конфигурация ввода-вывода для сериализации/десериализации.  Пользователь может указать детальные настройки, такие как путь поиска зависимостей, или настройки, связанные с форматом, здесь  @hideconstructor


## Методы

### getFileSystemFactory{#getFileSystemFactory}

| Имя | Описание |
| --- | --- |
| getFileSystemFactory() | Получает или задает класс фабрики для FileSystem. Фабрика по умолчанию создаёт LocalFileSystem, который не подходит для серверной среды. |

 **Result:**



---


### setFileSystemFactory{#setFileSystemFactory}

| Имя | Описание |
| --- | --- |
| setFileSystemFactory(value) | Получает или задает класс фабрики для FileSystem. Фабрика по умолчанию создаёт LocalFileSystem, который не подходит для серверной среды. |

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



