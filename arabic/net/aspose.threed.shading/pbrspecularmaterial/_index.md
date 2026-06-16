---
title: "فئة PbrSpecularMaterial"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Shading.PbrSpecularMaterial. مادة للتصيير القائم على الفيزياء بناءً على اللون المنتشر/اللمعان/السطوع"
type: docs
weight: 2560
url: /ar/net/aspose.threed.shading/pbrspecularmaterial/
---
## PbrSpecularMaterial class

المادة للتصيير الفيزيائي القائم على اللون المنتشر/اللمعان/اللمعان

```csharp
public class PbrSpecularMaterial : Material
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [PbrSpecularMaterial](pbrspecularmaterial/)() | منشئ `PbrSpecularMaterial` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Diffuse](../../aspose.threed.shading/pbrspecularmaterial/diffuse/) { get; set; } | يحصل أو يضبط اللون المنتشر للمادة، القيمة الافتراضية هي (1, 1, 1) |
| [DiffuseTexture](../../aspose.threed.shading/pbrspecularmaterial/diffusetexture/) { get; set; } | يحصل أو يعيّن النسيج للانتشار |
| [EmissiveColor](../../aspose.threed.shading/pbrspecularmaterial/emissivecolor/) { get; set; } | يحصل أو يعيّن اللون الانبعاثي، القيمة الافتراضية هي (0, 0, 0) |
| [EmissiveTexture](../../aspose.threed.shading/pbrspecularmaterial/emissivetexture/) { get; set; } | يحصل أو يعيّن النسيج للانبعاثي |
| [GlossinessFactor](../../aspose.threed.shading/pbrspecularmaterial/glossinessfactor/) { get; set; } | يحصل أو يعيّن اللمعان (النعومة) للمادة، 1 يعني ناعم تمامًا و0 يعني خشن تمامًا، القيمة الافتراضية هي 1، النطاق هو [0, 1] |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [NormalTexture](../../aspose.threed.shading/pbrspecularmaterial/normaltexture/) { get; set; } | يحصل أو يعيّن نسيج تمثيل العادي |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Specular](../../aspose.threed.shading/pbrspecularmaterial/specular/) { get; set; } | يحصل أو يعيّن اللون الانعكاسي للمادة، القيمة الافتراضية هي (1, 1, 1). |
| [SpecularGlossinessTexture](../../aspose.threed.shading/pbrspecularmaterial/specularglossinesstexture/) { get; set; } | يحصل أو يعيّن النسيج للون الانعكاسي، القناة RGB تخزن اللون الانعكاسي والقناة A تخزن اللمعان. |
| [Transparency](../../aspose.threed.shading/pbrspecularmaterial/transparency/) { get; set; } | يحصل أو يضبط عامل الشفافية. يجب أن يكون العامل بين 0 (0٪، غير شفاف تمامًا) و 1 (100٪، شفاف تمامًا). أي قيمة عامل غير صالحة سيتم تقليمها. |

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

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [MapSpecularGlossiness](../../aspose.threed.shading/pbrspecularmaterial/mapspecularglossiness/) | خريطة النسيج لللمعان الانعكاسي |

### انظر أيضًا

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


