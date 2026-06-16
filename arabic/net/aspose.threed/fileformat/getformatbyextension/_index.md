---
title: "FileFormat.GetFormatByExtension"
second_title: "مرجع Aspose.3D for .NET API"
description: "FileFormat الطريقة. يحصل على تنسيق الملف المفضل من اسم امتداد الملف. يجب أن يبدأ اسم الامتداد بنقطة"
type: docs
weight: 470
url: /ar/net/aspose.threed/fileformat/getformatbyextension/
---
## FileFormat.GetFormatByExtension method

يحصل على تنسيق الملف المفضّل من اسم امتداد الملف. يجب أن يبدأ اسم الامتداد بنقطة ('.').

```csharp
public static FileFormat GetFormatByExtension(string extensionName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| extensionName | سلسلة | اسم الامتداد يبدأ بـ '.' للاستعلام. |

### قيمة الإرجاع

مثال من [`FileFormat`](../)، وإلا يتم إرجاع null.

## أمثلة

الكود التالي يوضح كيفية حفظ المشهد في الذاكرة باستخدام التنسيق المحدد

```csharp
Scene scene = new Scene(new Box());
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
using(var ms = new MemoryStream())
{
    scene.Save(ms, format);
}
```

### انظر أيضًا

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


