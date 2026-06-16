---
title: "MemoryFileSystem"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

سيقوم MemoryFileSystem بربط عمليات القراءة/الكتابة بالذاكرة.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| الاسم | الوصف |
| --- | --- |
| getFileNames() | أسماء الملفات الموجودة في نظام الملفات الذاكرة هذا. |

 **Result:**



---


### getFileContent{#getFileContent}

| الاسم | الوصف |
| --- | --- |
| getFileContent(fileName) | يرجع المحتوى الخام للملف المحدد. يطرح System.IO.FileNotFoundException إذا لم يكن الملف المحدد موجودًا. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| الاسم | الوصف |
| --- | --- |
| readFile(fileName, options) | إنشاء تدفق لقراءة التبعيات. |

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
| writeFile(fileName, options) | إنشاء تدفق لكتابة التبعيات. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileNam | String | null |
| خيار | IOConfig | null |

 **Result:**
Stream


---



