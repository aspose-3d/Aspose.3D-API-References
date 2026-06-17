---
title: "U3dSaveOptions"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/u3dsaveoptions/
---
## U3dSaveOptions class

Параметры сохранения для universal 3d


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Конструктор U3dSaveOptions |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Имя | Описание |
| --- | --- |
| getFlipCoordinateSystem() | Получает или задает, следует ли инвертировать систему координат контрольных точек/нормалей при импорте/экспорте. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Имя | Описание |
| --- | --- |
| setFlipCoordinateSystem(value) | Получает или задает, следует ли инвертировать систему координат контрольных точек/нормалей при импорте/экспорте. |

 **Result:**



---


### getMeshCompression{#getMeshCompression}

| Имя | Описание |
| --- | --- |
| getMeshCompression() | Получает или задает, следует ли включать сжатие данных сетки. |

 **Result:**



---


### setMeshCompression{#setMeshCompression}

| Имя | Описание |
| --- | --- |
| setMeshCompression(value) | Получает или задает, следует ли включать сжатие данных сетки. |

 **Result:**



---


### getExportNormals{#getExportNormals}

| Имя | Описание |
| --- | --- |
| getExportNormals() | Получает или задает, следует ли экспортировать данные нормалей. |

 **Result:**



---


### setExportNormals{#setExportNormals}

| Имя | Описание |
| --- | --- |
| setExportNormals(value) | Получает или задает, следует ли экспортировать данные нормалей. |

 **Result:**



---


### getExportTextureCoordinates{#getExportTextureCoordinates}

| Имя | Описание |
| --- | --- |
| getExportTextureCoordinates() | Получает или задает, следует ли экспортировать координаты текстур. |

 **Result:**



---


### setExportTextureCoordinates{#setExportTextureCoordinates}

| Имя | Описание |
| --- | --- |
| setExportTextureCoordinates(value) | Получает или задает, следует ли экспортировать координаты текстур. |

 **Result:**



---


### getExportVertexDiffuse{#getExportVertexDiffuse}

| Имя | Описание |
| --- | --- |
| getExportVertexDiffuse() | Получает или задает, экспортировать ли диффузный цвет вершины. |

 **Result:**



---


### setExportVertexDiffuse{#setExportVertexDiffuse}

| Имя | Описание |
| --- | --- |
| setExportVertexDiffuse(value) | Получает или задает, экспортировать ли диффузный цвет вершины. |

 **Result:**



---


### getExportVertexSpecular{#getExportVertexSpecular}

| Имя | Описание |
| --- | --- |
| getExportVertexSpecular() | Получает или задает, экспортировать ли зеркальный цвет вершины. |

 **Result:**



---


### setExportVertexSpecular{#setExportVertexSpecular}

| Имя | Описание |
| --- | --- |
| setExportVertexSpecular(value) | Получает или задает, экспортировать ли зеркальный цвет вершины. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Имя | Описание |
| --- | --- |
| getEmbedTextures() | Встраивает внешние текстуры в файл U3D, значение по умолчанию — false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Имя | Описание |
| --- | --- |
| setEmbedTextures(value) | Встраивает внешние текстуры в файл U3D, значение по умолчанию — false. |

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



