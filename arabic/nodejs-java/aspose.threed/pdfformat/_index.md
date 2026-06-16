---
title: "PdfFormat"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/pdfformat/
---
## PdfFormat class

تنسيق المستندات القابل للنقل من Adobe  @hideconstructor


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


### extract{#extract}

| الاسم | الوصف |
| --- | --- |
| extract(fileName, password) | استخراج المحتوى ثلاثي الأبعاد الخام من ملف PDF. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileNam | String | null |
| passwor | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### extractScene{#extractScene}

| الاسم | الوصف |
| --- | --- |
| extractScene(fileName) | استخراج المشاهد ثلاثية الأبعاد من ملف PDF. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### extractScene{#extractScene}

| الاسم | الوصف |
| --- | --- |
| extractScene(fileName, password) | استخراج المشاهد ثلاثية الأبعاد من ملف PDF. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileNam | String | null |
| passwor | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


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



