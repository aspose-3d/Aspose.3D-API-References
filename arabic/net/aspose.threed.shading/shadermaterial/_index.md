---
title: "الفئة ShaderMaterial"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Shading.ShaderMaterial. يتيح مادة الظل (shader material) وصف المادة بواسطة محرك عرض خارجي أو لغة ظل. يستخدم ShaderMaterial تقنية ShaderTechnique لوصف تفاصيل العرض الفعلية وسيتم اختيار الأنسب وفقًا لمنصة العرض النهائية. على سبيل المثال، يمكن أن يحتوي كائن ShaderMaterial الخاص بك على تقنيتين، إحداهما معرفة بـ HLSL والأخرى معرفة بـ GLSL. تحت منصة غير نافذة، يجب استخدام GLSL بدلاً من HLSL."
type: docs
weight: 2580
url: /ar/net/aspose.threed.shading/shadermaterial/
---
## ShaderMaterial class

يتيح مادة الظل وصف المادة بواسطة محرك عرض خارجي أو لغة ظل. `ShaderMaterial` يستخدم [`ShaderTechnique`](../shadertechnique/) لوصف تفاصيل العرض الفعلية، وسيتم اختيار الأنسب وفقًا لمنصة العرض النهائية. على سبيل المثال، يمكن أن يحتوي كائن `ShaderMaterial` الخاص بك على تقنيتين، إحداهما معرفة بـ HLSL، والأخرى معرفة بـ GLSL. تحت منصة غير نافذة يجب استخدام GLSL بدلاً من HLSL

```csharp
public class ShaderMaterial : Material
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [ShaderMaterial](shadermaterial/#constructor)() | ينشئ مثيلًا جديدًا للفئة `ShaderMaterial`. |
| [ShaderMaterial](shadermaterial/#constructor_1)(string) | ينشئ مثيلًا جديدًا للفئة `ShaderMaterial`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Techniques](../../aspose.threed.shading/shadermaterial/techniques/) { get; } | يحصل على جميع التقنيات المتاحة المعرفة في هذه المادة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | يحصل على المُعدِّد لتعداد فتحات القوام الداخلية. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | يحصل على القوام من الفتحة المحددة، يمكن أن يكون اسم خاصية المادة أو اسم معلمة المظلل |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | يعيّن القوام إلى الفتحة المحددة |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | يحوّل الكائن إلى سلسلة |

### انظر أيضًا

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


