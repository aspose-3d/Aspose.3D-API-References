---
title: "ZipArchiveFileSystem"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/ziparchivefilesystem/
---
## ZipArchiveFileSystem class

نظام ملفات لتوفير الوصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(fileName) | أنشئ ZipArchiveFileSystem باستخدام اسم ملف. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**



---


### readFile{#readFile}

| الاسم | الوصف |
| --- | --- |
| readFile(fileName, options) | افتح الملف للقراءة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileNam | String | null |
| خيار | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| الاسم | الوصف |
| --- | --- |
| writeFile(fileName, options) | افتح الملف للكتابة، غير مُنفّذ في هذه الفئة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileNam | String | null |
| خيار | IOConfig | null |

 **Result:**
Stream


---



