---
title: الفئة Text
second_title: مرجع API Aspose.3D لـ .NET
description: فئة Aspose.ThreeD.Profiles.Text. ملف تعريف نصي يصف هذا الملف التعريفي الحدود باستخدام الخط والنص.
type: docs
weight: 1820
url: /ar/net/aspose.threed.profiles/text/
---
## Text class

ملف تعريف نصي، يصف هذا الملف التعريف الحدود باستخدام الخط والنص.

```csharp
public class Text : Profile
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Text](text/)() | المُنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Content](../../aspose.threed.profiles/text/content/) { get; set; } | محتوى النص |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [Font](../../aspose.threed.profiles/text/font/) { get; set; } | خط النص. |
| [FontSize](../../aspose.threed.profiles/text/fontsize/) { get; set; } | مقياس حجم الخط. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يضبط العقدة الأب الأولى، إذا تم تعيين العقدة الأب الأولى، سيتم فصل هذا الكيان عن باقي العقد الأبوية. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض. |
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

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


