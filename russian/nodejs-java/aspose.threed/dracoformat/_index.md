---
title: "DracoFormat"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Формат Google Draco  @hideconstructor


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


### decode{#decode}

| Имя | Описание |
| --- | --- |
| decode(fileName) | Декодировать облако точек или сетку из указанного имени файла |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла содержит файл drc |

 **Result:**
Геометрия


---


### decode{#decode}

| Имя | Описание |
| --- | --- |
| decode(data) | Декодировать облако точек или сетку из данных в памяти |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| data | byte[] | Необработанные байты drc |

 **Result:**
Геометрия


---


### encode{#encode}

| Имя | Описание |
| --- | --- |
| encode(entity, fileName, options) | Кодировать объект в указанный файл |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| entity | Entity | Объект для кодирования |
| fileName | String | Имя файла для записи |
| опции | DracoSaveOptions | Дополнительные параметры для кодирования облака точек |

 **Result:**
Геометрия


---


### encode{#encode}

| Имя | Описание |
| --- | --- |
| encode(entity, options) | Кодировать объект в необработанные данные Draco |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| entity | Entity | Объект для кодирования |
| опции | DracoSaveOptions | Дополнительные параметры для кодирования облака точек |

 **Result:**
byte[]


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



