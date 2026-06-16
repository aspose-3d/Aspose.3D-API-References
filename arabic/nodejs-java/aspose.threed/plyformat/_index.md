---
title: "PlyFormat"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

تنسيق PLY.  @hideconstructor


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


### encode{#encode}

| الاسم | الوصف |
| --- | --- |
| encode(entity, fileName) | قم بترميز الكيان وحفظ النتيجة في ملف خارجي. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان المراد ترميزه |
| fileName | String | الملف الذي سيتم الكتابة إليه |

 **Result:**



---


### encode{#encode}

| الاسم | الوصف |
| --- | --- |
| encode(entity, fileName, opt) | قم بترميز الكيان وحفظ النتيجة في ملف خارجي. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان المراد ترميزه |
| fileName | String | الملف الذي سيتم الكتابة إليه |
| opt | PlySaveOptions | خيارات الحفظ |

 **Result:**



---


### decode{#decode}

| الاسم | الوصف |
| --- | --- |
| decode(fileName) | قم بفك ترميز سحابة النقاط أو الشبكة من الدفق المحدد. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileName | String | دفق الإدخال |

 **Result:**
الهندسة


---


### decode{#decode}

| الاسم | الوصف |
| --- | --- |
| decode(fileName, opt) | قم بفك ترميز سحابة النقاط أو الشبكة من الدفق المحدد. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileName | String | دفق الإدخال |
| opt | PlyLoadOptions | خيار التحميل لتنسيق PLY |

 **Result:**
الهندسة


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



