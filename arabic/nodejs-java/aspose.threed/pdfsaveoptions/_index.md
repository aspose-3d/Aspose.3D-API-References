---
title: "PdfSaveOptions"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/pdfsaveoptions/
---
## PdfSaveOptions class

خيارات الحفظ عند تصدير PDF.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | منشئ PdfSaveOptions |

 **Result:**



---


### getRenderMode{#getRenderMode}

| الاسم | الوصف |
| --- | --- |
| getRenderMode() | وضع العرض يحدد النمط الذي يتم فيه عرض العمل ثلاثي الأبعاد. قيمة الخاصية هي ثابت عدد صحيح PdfRenderMode. |

 **Result:**



---


### setRenderMode{#setRenderMode}

| الاسم | الوصف |
| --- | --- |
| setRenderMode(value) | وضع العرض يحدد النمط الذي يتم فيه عرض العمل ثلاثي الأبعاد. قيمة الخاصية هي ثابت عدد صحيح PdfRenderMode. |

 **Result:**



---


### getLightingScheme{#getLightingScheme}

| الاسم | الوصف |
| --- | --- |
| getLightingScheme() | يحدد LightingScheme الإضاءة التي تُطبق على العمل ثلاثي الأبعاد. قيمة الخاصية هي ثابت عدد صحيح PdfLightingScheme. |

 **Result:**



---


### setLightingScheme{#setLightingScheme}

| الاسم | الوصف |
| --- | --- |
| setLightingScheme(value) | يحدد LightingScheme الإضاءة التي تُطبق على العمل ثلاثي الأبعاد. قيمة الخاصية هي ثابت عدد صحيح PdfLightingScheme. |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| الاسم | الوصف |
| --- | --- |
| getBackgroundColor() | لون الخلفية للعرض ثلاثي الأبعاد في ملف PDF. |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| الاسم | الوصف |
| --- | --- |
| setBackgroundColor(value) | لون الخلفية للعرض ثلاثي الأبعاد في ملف PDF. |

 **Result:**



---


### getFaceColor{#getFaceColor}

| الاسم | الوصف |
| --- | --- |
| getFaceColor() | يحصل أو يضبط لون الوجه الذي يُستخدم عند عرض المحتوى ثلاثي الأبعاد. هذا يكون ذا صلة فقط عندما يكون RenderMode له قيمة Illustration. |

 **Result:**



---


### setFaceColor{#setFaceColor}

| الاسم | الوصف |
| --- | --- |
| setFaceColor(value) | يحصل أو يضبط لون الوجه الذي يُستخدم عند عرض المحتوى ثلاثي الأبعاد. هذا يكون ذا صلة فقط عندما يكون RenderMode له قيمة Illustration. |

 **Result:**



---


### getAuxiliaryColor{#getAuxiliaryColor}

| الاسم | الوصف |
| --- | --- |
| getAuxiliaryColor() | يحصل أو يضبط اللون المساعد الذي يُستخدم عند عرض المحتوى ثلاثي الأبعاد. تفسير هذا اللون يعتمد على RenderMode. |

 **Result:**



---


### setAuxiliaryColor{#setAuxiliaryColor}

| الاسم | الوصف |
| --- | --- |
| setAuxiliaryColor(value) | يحصل أو يضبط اللون المساعد الذي يُستخدم عند عرض المحتوى ثلاثي الأبعاد. تفسير هذا اللون يعتمد على RenderMode. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| الاسم | الوصف |
| --- | --- |
| getFlipCoordinateSystem() | يحصل أو يضبط لعكس نظام إحداثيات المشهد أثناء التصدير. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| الاسم | الوصف |
| --- | --- |
| setFlipCoordinateSystem(value) | يحصل أو يضبط لعكس نظام إحداثيات المشهد أثناء التصدير. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| الاسم | الوصف |
| --- | --- |
| getEmbedTextures() | دمج القوام الخارجية في ملف PDF، القيمة الافتراضية هي false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| الاسم | الوصف |
| --- | --- |
| setEmbedTextures(value) | دمج القوام الخارجية في ملف PDF، القيمة الافتراضية هي false. |

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



