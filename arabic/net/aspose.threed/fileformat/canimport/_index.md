---
title: "FileFormat.CanImport"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "FileFormat property. يحدد ما إذا كان Aspose.3D يدعم استيراد المشهد من تنسيق الملف الحالي"
type: docs
weight: 490
url: /ar/net/aspose.threed/fileformat/canimport/
---
## FileFormat.CanImport property

يحدد ما إذا كان Aspose.3D يدعم استيراد المشهد من تنسيق الملف الحالي.

```csharp
public bool CanImport { get; }
```

## أمثلة

الكود التالي يوضح كيفية التحقق مما إذا كان الاستيراد من التنسيق المحدد مدعومًا.

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanImport)
    Console.WriteLine($"Can import from {outputFormat}");
```

### انظر أيضًا

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


