---
title: "PdfSaveOptions"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/pdfsaveoptions/
---
## PdfSaveOptions class

Параметры сохранения при экспорте PDF.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Конструктор PdfSaveOptions |

 **Result:**



---


### getRenderMode{#getRenderMode}

| Имя | Описание |
| --- | --- |
| getRenderMode() | Режим рендеринга указывает стиль, в котором отображается 3D‑рисунок. Значение свойства — целочисленная константа PdfRenderMode. |

 **Result:**



---


### setRenderMode{#setRenderMode}

| Имя | Описание |
| --- | --- |
| setRenderMode(value) | Режим рендеринга указывает стиль, в котором отображается 3D‑рисунок. Значение свойства — целочисленная константа PdfRenderMode. |

 **Result:**



---


### getLightingScheme{#getLightingScheme}

| Имя | Описание |
| --- | --- |
| getLightingScheme() | LightingScheme определяет освещение, применяемое к 3D‑рисунку. Значение свойства — целочисленная константа PdfLightingScheme. |

 **Result:**



---


### setLightingScheme{#setLightingScheme}

| Имя | Описание |
| --- | --- |
| setLightingScheme(value) | LightingScheme определяет освещение, применяемое к 3D‑рисунку. Значение свойства — целочисленная константа PdfLightingScheme. |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| Имя | Описание |
| --- | --- |
| getBackgroundColor() | Цвет фона 3D‑просмотра в PDF‑файле. |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| Имя | Описание |
| --- | --- |
| setBackgroundColor(value) | Цвет фона 3D‑просмотра в PDF‑файле. |

 **Result:**



---


### getFaceColor{#getFaceColor}

| Имя | Описание |
| --- | --- |
| getFaceColor() | Получает или задает цвет граней, используемый при рендеринге 3D‑контента. Это актуально только когда RenderMode имеет значение Illustration. |

 **Result:**



---


### setFaceColor{#setFaceColor}

| Имя | Описание |
| --- | --- |
| setFaceColor(value) | Получает или задает цвет граней, используемый при рендеринге 3D‑контента. Это актуально только когда RenderMode имеет значение Illustration. |

 **Result:**



---


### getAuxiliaryColor{#getAuxiliaryColor}

| Имя | Описание |
| --- | --- |
| getAuxiliaryColor() | Получает или задает вспомогательный цвет, используемый при рендеринге 3D‑контента. Интерпретация этого цвета зависит от RenderMode. |

 **Result:**



---


### setAuxiliaryColor{#setAuxiliaryColor}

| Имя | Описание |
| --- | --- |
| setAuxiliaryColor(value) | Получает или задает вспомогательный цвет, используемый при рендеринге 3D‑контента. Интерпретация этого цвета зависит от RenderMode. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Имя | Описание |
| --- | --- |
| getFlipCoordinateSystem() | Получает или задает переключение системы координат сцены при экспорте. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Имя | Описание |
| --- | --- |
| setFlipCoordinateSystem(value) | Получает или задает переключение системы координат сцены при экспорте. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Имя | Описание |
| --- | --- |
| getEmbedTextures() | Встраивать внешние текстуры в PDF‑файл, значение по умолчанию — false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Имя | Описание |
| --- | --- |
| setEmbedTextures(value) | Встраивать внешние текстуры в PDF‑файл, значение по умолчанию — false. |

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



