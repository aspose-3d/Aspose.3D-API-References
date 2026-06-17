---
title: "RvmLoadOptions"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/rvmloadoptions/
---
## RvmLoadOptions class

Параметры загрузки RVM‑файла системы AVEVA Plant Design Management System.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(contentType) | Создайте экземпляр RvmLoadOptions |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload() | Создайте экземпляр RvmLoadOptions |

 **Result:**



---


### getGenerateMaterials{#getGenerateMaterials}

| Имя | Описание |
| --- | --- |
| getGenerateMaterials() | Генерировать материалы со случайными цветами для каждого объекта в сцене, если таблица цветов не экспортирована в файле RVM. Значение по умолчанию — true. |

 **Result:**



---


### setGenerateMaterials{#setGenerateMaterials}

| Имя | Описание |
| --- | --- |
| setGenerateMaterials(value) | Генерировать материалы со случайными цветами для каждого объекта в сцене, если таблица цветов не экспортирована в файле RVM. Значение по умолчанию — true. |

 **Result:**



---


### getCylinderRadialSegments{#getCylinderRadialSegments}

| Имя | Описание |
| --- | --- |
| getCylinderRadialSegments() | Получает или задает количество радиальных сегментов цилиндра, значение по умолчанию — 16. |

 **Result:**



---


### setCylinderRadialSegments{#setCylinderRadialSegments}

| Имя | Описание |
| --- | --- |
| setCylinderRadialSegments(value) | Получает или задает количество радиальных сегментов цилиндра, значение по умолчанию — 16. |

 **Result:**



---


### getDishLongitudeSegments{#getDishLongitudeSegments}

| Имя | Описание |
| --- | --- |
| getDishLongitudeSegments() | Получает или задает количество долготных сегментов тарелки, значение по умолчанию — 12. |

 **Result:**



---


### setDishLongitudeSegments{#setDishLongitudeSegments}

| Имя | Описание |
| --- | --- |
| setDishLongitudeSegments(value) | Получает или задает количество долготных сегментов тарелки, значение по умолчанию — 12. |

 **Result:**



---


### getDishLatitudeSegments{#getDishLatitudeSegments}

| Имя | Описание |
| --- | --- |
| getDishLatitudeSegments() | Получает или задает количество широтных сегментов тарелки, значение по умолчанию — 8. |

 **Result:**



---


### setDishLatitudeSegments{#setDishLatitudeSegments}

| Имя | Описание |
| --- | --- |
| setDishLatitudeSegments(value) | Получает или задает количество широтных сегментов тарелки, значение по умолчанию — 8. |

 **Result:**



---


### getTorusTubularSegments{#getTorusTubularSegments}

| Имя | Описание |
| --- | --- |
| getTorusTubularSegments() | Получает или задает количество трубчатых сегментов тора, значение по умолчанию — 20. |

 **Result:**



---


### setTorusTubularSegments{#setTorusTubularSegments}

| Имя | Описание |
| --- | --- |
| setTorusTubularSegments(value) | Получает или задает количество трубчатых сегментов тора, значение по умолчанию — 20. |

 **Result:**



---


### getRectangularTorusSegments{#getRectangularTorusSegments}

| Имя | Описание |
| --- | --- |
| getRectangularTorusSegments() | Получает или задает количество радиальных сегментов прямоугольного тора, значение по умолчанию — 20. |

 **Result:**



---


### setRectangularTorusSegments{#setRectangularTorusSegments}

| Имя | Описание |
| --- | --- |
| setRectangularTorusSegments(value) | Получает или задает количество радиальных сегментов прямоугольного тора, значение по умолчанию — 20. |

 **Result:**



---


### getCenterScene{#getCenterScene}

| Имя | Описание |
| --- | --- |
| getCenterScene() | Центрировать сцену после её загрузки. |

 **Result:**



---


### setCenterScene{#setCenterScene}

| Имя | Описание |
| --- | --- |
| setCenterScene(value) | Центрировать сцену после её загрузки. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Имя | Описание |
| --- | --- |
| getAttributePrefix() | Получает или задает префикс атрибутов, определённых во внешних файлах атрибутов, префикс используется для избежания конфликтов имён, значение по умолчанию — "rvm:" |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Имя | Описание |
| --- | --- |
| setAttributePrefix(value) | Получает или задает префикс атрибутов, определённых во внешних файлах атрибутов, префикс используется для избежания конфликтов имён, значение по умолчанию — "rvm:" |

 **Result:**



---


### getLookupAttributes{#getLookupAttributes}

| Имя | Описание |
| --- | --- |
| getLookupAttributes() | Получает или задает, следует ли загружать атрибуты из внешнего файла списка атрибутов (.att/.attrib/.txt), значение по умолчанию — true. |

 **Result:**



---


### setLookupAttributes{#setLookupAttributes}

| Имя | Описание |
| --- | --- |
| setLookupAttributes(value) | Получает или задает, следует ли загружать атрибуты из внешнего файла списка атрибутов (.att/.attrib/.txt), значение по умолчанию — true. |

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



