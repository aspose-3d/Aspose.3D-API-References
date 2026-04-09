---
title: FileSystem.CreateZipFileSystem
second_title: مرجع API Aspose.3D لـ .NET
description: طريقة FileSystem. إنشاء نظام ملفات لتوفير وصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ
type: docs
weight: 40
url: /ar/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

إنشاء نظام ملفات لتوفير وصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | التدفق للوصول إلى ملف zip |
| baseDir | سلسلة | الدليل الأساسي داخل ملف zip. |

### قيمة الإرجاع

نظام ملفات zip

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عندما يفشل القراءة من التدفق. |

## ملاحظات

هذا نظام ملفات للقراءة فقط، لذا لا يتم دعم عمليات الكتابة.

## Examples

يعرض الشيفرة التالية كيفية استيراد ملف وتوفير الملفات التابعة في ملف أرشيف zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//إنشاء مثيل لخيارات التحميل وتحديد نظام ملفات zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//تحميل الملف
var scene = Scene.FromFile(inputFile, opt);
```

### انظر أيضًا

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

نظام ملفات لتوفير وصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | اسم الملف لملف zip. |

### قيمة الإرجاع

نظام ملفات zip

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عندما يفشل القراءة من التدفق. |

## Examples

يعرض الشيفرة التالية كيفية استيراد ملف وتوفير الملفات التابعة في ملف أرشيف zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//إنشاء مثيل لخيارات التحميل وتحديد نظام ملفات zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//تحميل الملف
var scene = Scene.FromFile(inputFile, opt);
```

### انظر أيضًا

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


