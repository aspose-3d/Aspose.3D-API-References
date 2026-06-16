---
title: "Watermark"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/watermark/
---
## Watermark class

أداة لتشفير/فك تشفير العلامة المائية العمياء إلى/من شبكة. @hideconstructor


## الطرق

### encodeWatermark{#encodeWatermark}

| الاسم | الوصف |
| --- | --- |
| encodeWatermark(input, text) | ترميز نص إلى علامة مائية عمياء في الشبكة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| input | شبكة | شبكة لتشفير علامة مائية عمياء |
| text | String | نص لتشفيره في الشبكة |

 **Result:**
شبكة


---


### encodeWatermark{#encodeWatermark}

| الاسم | الوصف |
| --- | --- |
| encodeWatermark(input, text, password) | ترميز نص إلى علامة مائية عمياء في الشبكة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| input | شبكة | شبكة لتشفير علامة مائية عمياء |
| text | String | نص لتشفيره في الشبكة |
| password | String | كلمة مرور لحماية العلامة المائية، وهي اختيارية |

 **Result:**
شبكة


---


### decodeWatermark{#decodeWatermark}

| الاسم | الوصف |
| --- | --- |
| decodeWatermark(input) | فك تشفير العلامة المائية من شبكة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| input | شبكة | الشبكة لاستخراج العلامة المائية |

 **Result:**
String


---


### decodeWatermark{#decodeWatermark}

| الاسم | الوصف |
| --- | --- |
| decodeWatermark(input, password) | فك تشفير العلامة المائية من شبكة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| input | شبكة | الشبكة لاستخراج العلامة المائية |
| password | String | كلمة المرور لفك تشفير العلامة المائية |

 **Result:**
String


---



