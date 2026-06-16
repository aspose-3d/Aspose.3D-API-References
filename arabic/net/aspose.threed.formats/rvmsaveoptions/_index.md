---
title: "الفئة RvmSaveOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Formats.RvmSaveOptions. خيارات الحفظ لملف Aveva PDMS RVM"
type: docs
weight: 1480
url: /ar/net/aspose.threed.formats/rvmsaveoptions/
---
## RvmSaveOptions class

خيارات الحفظ لملف Aveva PDMS RVM.

```csharp
public class RvmSaveOptions : SaveOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [RvmSaveOptions](rvmsaveoptions/#constructor)() | منشئ `RvmSaveOptions` |
| [RvmSaveOptions](rvmsaveoptions/#constructor_1)(FileContentType) | منشئ `RvmSaveOptions` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AttributeListFile](../../aspose.threed.formats/rvmsaveoptions/attributelistfile/) { get; set; } | يحصل أو يعيّن اسم ملف قائمة السمات، سيولد المصدّر اسمًا بناءً على اسم ملف .rvm عندما تكون هذه الخاصية غير معرفة، القيمة الافتراضية هي null. |
| [AttributePrefix](../../aspose.threed.formats/rvmsaveoptions/attributeprefix/) { get; set; } | يحصل أو يعيّن البادئة للسمات التي سيتم تصديرها، الخاصية المصدّرة لن تحتوي على بادئة، السمات المخصصة ذات البادئة المختلفة لن تُصدّر، القيمة الافتراضية هي 'rvm:'. على سبيل المثال إذا كانت الخاصية rvm:Refno=345، فإن السمة المصدّرة ستكون Refno = 345، تُزال البادئة. |
| [Author](../../aspose.threed.formats/rvmsaveoptions/author/) { get; set; } | معلومات المؤلف، القيمة الافتراضية هي '3d@aspose' |
| [CreationTime](../../aspose.threed.formats/rvmsaveoptions/creationtime/) { get; set; } | الطابع الزمني الذي صدر هذا الملف، القيمة الافتراضية هي الوقت الحالي |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [ExportAttributes](../../aspose.threed.formats/rvmsaveoptions/exportattributes/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم تصدير قائمة السمات إلى ملف .att خارجي، القيمة الافتراضية هي false. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | محاولة نسخ القوام المستخدمة في المشهد إلى دليل الإخراج. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileNote](../../aspose.threed.formats/rvmsaveoptions/filenote/) { get; set; } | ملاحظة الملف في رأس الملف. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |

## أمثلة

الكود التالي يوضح كيفية تصدير السمة في RVM.

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//اسم العقدة مطلوب لتصدير السمات
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//الخصائص ذات البادئة rvm: سيتم تصديرها.
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


