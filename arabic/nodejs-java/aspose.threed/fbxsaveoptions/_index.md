---
title: "FbxSaveOptions"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

خيارات الحفظ لملف Fbx.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(format) | يُهيئ كائن FbxSaveOptions |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| forma | FileFormat | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(contentType) | تهيئة كائن FbxSaveOptions باستخدام أحدث نسخة مدعومة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| الاسم | الوصف |
| --- | --- |
| getReusePrimitiveMesh() | إعادة استخدام الشبكة للأشكال الأولية ذات المعلمات نفسها، سيؤدي ذلك إلى تقليل حجم مخرجات FBX بشكل كبير عندما يتم بناء المشهد بمجموعة كبيرة من الأشكال الأولية (مثل المستوردة من ملفات CAD). القيمة الافتراضية هي false |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| الاسم | الوصف |
| --- | --- |
| setReusePrimitiveMesh(value) | إعادة استخدام الشبكة للأشكال الأولية ذات المعلمات نفسها، سيؤدي ذلك إلى تقليل حجم مخرجات FBX بشكل كبير عندما يتم بناء المشهد بمجموعة كبيرة من الأشكال الأولية (مثل المستوردة من ملفات CAD). القيمة الافتراضية هي false |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| الاسم | الوصف |
| --- | --- |
| getEnableCompression() | ضغط البيانات الثنائية الكبيرة في ملف FBX (مثل بيانات الرسوم المتحركة، نقاط التحكم، بيانات عناصر الرؤوس، الفهارس)، القيمة الافتراضية هي true. |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| الاسم | الوصف |
| --- | --- |
| setEnableCompression(value) | ضغط البيانات الثنائية الكبيرة في ملف FBX (مثل بيانات الرسوم المتحركة، نقاط التحكم، بيانات عناصر الرؤوس، الفهارس)، القيمة الافتراضية هي true. |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| الاسم | الوصف |
| --- | --- |
| getFoldRepeatedCurveData() | يحصل أو يضبط ما إذا كان سيتم إعادة استخدام بيانات المنحنى المتكررة بزيادة عدد المراجع للبيانات الأخيرة؛ true إذا تم طي بيانات المنحنى المتكررة؛ وإلا false. |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| الاسم | الوصف |
| --- | --- |
| getExportLegacyMaterialProperties() | يحصل أو يضبط ما إذا كان سيتم تصدير خصائص المواد القديمة، يُستخدم للتوافق العكسي. هذا الخيار مفعّل افتراضيًا. |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| الاسم | الوصف |
| --- | --- |
| setExportLegacyMaterialProperties(value) | يحصل أو يضبط ما إذا كان سيتم تصدير خصائص المواد القديمة، يُستخدم للتوافق العكسي. هذا الخيار مفعّل افتراضيًا. |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| الاسم | الوصف |
| --- | --- |
| getVideoForTexture() | يحصل أو يضبط ما إذا كان سيتم إنشاء كائن Video للملمس عند التصدير كـ FBX. |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| الاسم | الوصف |
| --- | --- |
| setVideoForTexture(value) | يحصل أو يضبط ما إذا كان سيتم إنشاء كائن Video للملمس عند التصدير كـ FBX. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| الاسم | الوصف |
| --- | --- |
| getEmbedTextures() | يحصل أو يضبط ما إذا كان سيتم تضمين الملمس في ملف الإخراج النهائي. سيحاول مُصدّر FBX العثور على البيانات الخام للملمس من نظام الملفات، وتضمين الملف في ملف FBX النهائي. القيمة الافتراضية هي false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| الاسم | الوصف |
| --- | --- |
| setEmbedTextures(value) | يحصل أو يضبط ما إذا كان سيتم تضمين الملمس في ملف الإخراج النهائي. سيحاول مُصدّر FBX العثور على البيانات الخام للملمس من نظام الملفات، وتضمين الملف في ملف FBX النهائي. القيمة الافتراضية هي false. |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| الاسم | الوصف |
| --- | --- |
| getGenerateVertexElementMaterial() | يحصل أو يضبط ما إذا كان سيتم دائمًا إنشاء VertexElementMaterial للأشكال الهندسية إذا كان العقدة المرتبطة تحتوي على مواد. هذا الخيار مُعطَّل افتراضيًا. |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| الاسم | الوصف |
| --- | --- |
| setGenerateVertexElementMaterial(value) | يحصل أو يضبط ما إذا كان سيتم دائمًا إنشاء VertexElementMaterial للأشكال الهندسية إذا كان العقدة المرتبطة تحتوي على مواد. هذا الخيار مُعطَّل افتراضيًا. |

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



