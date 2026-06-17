---
title: "DracoSaveOptions"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/dracosaveoptions/
---
## DracoSaveOptions class

Параметры сохранения для файлов Google Draco


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Создать конфигурацию по умолчанию для сохранения файлов draco. |

 **Result:**



---


### getPositionBits{#getPositionBits}

| Имя | Описание |
| --- | --- |
| getPositionBits() | Биты квантизации для позиции, значение по умолчанию — 14 |

 **Result:**



---


### setPositionBits{#setPositionBits}

| Имя | Описание |
| --- | --- |
| setPositionBits(value) | Биты квантизации для позиции, значение по умолчанию — 14 |

 **Result:**



---


### getTextureCoordinateBits{#getTextureCoordinateBits}

| Имя | Описание |
| --- | --- |
| getTextureCoordinateBits() | Биты квантизации для текстурных координат, значение по умолчанию — 12 |

 **Result:**



---


### setTextureCoordinateBits{#setTextureCoordinateBits}

| Имя | Описание |
| --- | --- |
| setTextureCoordinateBits(value) | Биты квантизации для текстурных координат, значение по умолчанию — 12 |

 **Result:**



---


### getColorBits{#getColorBits}

| Имя | Описание |
| --- | --- |
| getColorBits() | Биты квантизации для цвета вершин, значение по умолчанию — 10 |

 **Result:**



---


### setColorBits{#setColorBits}

| Имя | Описание |
| --- | --- |
| setColorBits(value) | Биты квантизации для цвета вершин, значение по умолчанию — 10 |

 **Result:**



---


### getNormalBits{#getNormalBits}

| Имя | Описание |
| --- | --- |
| getNormalBits() | Биты квантизации для нормальных векторов, значение по умолчанию — 10 |

 **Result:**



---


### setNormalBits{#setNormalBits}

| Имя | Описание |
| --- | --- |
| setNormalBits(value) | Биты квантизации для нормальных векторов, значение по умолчанию — 10 |

 **Result:**



---


### getCompressionLevel{#getCompressionLevel}

| Имя | Описание |
| --- | --- |
| getCompressionLevel() | Уровень сжатия, значение по умолчанию — DracoCompressionLevel.STANDARD. Значение свойства — целая константа DracoCompressionLevel. |

 **Result:**



---


### setCompressionLevel{#setCompressionLevel}

| Имя | Описание |
| --- | --- |
| setCompressionLevel(value) | Уровень сжатия, значение по умолчанию — DracoCompressionLevel.STANDARD. Значение свойства — целая константа DracoCompressionLevel. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| Имя | Описание |
| --- | --- |
| getApplyUnitScale() | Применить AssetInfo.UnitScaleFactor к сетке. Значение по умолчанию — false. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| Имя | Описание |
| --- | --- |
| setApplyUnitScale(value) | Применить AssetInfo.UnitScaleFactor к сетке. Значение по умолчанию — false. |

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



