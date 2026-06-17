---
title: "FileFormat"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Определение формата файла  @hideconstructor


## Свойства

| Имя | Описание |
| --- | --- |
| MAYA_BINARY | Autodesk Maya в бинарном формате |
| STL_BINARY | Бинарный формат файла STL |
| STLASCII | Формат файла ASCII STL |
| COLLADA | Формат файла Collada |
| GLTF | glTF группы Khronos |
| GLTF_BINARY | glTF группы Khronos в бинарном формате |
| PDF | Портативный формат документа Adobe |
| DXF | AutoCAD DXF |
| PLY | Формат файлов Polygon или Stanford Triangle Format |
| X_BINARY | Файл X DirectX в бинарном формате |
| X_TEXT | Файл X DirectX в бинарном формате |
| DRACO | Google Draco сетка |
| RVM_TEXT | Модель системы управления проектированием AVEVA Plant Design Management System в текстовом формате |
| RVM_BINARY | Модель системы управления проектированием AVEVA Plant Design Management System в бинарном формате |
| ASE | Формат ASCII-экспортера сцен 3D Studio Max. |
| IFC | Модель данных ISO 16739-1 Industry Foundation Classes. |
| AMF | Формат файла аддитивного производства |
| VRML | Язык моделирования виртуальной реальности |
| ZIP | ZIP-архив, содержащий другие 3D-форматы файлов. |
| USD | Универсальное описание сцены |
| USDZ | Сжатое универсальное описание сцены |
| XYZ | Файл облака точек XYZ |
| PCD | Файл данных облака точек PCL в режиме ASCII |
| PCD_BINARY | Файл данных облака точек PCL в бинарном режиме |

## Методы

### getVersion{#getVersion}

| Имя | Описание |
| --- | --- |
| getVersion() | Получает версию формата файла |

 **Result:**



---


### getExtension{#getExtension}

| Имя | Описание |
| --- | --- |
| getExtension() | Получает имя расширения этого типа. |

 **Result:**



---


### getExtensions{#getExtensions}

| Имя | Описание |
| --- | --- |
| getExtensions() | Получает имена расширений этого типа. |

 **Result:**



---


### getContentType{#getContentType}

| Имя | Описание |
| --- | --- |
| getContentType() | Получает тип содержимого формата файла. Значение свойства — целочисленная константа FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Имя | Описание |
| --- | --- |
| getFileFormatType() | Получает тип формата файла |

 **Result:**



---


### getFormatByExtension{#getFormatByExtension}

| Имя | Описание |
| --- | --- |
| getFormatByExtension(extensionName) | Получает предпочтительный формат файла по имени расширения. Имя расширения должно начинаться с точки ('.'). |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| extensionNam | String | null |

 **Result:**
FileFormat


---


### detect{#detect}

| Имя | Описание |
| --- | --- |
| detect(fileName) | Определяет формат файла по имени файла, файл должен быть доступен для чтения, чтобы Aspose.3D мог определить формат файла по заголовку. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
FileFormat


---


### createLoadOptions{#createLoadOptions}

| Имя | Описание |
| --- | --- |
| createLoadOptions() | Создает параметры загрузки по умолчанию для этого формата файла |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Имя | Описание |
| --- | --- |
| createSaveOptions() | Создает параметры сохранения по умолчанию для этого формата файла |

 **Result:**
SaveOptions


---


### toString{#toString}

| Имя | Описание |
| --- | --- |
| toString() | Форматы в строку |

 **Result:**
String


---



