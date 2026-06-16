---
title: "الفئة Texture"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Shading.Texture. هذه الفئة تعرف الملمس من ملف خارجي"
type: docs
weight: 2600
url: /ar/net/aspose.threed.shading/texture/
---
## Texture class

هذه الفئة تعرف الملمس من ملف خارجي.

```csharp
public class Texture : TextureBase
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Texture](texture/#constructor)() | ينشئ مثيلاً جديداً للفئة `Texture`. |
| [Texture](texture/#constructor_1)(string) | ينشئ مثيلاً جديداً للفئة `Texture`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha/) { get; set; } | يحصل أو يعيّن قيمة ألفا الافتراضية للملمس. هذا صالح عندما يكون [`AlphaSource`](../texturebase/alphasource/) هو PixelAlpha. القيمة الافتراضية هي 1.0، نطاق القيم الصالحة بين 0 و 1 |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource/) { get; set; } | يحصل أو يعيّن ما إذا كان الملمس يحدد قناة ألفا. القيمة الافتراضية هي لا شيء |
| [Content](../../aspose.threed.shading/texture/content/) { get; set; } | يحصل أو يعيّن المحتوى الثنائي للملمس. المحتوى المدمج للملمس اختياري، يجب على المستخدم تحميل الملمس من ملف خارجي إذا كان مفقوداً. |
| [EnableMipMap](../../aspose.threed.shading/texture/enablemipmap/) { get; set; } | يحصل أو يعيّن ما إذا كان mipmap مفعلاً لهذا الملمس |
| [FileName](../../aspose.threed.shading/texture/filename/) { get; set; } | يحصل أو يعيّن ملف الملمس المرتبط. |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter/) { get; set; } | يحصل أو يعيّن الفلتر للتكبير. |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter/) { get; set; } | يسترجع أو يعيّن الفلتر للتقليل. |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter/) { get; set; } | يسترجع أو يعيّن الفلتر لأخذ عينات مستوى الميب. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation/) { get; set; } | يسترجع أو يعيّن دوران القوام |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale/) { get; set; } | يسترجع أو يعيّن مقياس الـ UV. |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation/) { get; set; } | يسترجع أو يعيّن إزاحة الـ UV. |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu/) { get; set; } | يسترجع أو يعيّن أوضاع لف القوام في الاتجاه U. |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev/) { get; set; } | يسترجع أو يعيّن أوضاع لف القوام في الاتجاه V. |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew/) { get; set; } | يسترجع أو يعيّن أوضاع لف القوام في الاتجاه W. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation/)(double, double) | يعيّن دوران الـ UV. |
| [SetScale](../../aspose.threed.shading/texturebase/setscale/)(double, double) | يعيّن مقياس الـ UV. |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation/)(double, double) | يعيّن إزاحة الـ UV. |

### انظر أيضًا

* class [TextureBase](../texturebase/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


