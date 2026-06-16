---
title: "FileSystem.CreateZipFileSystem"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة FileSystem. إنشاء نظام ملفات لتوفير الوصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ."
type: docs
weight: 40
url: /ar/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

إنشاء نظام ملفات لتوفير وصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق للوصول إلى ملف zip |
| baseDir | سلسلة | الدليل الأساسي داخل ملف zip. |

### قيمة الإرجاع

نظام ملفات zip

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يتم إلقاؤه عندما يفشل القراءة من التدفق. |

## ملاحظات

هذا نظام ملفات للقراءة فقط، لذا لا يتم دعم عمليات الكتابة.

## أمثلة

الكود التالي يوضح كيفية استيراد الملف وتوفير الملفات التابعة في ملف أرشيف zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//إنشاء كائن خيارات التحميل وتحديد نظام ملفات zip
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

نظام الملفات لتوفير الوصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | اسم الملف لملف zip. |

### قيمة الإرجاع

نظام ملفات zip

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يتم إلقاؤه عندما يفشل القراءة من التدفق. |

## أمثلة

الكود التالي يوضح كيفية استيراد الملف وتوفير الملفات التابعة في ملف أرشيف zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//إنشاء كائن خيارات التحميل وتحديد نظام ملفات zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//تحميل الملف
var scene = Scene.FromFile(inputFile, opt);
```

### انظر أيضًا

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


