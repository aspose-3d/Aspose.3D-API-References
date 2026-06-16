---
title: "الفئة RevolvedAreaSolid"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.RevolvedAreaSolid. هذه الفئة تمثل نموذجًا صلبًا عن طريق تدوير مقطع عرضي موفر بواسطة ملف تعريف حول محور"
type: docs
weight: 680
url: /ar/net/aspose.threed.entities/revolvedareasolid/
---
## RevolvedAreaSolid class

هذه الفئة تمثل نموذجًا صلبًا عن طريق تدوير مقطع عرضي مُقدَّم بواسطة ملف حول محور.

```csharp
public class RevolvedAreaSolid : Entity, IMeshConvertible
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [RevolvedAreaSolid](revolvedareasolid/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AngleEnd](../../aspose.threed.entities/revolvedareasolid/angleend/) { get; set; } | يحصل أو يضبط زاوية النهاية لإجراء التدوير، مقاسة بالراديان، القيمة الافتراضية هي π. |
| [AngleStart](../../aspose.threed.entities/revolvedareasolid/anglestart/) { get; set; } | يحصل أو يضبط زاوية البداية لإجراء التدوير، مقاسة بالراديان، القيمة الافتراضية هي 0. |
| [Axis](../../aspose.threed.entities/revolvedareasolid/axis/) { get; set; } | يحصل أو يضبط اتجاه المحور، القيمة الافتراضية هي (0, 1, 0). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Origin](../../aspose.threed.entities/revolvedareasolid/origin/) { get; set; } | يحصل أو يعيّن نقطة الأصل للدوران، القيمة الافتراضية هي (0, 0, 0). |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Shape](../../aspose.threed.entities/revolvedareasolid/shape/) { get; set; } | يحصل أو يعيّن ملف التعريف الأساسي المستخدم للدوران. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| [ToMesh](../../aspose.threed.entities/revolvedareasolid/tomesh/)() | تحويل الـ `RevolvedAreaSolid` إلى شبكة. |

## أمثلة

الكود التالي يوضح كيفية استخدام RevolvedAreaSolid لدوران شكل إلى نموذج صلب.

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//إنشاء مشهد ثلاثي الأبعاد جديد
Scene scene = new Scene();

// تهيئة ملف التعريف الأساسي ليتم تدويره
var profile = new RectangleShape()
{
    RoundingRadius = 0.3
};
//إنشاء نسخة من RevolvedAreaSolid 
var revolved = new RevolvedAreaSolid()
{
  Shape = profile,
  Origin = new Vector3(1, 0, 0),
  AngleStart = 0,
  AngleEnd = Math.PI
};
scene.RootNode.CreateChildNode(revolved);

scene.Save("revolved.obj");
```

```csharp
//إنشاء مشهد ثلاثي الأبعاد جديد
Scene scene = new Scene();

// تهيئة ملف التعريف الأساسي ليتم بُثقَه
var profile = new RectangleShape();
profile.setRoundingRadius(0.3);

var revolved = new RevolvedAreaSolid();
revolved.setShape(profile);
revolved.setOrigin(new Vector3(1, 0, 0));
revolved.setAngleStart(0);
revolved.setAngleEnd(Math.PI);
scene.getRootNode().createChildNode(revolved);

scene.save("revolved.obj");
```

### انظر أيضًا

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


