---
title: PhongMaterial
second_title: Aspose.3D لمرجع .NET API
description: مادة لنموذج التظليل blinnphong .
type: docs
weight: 2320
url: /ar/net/aspose.threed.shading/phongmaterial/
---
## PhongMaterial class

مادة لنموذج التظليل blinn-phong .

```csharp
public class PhongMaterial : LambertMaterial
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PhongMaterial](phongmaterial#constructor)() | يقوم بتهيئة مثيل جديد لملف[`PhongMaterial`](../phongmaterial) فئة . |
| [PhongMaterial](phongmaterial#constructor_1)(string) | يقوم بتهيئة مثيل جديد لملف[`PhongMaterial`](../phongmaterial) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor) { get; set; } | الحصول على أو تعيين اللون المحيط |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor) { get; set; } | الحصول على أو تعيين اللون المنتشر |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor) { get; set; } | الحصول على أو تعيين اللون المنبعث |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | الحصول على الاسم أو تعيينه . |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | الحصول على مجموعة من كافة الخصائص . |
| [ReflectionColor](../../aspose.threed.shading/phongmaterial/reflectioncolor) { get; set; } | الحصول على لون الانعكاس أو تعيينه. |
| [ReflectionFactor](../../aspose.threed.shading/phongmaterial/reflectionfactor) { get; set; } | الحصول على أو تحديد توهين لون الانعكاس. |
| [Shininess](../../aspose.threed.shading/phongmaterial/shininess) { get; set; } | الحصول على اللمعان أو ضبطه ، وهذا يتحكم في حجم الإبراز المرآوي. صيغة البريق: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [SpecularColor](../../aspose.threed.shading/phongmaterial/specularcolor) { get; set; } | الحصول على اللون المميز أو تحديده. |
| [SpecularFactor](../../aspose.threed.shading/phongmaterial/specularfactor) { get; set; } | الحصول على أو تحديد العامل المرآوي. صيغة المرآوية: SpecularColor * SpecularFactor * (N نقطة H) ^ Shininess |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency) { get; set; } | الحصول على عامل الشفافية أو تعيينه . يجب أن يتراوح العامل بين 0 (0٪ ، معتم تمامًا) و 1 (100٪ ، شفاف تمامًا) سيتم تثبيت أي قيمة غير صالحة للعامل . |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor) { get; set; } | الحصول على اللون الشفاف أو تعيينه. |

## طُرق

| اسم | وصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | البحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (تم إنشاؤها بواسطة CreateDynamicProperty / SetProperty) أو خاصية أصلية (محددة باسمها) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator)() | الحصول على العداد لتعداد فتحات النسيج الداخلي. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | الحصول على قيمة الخاصية المحددة |
| [GetTexture](../../aspose.threed.shading/material/gettexture)(string) | الحصول على النسيج من الفتحة المحددة ، يمكن أن يكون اسم خاصية المادة أو اسم معلمة shader |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | يزيل خاصية ديناميكية . |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | إزالة الخاصية المحددة المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | يحدد قيمة الخاصية المحددة |
| [SetTexture](../../aspose.threed.shading/material/settexture)(string, TextureBase) | يضبط النسيج على slot |
| override [ToString](../../aspose.threed.shading/material/tostring)() | كائن تنسيقات إلى string |

### أنظر أيضا

* class [LambertMaterial](../lambertmaterial)
* مساحة الاسم [Aspose.ThreeD.Shading](../../aspose.threed.shading)
* المجسم [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
