---
title: "الفئة RvmLoadOptions"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Formats.RvmLoadOptions. خيارات التحميل لملف RVM الخاص بنظام إدارة تصميم مصنع AVEVA."
type: docs
weight: 1470
url: /ar/net/aspose.threed.formats/rvmloadoptions/
---
## RvmLoadOptions class

خيارات التحميل لملف RVM الخاص بنظام إدارة تصميم مصنع AVEVA.

```csharp
public class RvmLoadOptions : LoadOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [RvmLoadOptions](rvmloadoptions/#constructor)() | إنشاء مثال `RvmLoadOptions` |
| [RvmLoadOptions](rvmloadoptions/#constructor_1)(FileContentType) | إنشاء مثال `RvmLoadOptions` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AttributePrefix](../../aspose.threed.formats/rvmloadoptions/attributeprefix/) { get; set; } | يحصل أو يعيّن بادئة السمات التي تم تعريفها في ملفات السمات الخارجية، تُستخدم البادئة لتجنب تعارض الأسماء، القيمة الافتراضية هي "rvm:" |
| [CenterScene](../../aspose.threed.formats/rvmloadoptions/centerscene/) { get; set; } | مركز المشهد بعد تحميله. |
| [CylinderRadialSegments](../../aspose.threed.formats/rvmloadoptions/cylinderradialsegments/) { get; set; } | يحصل أو يعيّن عدد القطاعات الشعاعية للأسطوانة، القيمة الافتراضية هي 16 |
| [DishLatitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlatitudesegments/) { get; set; } | يحصل أو يعيّن عدد قطاعات خطوط العرض للطبق، القيمة الافتراضية هي 8 |
| [DishLongitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlongitudesegments/) { get; set; } | يحصل أو يعيّن عدد القطاعات الطولية للطبق، القيمة الافتراضية هي 12 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | يحصل أو يضبط الترميز الافتراضي للملفات النصية. القيمة الافتراضية هي null مما يعني أن المستورد/المصدر سيقرر أي ترميز يستخدم. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | يحصل على تنسيق الملف المحدد في خيار الحفظ/التحميل الحالي. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | اسم ملف المشهد المُصدّر/المستورد. هذا اختياري، لكنه مفيد عند تسلسل الأصول الخارجية مثل مادة OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | السماح للمستخدم بالتعامل مع كيفية إدارة التبعيات الخارجية أثناء التحميل/الحفظ. |
| [GenerateMaterials](../../aspose.threed.formats/rvmloadoptions/generatematerials/) { get; set; } | إنشاء مواد بألوان عشوائية لكل كائن في المشهد إذا لم يتم تصدير جدول الألوان داخل ملف RVM. القيمة الافتراضية هي true |
| [LookupAttributes](../../aspose.threed.formats/rvmloadoptions/lookupattributes/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم تحميل السمات من ملف قائمة السمات الخارجية (.att/.attrib/.txt)، القيمة الافتراضية هي true. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل. |
| [RectangularTorusSegments](../../aspose.threed.formats/rvmloadoptions/rectangulartorussegments/) { get; set; } | يحصل أو يعيّن عدد القطاعات الشعاعية للطور المستطيل، القيمة الافتراضية هي 20 |
| [TorusTubularSegments](../../aspose.threed.formats/rvmloadoptions/torustubularsegments/) { get; set; } | يحصل أو يعيّن عدد القطاعات الأنبوبيّة للطور، القيمة الافتراضية هي 20 |

## أمثلة

يعرض الشيفرة التالية كيفية تخصيص معلمات التجزئة للأشكال الهندسية الأولية المستوردة من ملف RVM باستخدام RvmLoadOptions.

```csharp
RvmLoadOptions opt = new RvmLoadOptions();
opt.RectangularTorusSegments = 30;
opt.CylinderRadialSegments = 20;
opt.DishLatitudeSegments = 20;
opt.DishLongitudeSegments = 20;
opt.CenterScene = true;
var scene = Scene.FromFile("input.rvm", opt);
scene.Save("output.obj");
```

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


