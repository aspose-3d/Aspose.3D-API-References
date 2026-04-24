---
title: FontFile.FromFile
second_title: مرجع API Aspose.3D لـ .NET
description: طريقة FontFile. تحميل FontFile من اسم الملف
type: docs
weight: 10
url: /ar/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

تحميل FontFile من اسم الملف

```csharp
public static FontFile FromFile(string fileName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | المسار إلى ملف الخط |

### قيمة الإرجاع

مثيل FontFile

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عندما يفشل القراءة من الملف. |

## Examples

يظهر الشيفرة التالية كيفية إنشاء شبكة ثلاثية الأبعاد من النص باستخدام ملف الخط المحدد.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### انظر أيضًا

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


