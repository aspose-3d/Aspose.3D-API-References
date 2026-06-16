---
title: "RvmSaveOptions"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

خيارات الحفظ لملف RVM الخاص بـ Aveva PDMS.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | منشئ RvmSaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(contentType) | منشئ RvmSaveOptions |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| الاسم | الوصف |
| --- | --- |
| getFileNote() | ملاحظة الملف في رأس الملف. |

 **Result:**



---


### setFileNote{#setFileNote}

| الاسم | الوصف |
| --- | --- |
| setFileNote(value) | ملاحظة الملف في رأس الملف. |

 **Result:**



---


### getAuthor{#getAuthor}

| الاسم | الوصف |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| الاسم | الوصف |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| الاسم | الوصف |
| --- | --- |
| getCreationTime() | الطابع الزمني الذي صدر هذا الملف، القيمة الافتراضية هي الوقت الحالي. |

 **Result:**



---


### setCreationTime{#setCreationTime}

| الاسم | الوصف |
| --- | --- |
| setCreationTime(value) | الطابع الزمني الذي صدر هذا الملف، القيمة الافتراضية هي الوقت الحالي. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| الاسم | الوصف |
| --- | --- |
| getAttributePrefix() | يحصل أو يحدد البادئة للسمات التي سيتم تصديرها، الخاصية المصدرة لن تحتوي على بادئة، الخصائص المخصصة ذات البادئة المختلفة لن تُصدر، القيمة الافتراضية هي 'rvm:'. على سبيل المثال إذا كانت الخاصية rvm:Refno=345، فإن السمة المصدرة ستكون Refno = 345، تُزال البادئة. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| الاسم | الوصف |
| --- | --- |
| setAttributePrefix(value) | يحصل أو يحدد البادئة للسمات التي سيتم تصديرها، الخاصية المصدرة لن تحتوي على بادئة، الخصائص المخصصة ذات البادئة المختلفة لن تُصدر، القيمة الافتراضية هي 'rvm:'. على سبيل المثال إذا كانت الخاصية rvm:Refno=345، فإن السمة المصدرة ستكون Refno = 345، تُزال البادئة. |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| الاسم | الوصف |
| --- | --- |
| getAttributeListFile() | يحصل أو يضبط اسم ملف قائمة السمات، سيولد المصدّر اسمًا بناءً على اسم ملف .rvm عندما تكون هذه الخاصية غير معرفة، القيمة الافتراضية هي null. |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| الاسم | الوصف |
| --- | --- |
| setAttributeListFile(value) | يحصل أو يضبط اسم ملف قائمة السمات، سيولد المصدّر اسمًا بناءً على اسم ملف .rvm عندما تكون هذه الخاصية غير معرفة، القيمة الافتراضية هي null. |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| الاسم | الوصف |
| --- | --- |
| getExportAttributes() | يحصل أو يضبط ما إذا كان سيتم تصدير قائمة السمات إلى ملف .att خارجي، القيمة الافتراضية هي false. |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| الاسم | الوصف |
| --- | --- |
| setExportAttributes(value) | يحصل أو يضبط ما إذا كان سيتم تصدير قائمة السمات إلى ملف .att خارجي، القيمة الافتراضية هي false. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| الاسم | الوصف |
| --- | --- |
| getExportTextures() | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| الاسم | الوصف |
| --- | --- |
| setExportTextures(value) | حاول نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| الاسم | الوصف |
| --- | --- |
| getFileFormat() | يسترجع تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |

 **Result:**



---


### getEncoding{#getEncoding}

| الاسم | الوصف |
| --- | --- |
| getEncoding() | يسترجع أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يُستخدم. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| الاسم | الوصف |
| --- | --- |
| getFileSystem() | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| الاسم | الوصف |
| --- | --- |
| setFileSystem(value) | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| الاسم | الوصف |
| --- | --- |
| getLookupPaths() | بعض الملفات مثل OBJ تعتمد على ملفات خارجية، مسارات البحث تسمح لـ Aspose.3D بالبحث عن الملف الخارجي لتحميله. |

 **Result:**



---


### getFileName{#getFileName}

| الاسم | الوصف |
| --- | --- |
| getFileName() | اسم ملف المشهد المستورد/المصدر. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| الاسم | الوصف |
| --- | --- |
| setFileName(value) | اسم ملف المشهد المستورد/المصدر. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |

 **Result:**



---



