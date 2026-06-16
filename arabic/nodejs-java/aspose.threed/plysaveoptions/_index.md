---
title: "PlySaveOptions"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

خيارات الحفظ لتصدير المشهد كملف PLY.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | منشئ PlySaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(contentType) | منشئ PlySaveOptions |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getPointCloud{#getPointCloud}

| الاسم | الوصف |
| --- | --- |
| getPointCloud() | صدّر المشهد كسحابة نقطية، القيمة الافتراضية هي false. |

 **Result:**



---


### setPointCloud{#setPointCloud}

| الاسم | الوصف |
| --- | --- |
| setPointCloud(value) | صدّر المشهد كسحابة نقطية، القيمة الافتراضية هي false. |

 **Result:**



---


### getFlipCoordinate{#getFlipCoordinate}

| الاسم | الوصف |
| --- | --- |
| getFlipCoordinate() | اقلب الإحداثيات أثناء حفظ المشهد، القيمة الافتراضية هي true |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| الاسم | الوصف |
| --- | --- |
| setFlipCoordinate(value) | اقلب الإحداثيات أثناء حفظ المشهد، القيمة الافتراضية هي true |

 **Result:**



---


### getVertexElement{#getVertexElement}

| الاسم | الوصف |
| --- | --- |
| getVertexElement() | اسم العنصر لبيانات الرأس، القيمة الافتراضية هي "vertex" |

 **Result:**



---


### setVertexElement{#setVertexElement}

| الاسم | الوصف |
| --- | --- |
| setVertexElement(value) | اسم العنصر لبيانات الرأس، القيمة الافتراضية هي "vertex" |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| الاسم | الوصف |
| --- | --- |
| getPositionComponents() | أسماء المكونات لبيانات الموقع، القيمة الافتراضية هي ("x", "y", "z") |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| الاسم | الوصف |
| --- | --- |
| getNormalComponents() | أسماء المكونات لبيانات العادي، القيمة الافتراضية هي ("nx", "ny", "nz") |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| الاسم | الوصف |
| --- | --- |
| getTextureCoordinateComponents() | أسماء المكوّنات لبيانات إحداثيات النسيج، القيمة الافتراضية هي ("u", "v") |

 **Result:**



---


### getColorComponents{#getColorComponents}

| الاسم | الوصف |
| --- | --- |
| getColorComponents() | أسماء المكوّنات للون القمم، القيمة الافتراضية هي ("red", "green", "blue") |

 **Result:**



---


### getFaceElement{#getFaceElement}

| الاسم | الوصف |
| --- | --- |
| getFaceElement() | اسم العنصر لبيانات الوجه، القيمة الافتراضية هي "face" |

 **Result:**



---


### setFaceElement{#setFaceElement}

| الاسم | الوصف |
| --- | --- |
| setFaceElement(value) | اسم العنصر لبيانات الوجه، القيمة الافتراضية هي "face" |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| الاسم | الوصف |
| --- | --- |
| getFaceProperty() | اسم الخاصية لبيانات الوجه، القيمة الافتراضية هي "vertex_index" |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| الاسم | الوصف |
| --- | --- |
| setFaceProperty(value) | اسم الخاصية لبيانات الوجه، القيمة الافتراضية هي "vertex_index" |

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



