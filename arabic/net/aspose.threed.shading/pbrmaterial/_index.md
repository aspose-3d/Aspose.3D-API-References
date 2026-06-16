---
title: "الفئة PbrMaterial"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Shading.PbrMaterial. مادة للتصيير القائم على الفيزياء بناءً على لون الألبيدو/المعدن/الخشونة"
type: docs
weight: 2550
url: /ar/net/aspose.threed.shading/pbrmaterial/
---
## PbrMaterial class

المادة للتصيير الفيزيائي القائم على لون الألبيدو/المعدن/الخشونة

```csharp
public class PbrMaterial : Material
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [PbrMaterial](pbrmaterial/#constructor)() | إنشاء نسخة مادة PBR افتراضية |
| [PbrMaterial](pbrmaterial/#constructor_1)(Vector3) | إنشاء مادة PBR افتراضية مع قيمة لون الألبيدو المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Albedo](../../aspose.threed.shading/pbrmaterial/albedo/) { get; set; } | يحصل أو يضبط اللون الأساسي للمادة |
| [AlbedoTexture](../../aspose.threed.shading/pbrmaterial/albedotexture/) { get; set; } | يحصل أو يضبط النسيج للـ albedo |
| [EmissiveColor](../../aspose.threed.shading/pbrmaterial/emissivecolor/) { get; set; } | يحصل أو يضبط اللون المنبعث |
| [EmissiveTexture](../../aspose.threed.shading/pbrmaterial/emissivetexture/) { get; set; } | يحصل أو يعيّن النسيج للانبعاثي |
| [MetallicFactor](../../aspose.threed.shading/pbrmaterial/metallicfactor/) { get; set; } | يحصل أو يضبط معدنية المادة، قيمة 1 تعني أن المادة معدن وقيمة 0 تعني أن المادة عازلة. |
| [MetallicRoughness](../../aspose.threed.shading/pbrmaterial/metallicroughness/) { get; set; } | يحصل أو يضبط النسيج للمعدن (في قناة R) والخشونة (في قناة G) |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [NormalTexture](../../aspose.threed.shading/pbrmaterial/normaltexture/) { get; set; } | يحصل أو يعيّن نسيج تمثيل العادي |
| [OcclusionFactor](../../aspose.threed.shading/pbrmaterial/occlusionfactor/) { get; set; } | يحصل أو يضبط عامل الإغلاق المحيطي |
| [OcclusionTexture](../../aspose.threed.shading/pbrmaterial/occlusiontexture/) { get; set; } | يحصل أو يضبط النسيج للإغلاق المحيطي |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [RoughnessFactor](../../aspose.threed.shading/pbrmaterial/roughnessfactor/) { get; set; } | يحصل أو يضبط خشونة المادة، قيمة 1 تعني أن المادة خشنة تمامًا وقيمة 0 تعني أن المادة ناعمة تمامًا. |
| [SpecularTexture](../../aspose.threed.shading/pbrmaterial/speculartexture/) { get; set; } | يحصل أو يضبط النسيج للون الانعكاس |
| [Transparency](../../aspose.threed.shading/pbrmaterial/transparency/) { get; set; } | يحصل أو يضبط عامل الشفافية. يجب أن يكون العامل بين 0 (0٪، غير شفاف تمامًا) و 1 (100٪، شفاف تمامًا). أي قيمة عامل غير صالحة سيتم تقليمها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromMaterial](../../aspose.threed.shading/pbrmaterial/frommaterial/)(Material) | السماح بتحويل مادة أخرى إلى PbrMaterial |
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


