---
title: "FileFormat.CanExport"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية FileFormat. تُعيد ما إذا كان Aspose.3D يدعم تصدير المشهد إلى تنسيق الملف الحالي"
type: docs
weight: 480
url: /ar/net/aspose.threed/fileformat/canexport/
---
## FileFormat.CanExport property

يحصل ما إذا كان Aspose.3D يدعم تصدير المشهد إلى تنسيق الملف الحالي.

```csharp
public bool CanExport { get; }
```

## أمثلة

الكود التالي يوضح كيفية التحقق مما إذا كان تصدير إلى التنسيق المحدد مدعومًا.

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanExport)
    Console.WriteLine($"Can export to {outputFormat}");
```

### انظر أيضًا

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


