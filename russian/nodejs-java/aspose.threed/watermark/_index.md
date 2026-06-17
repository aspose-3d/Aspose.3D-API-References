---
title: "Watermark"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/watermark/
---
## Watermark class

Утилита для кодирования/декодирования слепой водяной метки в/из сетки.  @hideconstructor


## Методы

### encodeWatermark{#encodeWatermark}

| Имя | Описание |
| --- | --- |
| encodeWatermark(input, text) | Кодирует текст в слепую водяную метку сетки. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| input | Сетка | Сетка для кодирования слепой водяной метки. |
| text | String | Текст для кодирования в сетку. |

 **Result:**
Сетка


---


### encodeWatermark{#encodeWatermark}

| Имя | Описание |
| --- | --- |
| encodeWatermark(input, text, password) | Кодирует текст в слепую водяную метку сетки. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| input | Сетка | Сетка для кодирования слепой водяной метки. |
| text | String | Текст для кодирования в сетку. |
| password | String | Пароль для защиты водяной метки, необязателен. |

 **Result:**
Сетка


---


### decodeWatermark{#decodeWatermark}

| Имя | Описание |
| --- | --- |
| decodeWatermark(input) | Декодировать водяную метку из сетки. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| input | Сетка | Сетка для извлечения водяной метки. |

 **Result:**
String


---


### decodeWatermark{#decodeWatermark}

| Имя | Описание |
| --- | --- |
| decodeWatermark(input, password) | Декодировать водяную метку из сетки. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| input | Сетка | Сетка для извлечения водяной метки. |
| password | String | Пароль для расшифровки водяной метки. |

 **Result:**
String


---



