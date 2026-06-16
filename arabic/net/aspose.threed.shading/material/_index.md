---
title: "الفئة Material"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Shading.Material. المادة تعرف المعلمات اللازمة للمظهر البصري للهندسة. Aspose.3D توفر نموذج الظل لـ LambertMaterial و PhongMaterial و ShaderMaterial"
type: docs
weight: 2540
url: /ar/net/aspose.threed.shading/material/
---
## Material class

المادة تعرف المعلمات اللازمة للمظهر البصري للهندسة. Aspose.3D توفر نموذج الظل لـ [`LambertMaterial`](../lambertmaterial/)، [`PhongMaterial`](../phongmaterial/) و [`ShaderMaterial`](../shadermaterial/)

```csharp
public abstract class Material : A3DObject, IEnumerable<TextureSlot>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |

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
| const [MapAmbient](../../aspose.threed.shading/material/mapambient/) | يُستخدم في [`SetTexture`](./settexture/) لتعيين خريطة نسيج محيطي. |
| const [MapDiffuse](../../aspose.threed.shading/material/mapdiffuse/) | يُستخدم في [`SetTexture`](./settexture/) لتعيين خريطة نسيج انتشارية. |
| const [MapEmissive](../../aspose.threed.shading/material/mapemissive/) | يُستخدم في [`SetTexture`](./settexture/) لتعيين خريطة نسيج مضيئة. |
| const [MapNormal](../../aspose.threed.shading/material/mapnormal/) | يُستخدم في [`SetTexture`](./settexture/) لتعيين خريطة نسيج عادية. |
| const [MapSpecular](../../aspose.threed.shading/material/mapspecular/) | يُستخدم في [`SetTexture`](./settexture/) لتعيين خريطة نسيج انعكاسية. |

## أمثلة

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
foreach(var slot in mat)
{
    Console.WriteLine($"Texture slot {slot.SlotName} = {slot.Texture}");
}
```

### انظر أيضًا

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [TextureSlot](../textureslot/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


