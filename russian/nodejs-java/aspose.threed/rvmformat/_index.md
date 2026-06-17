---
title: "RvmFormat"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/rvmformat/
---
## RvmFormat class

Формат RVM  @hideconstructor


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


### loadAttributes{#loadAttributes}

| Имя | Описание |
| --- | --- |
| loadAttributes(scene, fileName, prefix) | Загрузить атрибуты из указанного имени файла |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| сцена | Scene | Сцена, к которой будут применены атрибуты |
| fileName | String | Имя файла, содержащего атрибуты |
| prefix | String | Префикс атрибутов, используемый для избежания конфликтов имён, значение по умолчанию — "rvm:" |

 **Result:**



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



