---
title: "UsdSaveOptions"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

خيارات الحفظ لتنسيقات USD/USDZ.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | إنشاء كائن جديد من UsdSaveOptions بصيغة FileFormat.USD. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(fileFormat) | إنشاء كائن جديد من UsdSaveOptions بصيغة USD/USDZ المحددة. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| الاسم | الوصف |
| --- | --- |
| getPrimitiveToMesh() | تحويل الكيانات الأولية إلى شبكة أثناء التصدير. أو ترميز الكيانات الأولية مباشرةً إلى ملف الإخراج (سيتم استخدام تعريف امتداد Aspose للكيانات غير الرسمية مثل Dish و Torus). القيمة الافتراضية هي true. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| الاسم | الوصف |
| --- | --- |
| setPrimitiveToMesh(value) | تحويل الكيانات الأولية إلى شبكة أثناء التصدير. أو ترميز الكيانات الأولية مباشرةً إلى ملف الإخراج (سيتم استخدام تعريف امتداد Aspose للكيانات غير الرسمية مثل Dish و Torus). القيمة الافتراضية هي true. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| الاسم | الوصف |
| --- | --- |
| getExportMetaData() | تصدير خصائص العقدة عبر حقل customData الخاص بـ USD. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| الاسم | الوصف |
| --- | --- |
| setExportMetaData(value) | تصدير خصائص العقدة عبر حقل customData الخاص بـ USD. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| الاسم | الوصف |
| --- | --- |
| getMaterialConverter() | محول مخصص لتحويل مادة الهندسة إلى مادة PBR. إذا لم يتم تعيينه، سيقوم مُصدّر USD تلقائيًا بتحويل المادة القياسية إلى مادة PBR. القيمة الافتراضية هي null |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| الاسم | الوصف |
| --- | --- |
| setMaterialConverter(value) | محول مخصص لتحويل مادة الهندسة إلى مادة PBR. إذا لم يتم تعيينه، سيقوم مُصدّر USD تلقائيًا بتحويل المادة القياسية إلى مادة PBR. القيمة الافتراضية هي null |

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



