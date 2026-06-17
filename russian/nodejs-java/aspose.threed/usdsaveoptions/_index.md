---
title: "UsdSaveOptions"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

Сохранить параметры для форматов USD/USDZ.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый объект UsdSaveOptions с форматом FileFormat.USD. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(fileFormat) | Инициализирует новый объект UsdSaveOptions с указанным форматом USD/USDZ. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| Имя | Описание |
| --- | --- |
| getPrimitiveToMesh() | Преобразует примитивные сущности в сетку во время экспорта. Или напрямую кодирует примитивы в выходной файл (будет использовано определение расширения Aspose для неофициальных примитивов, таких как Dish, Torus). Значение по умолчанию — true. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| Имя | Описание |
| --- | --- |
| setPrimitiveToMesh(value) | Преобразует примитивные сущности в сетку во время экспорта. Или напрямую кодирует примитивы в выходной файл (будет использовано определение расширения Aspose для неофициальных примитивов, таких как Dish, Torus). Значение по умолчанию — true. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| Имя | Описание |
| --- | --- |
| getExportMetaData() | Экспортирует свойства узла через поле customData формата USD. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| Имя | Описание |
| --- | --- |
| setExportMetaData(value) | Экспортирует свойства узла через поле customData формата USD. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Имя | Описание |
| --- | --- |
| getMaterialConverter() | Пользовательский конвертер для преобразования материала геометрии в материал PBR. Если он не назначен, экспортёр USD автоматически преобразует стандартный материал в материал PBR. Значение по умолчанию — null |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Имя | Описание |
| --- | --- |
| setMaterialConverter(value) | Пользовательский конвертер для преобразования материала геометрии в материал PBR. Если он не назначен, экспортёр USD автоматически преобразует стандартный материал в материал PBR. Значение по умолчанию — null |

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



