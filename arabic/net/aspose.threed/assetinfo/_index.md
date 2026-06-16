---
title: "الفئة AssetInfo"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.AssetInfo. معلومات الأصل. يمكن إرفاق معلومات الأصل بمشهد. يمكن للمشهد الفرعي أن يمتلك AssetInfo الخاص به لتجاوز تعريف الوالدين"
type: docs
weight: 130
url: /ar/net/aspose.threed/assetinfo/
---
## AssetInfo class

معلومات الأصل. يمكن إرفاق معلومات الأصل إلى [`Scene`](../scene/). يمكن لـ [`Scene`](../scene/) الفرعي أن يمتلك `AssetInfo` الخاص به لتجاوز تعريف الوالد.

```csharp
public class AssetInfo : A3DObject
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [AssetInfo](assetinfo/#constructor)() | يُهيئ مثيلاً جديداً من فئة `AssetInfo`. |
| [AssetInfo](assetinfo/#constructor_1)(string) | يُهيئ مثيلاً جديداً من فئة `AssetInfo`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Ambient](../../aspose.threed/assetinfo/ambient/) { get; set; } | يحصل أو يعيّن اللون المحيطي الافتراضي لهذا الأصل |
| [ApplicationName](../../aspose.threed/assetinfo/applicationname/) { get; set; } | الحصول أو تعيين التطبيق الذي أنشأ هذا الأصل |
| [ApplicationVendor](../../aspose.threed/assetinfo/applicationvendor/) { get; set; } | الحصول أو تعيين اسم بائع التطبيق |
| [ApplicationVersion](../../aspose.threed/assetinfo/applicationversion/) { get; set; } | الحصول أو تعيين نسخة التطبيق الذي أنشأ هذا الأصل. |
| [Author](../../aspose.threed/assetinfo/author/) { get; set; } | الحصول أو تعيين مؤلف هذا الأصل |
| [AxisSystem](../../aspose.threed/assetinfo/axissystem/) { get; set; } | الحصول أو تعيين نظام الإحداثيات/متجه الارتفاع/متجه الأمام لمعلومات الأصل. |
| [Comment](../../aspose.threed/assetinfo/comment/) { get; set; } | الحصول أو تعيين تعليق هذا الأصل. |
| [CoordinateSystem](../../aspose.threed/assetinfo/coordinatesystem/) { get; set; } | الحصول أو تعيين نظام الإحداثيات المستخدم في هذا الأصل. |
| [Copyright](../../aspose.threed/assetinfo/copyright/) { get; set; } | الحصول أو تعيين حقوق النشر للوثيقة |
| [CreationTime](../../aspose.threed/assetinfo/creationtime/) { get; set; } | الحصول أو تعيين وقت إنشاء هذا الأصل |
| [FrontVector](../../aspose.threed/assetinfo/frontvector/) { get; set; } | الحصول أو تعيين متجه الأمام المستخدم في هذا الأصل. |
| [Keywords](../../aspose.threed/assetinfo/keywords/) { get; set; } | الحصول أو تعيين الكلمات المفتاحية لهذا الأصل |
| [ModificationTime](../../aspose.threed/assetinfo/modificationtime/) { get; set; } | الحصول أو تعيين وقت التعديل لهذا الأصل |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Revision](../../aspose.threed/assetinfo/revision/) { get; set; } | الحصول أو تعيين رقم المراجعة لهذا الأصل، يُستخدم عادةً في نظام التحكم بالإصدارات. |
| [Subject](../../aspose.threed/assetinfo/subject/) { get; set; } | الحصول أو تعيين موضوع هذا الأصل |
| [Title](../../aspose.threed/assetinfo/title/) { get; set; } | الحصول أو تعيين عنوان هذا الأصل |
| [UnitName](../../aspose.threed/assetinfo/unitname/) { get; set; } | الحصول أو تعيين وحدة الطول المستخدمة في هذا الأصل. مثال: سم/م/كم/بوصة/قدم |
| [UnitScaleFactor](../../aspose.threed/assetinfo/unitscalefactor/) { get; set; } | الحصول أو تعيين معامل التحجيم إلى المتر في العالم الحقيقي. |
| [UpVector](../../aspose.threed/assetinfo/upvector/) { get; set; } | الحصول أو تعيين متجه الارتفاع المستخدم في هذا الأصل. |
| [Url](../../aspose.threed/assetinfo/url/) { get; set; } | الحصول أو تعيين عنوان URL لهذا الأصل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

## أمثلة

يعرض الشيفرة التالية كيفية قراءة معلومات الأصل من ملف fbx:

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The file is created at {scene.AssetInfo.CreationTime} by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion} ");
```

### انظر أيضًا

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


