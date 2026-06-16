---
title: "الفئة PhongMaterial"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Shading.PhongMaterial. مادة لنموذج الظل blinnphong"
type: docs
weight: 2570
url: /ar/net/aspose.threed.shading/phongmaterial/
---
## PhongMaterial class

المادة لنموذج التظليل بلين-فونغ.

```csharp
public class PhongMaterial : LambertMaterial
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [PhongMaterial](phongmaterial/#constructor)() | ينشئ مثيلًا جديدًا للفئة `PhongMaterial`. |
| [PhongMaterial](phongmaterial/#constructor_1)(string) | ينشئ مثيلًا جديدًا للفئة `PhongMaterial`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor/) { get; set; } | يحصل أو يضبط اللون المحيط |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor/) { get; set; } | يحصل أو يضبط اللون المنتشر |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor/) { get; set; } | يحصل أو يضبط اللون المنبعث |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [ReflectionColor](../../aspose.threed.shading/phongmaterial/reflectioncolor/) { get; set; } | يحصل أو يعيّن لون الانعكاس. |
| [ReflectionFactor](../../aspose.threed.shading/phongmaterial/reflectionfactor/) { get; set; } | يحصل أو يعيّن تخفيف لون الانعكاس. |
| [Shininess](../../aspose.threed.shading/phongmaterial/shininess/) { get; set; } | يحصل أو يعيّن اللمعان، هذا يتحكم في حجم الإبراز الانعكاسي. صيغة الانعكاس: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [SpecularColor](../../aspose.threed.shading/phongmaterial/specularcolor/) { get; set; } | يحصل أو يعيّن اللون الانعكاسي. |
| [SpecularFactor](../../aspose.threed.shading/phongmaterial/specularfactor/) { get; set; } | يحصل أو يعيّن عامل الانعكاس. صيغة الانعكاس: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency/) { get; set; } | يحصل أو يضبط عامل الشفافية. يجب أن يكون العامل بين 0 (0٪، غير شفاف تمامًا) و 1 (100٪، شفاف تمامًا). أي قيمة عامل غير صالحة سيتم تقليمها. |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor/) { get; set; } | يحصل أو يضبط اللون الشفاف. |

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

* class [LambertMaterial](../lambertmaterial/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


