---
title: "PdfFormat"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/pdfformat/
---
## PdfFormat class

Portable Document Format от Adobe  @hideconstructor


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


### extract{#extract}

| Имя | Описание |
| --- | --- |
| extract(fileName, password) | Извлечь необработанное 3D‑содержимое из PDF‑файла. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileNam | String | null |
| passwor | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### extractScene{#extractScene}

| Имя | Описание |
| --- | --- |
| extractScene(fileName) | Извлечь 3D‑сцены из PDF‑файла. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### extractScene{#extractScene}

| Имя | Описание |
| --- | --- |
| extractScene(fileName, password) | Извлечь 3D‑сцены из PDF‑файла. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileNam | String | null |
| passwor | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


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



