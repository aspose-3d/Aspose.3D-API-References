---
title: "PlySaveOptions"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

Параметры сохранения при экспорте сцены в файл PLY.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Конструктор PlySaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(contentType) | Конструктор PlySaveOptions |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getPointCloud{#getPointCloud}

| Имя | Описание |
| --- | --- |
| getPointCloud() | Экспортировать сцену как облако точек, значение по умолчанию — false. |

 **Result:**



---


### setPointCloud{#setPointCloud}

| Имя | Описание |
| --- | --- |
| setPointCloud(value) | Экспортировать сцену как облако точек, значение по умолчанию — false. |

 **Result:**



---


### getFlipCoordinate{#getFlipCoordinate}

| Имя | Описание |
| --- | --- |
| getFlipCoordinate() | Отразить координату при сохранении сцены, значение по умолчанию — true. |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| Имя | Описание |
| --- | --- |
| setFlipCoordinate(value) | Отразить координату при сохранении сцены, значение по умолчанию — true. |

 **Result:**



---


### getVertexElement{#getVertexElement}

| Имя | Описание |
| --- | --- |
| getVertexElement() | Имя элемента для данных вершины, значение по умолчанию — "vertex". |

 **Result:**



---


### setVertexElement{#setVertexElement}

| Имя | Описание |
| --- | --- |
| setVertexElement(value) | Имя элемента для данных вершины, значение по умолчанию — "vertex". |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| Имя | Описание |
| --- | --- |
| getPositionComponents() | Имена компонентов для данных позиции, значение по умолчанию — ("x", "y", "z"). |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| Имя | Описание |
| --- | --- |
| getNormalComponents() | Имена компонентов для данных нормали, значение по умолчанию — ("nx", "ny", "nz"). |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| Имя | Описание |
| --- | --- |
| getTextureCoordinateComponents() | Имена компонентов данных координат текстуры, значение по умолчанию — ("u", "v") |

 **Result:**



---


### getColorComponents{#getColorComponents}

| Имя | Описание |
| --- | --- |
| getColorComponents() | Имена компонентов цвета вершины, значение по умолчанию — ("red", "green", "blue") |

 **Result:**



---


### getFaceElement{#getFaceElement}

| Имя | Описание |
| --- | --- |
| getFaceElement() | Имя элемента данных грани, значение по умолчанию — "face" |

 **Result:**



---


### setFaceElement{#setFaceElement}

| Имя | Описание |
| --- | --- |
| setFaceElement(value) | Имя элемента данных грани, значение по умолчанию — "face" |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| Имя | Описание |
| --- | --- |
| getFaceProperty() | Имя свойства данных грани, значение по умолчанию — "vertex_index" |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| Имя | Описание |
| --- | --- |
| setFaceProperty(value) | Имя свойства данных грани, значение по умолчанию — "vertex_index" |

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



