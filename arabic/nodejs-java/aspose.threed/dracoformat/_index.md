---
title: "DracoFormat"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

تنسيق Google Draco  @hideconstructor


## الطرق

### getVersion{#getVersion}

| الاسم | الوصف |
| --- | --- |
| getVersion() | يحصل على إصدار تنسيق الملف |

 **Result:**



---


### getExtension{#getExtension}

| الاسم | الوصف |
| --- | --- |
| getExtension() | يحصل على اسم الامتداد لهذا النوع. |

 **Result:**



---


### getExtensions{#getExtensions}

| الاسم | الوصف |
| --- | --- |
| getExtensions() | يحصل على أسماء الامتداد لهذا النوع. |

 **Result:**



---


### getContentType{#getContentType}

| الاسم | الوصف |
| --- | --- |
| getContentType() | يحصل على نوع محتوى تنسيق الملف. قيمة الخاصية هي ثابت عدد صحيح FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| الاسم | الوصف |
| --- | --- |
| getFileFormatType() | يحصل على نوع تنسيق الملف |

 **Result:**



---


### decode{#decode}

| الاسم | الوصف |
| --- | --- |
| decode(fileName) | فك تشفير سحابة النقاط أو الشبكة من اسم الملف المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف يحتوي على ملف drc |

 **Result:**
الهندسة


---


### decode{#decode}

| الاسم | الوصف |
| --- | --- |
| decode(data) | فك تشفير سحابة النقاط أو الشبكة من بيانات الذاكرة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| data | byte[] | البتات الخام لملف drc |

 **Result:**
الهندسة


---


### encode{#encode}

| الاسم | الوصف |
| --- | --- |
| encode(entity, fileName, options) | تشفير الكيان إلى الملف المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان المراد تشفيره |
| fileName | String | اسم الملف الذي سيُكتب |
| الخيارات | DracoSaveOptions | خيارات إضافية لتشفير سحابة النقاط |

 **Result:**
الهندسة


---


### encode{#encode}

| الاسم | الوصف |
| --- | --- |
| encode(entity, options) | تشفير الكيان إلى بيانات Draco الخام |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان المراد تشفيره |
| الخيارات | DracoSaveOptions | خيارات إضافية لتشفير سحابة النقاط |

 **Result:**
byte[]


---


### createLoadOptions{#createLoadOptions}

| الاسم | الوصف |
| --- | --- |
| createLoadOptions() | إنشاء خيارات تحميل افتراضية لهذا تنسيق الملف |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| الاسم | الوصف |
| --- | --- |
| createSaveOptions() | إنشاء خيارات حفظ افتراضية لهذا تنسيق الملف |

 **Result:**
SaveOptions


---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() | تحويل التنسيقات إلى سلسلة |

 **Result:**
String


---



