---
title: "IOConfig"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/ioconfig/
---
## IOConfig class

إعدادات الإدخال/الإخراج للتسلسل/إلغاء التسلسل. يمكن للمستخدم تحديد تكوينات مفصلة مثل مسار البحث عن التبعيات أو إعدادات متعلقة بالتنسيق هنا  @hideconstructor


## الطرق

### getFileSystemFactory{#getFileSystemFactory}

| الاسم | الوصف |
| --- | --- |
| getFileSystemFactory() | يحصل أو يضبط فئة المصنع لنظام الملفات. المصنع الافتراضي سيُنشئ LocalFileSystem وهو غير مناسب لبيئة الخادم. |

 **Result:**



---


### setFileSystemFactory{#setFileSystemFactory}

| الاسم | الوصف |
| --- | --- |
| setFileSystemFactory(value) | يحصل أو يضبط فئة المصنع لنظام الملفات. المصنع الافتراضي سيُنشئ LocalFileSystem وهو غير مناسب لبيئة الخادم. |

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



