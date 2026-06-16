---
title: "RvmLoadOptions"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/rvmloadoptions/
---
## RvmLoadOptions class

خيارات التحميل لملف RVM الخاص بنظام إدارة تصميم مصنع AVEVA.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(contentType) | إنشاء نسخة من RvmLoadOptions |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload() | إنشاء نسخة من RvmLoadOptions |

 **Result:**



---


### getGenerateMaterials{#getGenerateMaterials}

| الاسم | الوصف |
| --- | --- |
| getGenerateMaterials() | توليد مواد بألوان عشوائية لكل كائن في المشهد إذا لم يتم تصدير جدول الألوان داخل ملف RVM. القيمة الافتراضية هي true |

 **Result:**



---


### setGenerateMaterials{#setGenerateMaterials}

| الاسم | الوصف |
| --- | --- |
| setGenerateMaterials(value) | توليد مواد بألوان عشوائية لكل كائن في المشهد إذا لم يتم تصدير جدول الألوان داخل ملف RVM. القيمة الافتراضية هي true |

 **Result:**



---


### getCylinderRadialSegments{#getCylinderRadialSegments}

| الاسم | الوصف |
| --- | --- |
| getCylinderRadialSegments() | يحصل أو يضبط عدد القطاعات الشعاعية للأسطوانة، القيمة الافتراضية هي 16 |

 **Result:**



---


### setCylinderRadialSegments{#setCylinderRadialSegments}

| الاسم | الوصف |
| --- | --- |
| setCylinderRadialSegments(value) | يحصل أو يضبط عدد القطاعات الشعاعية للأسطوانة، القيمة الافتراضية هي 16 |

 **Result:**



---


### getDishLongitudeSegments{#getDishLongitudeSegments}

| الاسم | الوصف |
| --- | --- |
| getDishLongitudeSegments() | يحصل أو يضبط عدد قطاعات الطول للطبق، القيمة الافتراضية هي 12 |

 **Result:**



---


### setDishLongitudeSegments{#setDishLongitudeSegments}

| الاسم | الوصف |
| --- | --- |
| setDishLongitudeSegments(value) | يحصل أو يضبط عدد قطاعات الطول للطبق، القيمة الافتراضية هي 12 |

 **Result:**



---


### getDishLatitudeSegments{#getDishLatitudeSegments}

| الاسم | الوصف |
| --- | --- |
| getDishLatitudeSegments() | يحصل أو يضبط عدد قطاعات العرض للطبق، القيمة الافتراضية هي 8 |

 **Result:**



---


### setDishLatitudeSegments{#setDishLatitudeSegments}

| الاسم | الوصف |
| --- | --- |
| setDishLatitudeSegments(value) | يحصل أو يضبط عدد قطاعات العرض للطبق، القيمة الافتراضية هي 8 |

 **Result:**



---


### getTorusTubularSegments{#getTorusTubularSegments}

| الاسم | الوصف |
| --- | --- |
| getTorusTubularSegments() | يحصل أو يضبط عدد القطاعات الأنبوبيّة للطوق، القيمة الافتراضية هي 20 |

 **Result:**



---


### setTorusTubularSegments{#setTorusTubularSegments}

| الاسم | الوصف |
| --- | --- |
| setTorusTubularSegments(value) | يحصل أو يضبط عدد القطاعات الأنبوبيّة للطوق، القيمة الافتراضية هي 20 |

 **Result:**



---


### getRectangularTorusSegments{#getRectangularTorusSegments}

| الاسم | الوصف |
| --- | --- |
| getRectangularTorusSegments() | يحصل أو يضبط عدد القطاعات الشعاعية للطوق المستطيل، القيمة الافتراضية هي 20 |

 **Result:**



---


### setRectangularTorusSegments{#setRectangularTorusSegments}

| الاسم | الوصف |
| --- | --- |
| setRectangularTorusSegments(value) | يحصل أو يضبط عدد القطاعات الشعاعية للطوق المستطيل، القيمة الافتراضية هي 20 |

 **Result:**



---


### getCenterScene{#getCenterScene}

| الاسم | الوصف |
| --- | --- |
| getCenterScene() | توسيط المشهد بعد تحميله. |

 **Result:**



---


### setCenterScene{#setCenterScene}

| الاسم | الوصف |
| --- | --- |
| setCenterScene(value) | توسيط المشهد بعد تحميله. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| الاسم | الوصف |
| --- | --- |
| getAttributePrefix() | يحصل أو يعيّن البادئة للسمات التي تم تعريفها في ملفات السمات الخارجية، تُستخدم البادئة لتجنب تعارض الأسماء، القيمة الافتراضية هي "rvm:" |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| الاسم | الوصف |
| --- | --- |
| setAttributePrefix(value) | يحصل أو يعيّن البادئة للسمات التي تم تعريفها في ملفات السمات الخارجية، تُستخدم البادئة لتجنب تعارض الأسماء، القيمة الافتراضية هي "rvm:" |

 **Result:**



---


### getLookupAttributes{#getLookupAttributes}

| الاسم | الوصف |
| --- | --- |
| getLookupAttributes() | يحصل أو يعيّن ما إذا كان سيتم تحميل السمات من ملف قائمة السمات الخارجية (.att/.attrib/.txt)، القيمة الافتراضية هي true. |

 **Result:**



---


### setLookupAttributes{#setLookupAttributes}

| الاسم | الوصف |
| --- | --- |
| setLookupAttributes(value) | يحصل أو يعيّن ما إذا كان سيتم تحميل السمات من ملف قائمة السمات الخارجية (.att/.attrib/.txt)، القيمة الافتراضية هي true. |

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



