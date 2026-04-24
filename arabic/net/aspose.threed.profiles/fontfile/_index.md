---
title: الفئة FontFile
second_title: مرجع API Aspose.3D لـ .NET
description: الفئة Aspose.ThreeD.Profiles.FontFile. ملف الخط يحتوي على تعريفات للرموز ويُستخدم لإنشاء ملف تعريف نصي.
type: docs
weight: 1720
url: /ar/net/aspose.threed.profiles/fontfile/
---
## FontFile class

ملف الخط يحتوي على تعريفات للرموز، يُستخدم لإنشاء ملف تعريف النص.

```csharp
public abstract class FontFile : A3DObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | تحميل FontFile من اسم الملف |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | تحليل FontFile من البايتات |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

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

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


