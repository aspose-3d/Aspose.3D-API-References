---
title: "الفئة TextureData"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Render.TextureData. تحتوي هذه الفئة على البيانات الخام وتعريف تنسيق القوام."
type: docs
weight: 2460
url: /ar/net/aspose.threed.render/texturedata/
---
## TextureData class

هذه الفئة تحتوي على البيانات الخام وتعريف التنسيق للملمس.

```csharp
public class TextureData : A3DObject
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [TextureData](texturedata/#constructor)() | منشئ `TextureData` |
| [TextureData](texturedata/#constructor_1)(int, int, PixelFormat) | ينشئ كائنًا جديدًا من `TextureData` ويخصص بيانات البكسل. |
| [TextureData](texturedata/#constructor_2)(int, int, int, int, PixelFormat, byte[]) | منشئ `TextureData` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BytesPerPixel](../../aspose.threed.render/texturedata/bytesperpixel/) { get; } | عدد البايتات في البكسل |
| [Data](../../aspose.threed.render/texturedata/data/) { get; } | البايتات الخام لبيانات البكسل |
| [Height](../../aspose.threed.render/texturedata/height/) { get; } | عدد البكسلات العمودية |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [PixelFormat](../../aspose.threed.render/texturedata/pixelformat/) { get; } | تنسيق البكسل |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Stride](../../aspose.threed.render/texturedata/stride/) { get; } | عدد البايتات في سطر المسح. |
| [Width](../../aspose.threed.render/texturedata/width/) { get; } | عدد البكسلات الأفقية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromFile](../../aspose.threed.render/texturedata/fromfile/)(string) | تحميل قوام من ملف |
| static [FromStream](../../aspose.threed.render/texturedata/fromstream/)(Stream) | تحميل قوام من تدفق |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels)(PixelMapMode) | تعيين جميع البكسلات للقراءة/الكتابة |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_1)(PixelMapMode, PixelFormat) | تعيين جميع البكسلات للقراءة/الكتابة بتنسيق بكسل محدد |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_2)(Rect, PixelMapMode, PixelFormat) | تعيين البكسلات المحددة بالمستطيل للقراءة/الكتابة بتنسيق بكسل محدد |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [Save](../../aspose.threed.render/texturedata/save/#save_1)(string) | حفظ بيانات القوام في ملف صورة |
| [Save](../../aspose.threed.render/texturedata/save/#save)(Stream, string) | حفظ بيانات القوام في تنسيق صورة محدد |
| [Save](../../aspose.threed.render/texturedata/save/#save_2)(string, string) | حفظ بيانات القوام في ملف صورة |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| [TransformPixelFormat](../../aspose.threed.render/texturedata/transformpixelformat/)(PixelFormat) | تحويل تخطيط البكسل إلى تنسيق بكسل جديد. |

### انظر أيضًا

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


