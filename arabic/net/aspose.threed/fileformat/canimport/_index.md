---
title: "FileFormat.CanImport"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية FileFormat. يحصل على ما إذا كان Aspose.3D يدعم استيراد المشهد من تنسيق الملف الحالي"
type: docs
weight: 490
url: /ar/net/aspose.threed/fileformat/canimport/
---
## FileFormat.CanImport property

يحصل على ما إذا كان Aspose.3D يدعم استيراد المشهد من تنسيق الملف الحالي.

```csharp
public bool CanImport { get; }
```

## أمثلة

الكود التالي يوضح كيفية التحقق مما إذا كان استيراد التنسيق المحدد مدعومًا.

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


