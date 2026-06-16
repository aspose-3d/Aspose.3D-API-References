---
title: "الفئة ZipArchiveFileSystem"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Utilities.ZipArchiveFileSystem. نظام ملفات لتوفير وصول للقراءة فقط إلى ملف zip أو تدفق zip محدد. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ."
type: docs
weight: 2830
url: /ar/net/aspose.threed.utilities/ziparchivefilesystem/
---
## ZipArchiveFileSystem class

نظام الملفات لتوفير الوصول للقراءة فقط إلى ملف zip المحدد أو تدفق zip. سيتم التخلص من نظام الملفات بعد عملية الفتح/الحفظ.

```csharp
public class ZipArchiveFileSystem : FileSystem
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Dispose](../../aspose.threed.utilities/ziparchivefilesystem/dispose/)() | تخلص من ZipArchiveFileSystem وأطلق موارده الداخلية. |
| override [ReadFile](../../aspose.threed.utilities/ziparchivefilesystem/readfile/)(string, IOConfig) | فتح الملف للقراءة |
| override [WriteFile](../../aspose.threed.utilities/ziparchivefilesystem/writefile/)(string, IOConfig) | فتح الملف للكتابة، غير مُنفّذ في هذه الفئة. |

### أمثلة

الكود التالي يوضح كيفية استيراد الملف وتوفير الملفات التابعة في ملف أرشيف zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//إنشاء كائن خيارات التحميل وتحديد نظام ملفات zip
var opt = format.CreateLoadOptions();
opt.FileSystem = new ZipArchiveFileSystem("textures.zip");
//تحميل الملف
var scene = Scene.FromFile(inputFile, opt);
```

### انظر أيضًا

* class [FileSystem](../filesystem/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


