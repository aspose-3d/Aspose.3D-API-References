---
title: "PlyFormat"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

Формат PLY.  @hideconstructor


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


### encode{#encode}

| Имя | Описание |
| --- | --- |
| encode(entity, fileName) | Закодируйте сущность и сохраните результат во внешний файл. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| entity | Entity | Сущность для кодирования |
| fileName | String | Файл для записи |

 **Result:**



---


### encode{#encode}

| Имя | Описание |
| --- | --- |
| encode(entity, fileName, opt) | Закодируйте сущность и сохраните результат во внешний файл. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| entity | Entity | Сущность для кодирования |
| fileName | String | Файл для записи |
| opt | PlySaveOptions | Параметры сохранения |

 **Result:**



---


### decode{#decode}

| Имя | Описание |
| --- | --- |
| decode(fileName) | Декодировать облако точек или сетку из указанного потока. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileName | String | Входной поток |

 **Result:**
Геометрия


---


### decode{#decode}

| Имя | Описание |
| --- | --- |
| decode(fileName, opt) | Декодировать облако точек или сетку из указанного потока. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileName | String | Входной поток |
| opt | PlyLoadOptions | Параметр загрузки формата PLY |

 **Result:**
Геометрия


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



