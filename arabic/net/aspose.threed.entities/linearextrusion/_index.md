---
title: "الفئة LinearExtrusion"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Entities.LinearExtrusion الفئة. الاستطالة الخطية تأخذ شكلًا ثنائي الأبعاد كمدخل وتوسّع الشكل في البعد الثالث."
type: docs
weight: 490
url: /ar/net/aspose.threed.entities/linearextrusion/
---
## LinearExtrusion class

الإسقاط الخطي يأخذ شكلًا ثنائي الأبعاد كمدخل ويُمد الشكل في البُعد الثالث.

```csharp
public class LinearExtrusion : Entity, IMeshConvertible
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [LinearExtrusion](linearextrusion/#constructor)() | منشئ المثيل `LinearExtrusion`. |
| [LinearExtrusion](linearextrusion/#constructor_1)(Profile, double) | منشئ المثيل `LinearExtrusion`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Center](../../aspose.threed.entities/linearextrusion/center/) { get; set; } | إذا كانت هذه القيمة خاطئة، يكون نطاق Z للاستطالة الخطية من 0 إلى الارتفاع، وإلا يكون النطاق من -height/2 إلى height/2. |
| [Direction](../../aspose.threed.entities/linearextrusion/direction/) { get; set; } | اتجاه الاستطالة، القيمة الافتراضية هي (0, 0, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [Height](../../aspose.threed.entities/linearextrusion/height/) { get; set; } | ارتفاع الشكل المستخرج، القيمة الافتراضية هي 1.0 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Shape](../../aspose.threed.entities/linearextrusion/shape/) { get; set; } | الشكل الأساسي الذي سيُستطَل. |
| [Slices](../../aspose.threed.entities/linearextrusion/slices/) { get; set; } | شرائح الشكل المستطَل الملتوي، القيمة الافتراضية هي 1. |
| [Twist](../../aspose.threed.entities/linearextrusion/twist/) { get; set; } | عدد الدرجات التي يُستطَل عبرها الشكل. |
| [TwistOffset](../../aspose.threed.entities/linearextrusion/twistoffset/) { get; set; } | الإزاحة المستخدمة في الالتواء، القيمة الافتراضية هي (0, 0, 0). |

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
| [ToMesh](../../aspose.threed.entities/linearextrusion/tomesh/)() | حوّل الاستطالة إلى شبكة. |

## أمثلة

يعرض الشيفرة التالية كيفية استخدام LinearExtrusion لاستطالة شكل إلى نموذج صلب.

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//إنشاء مشهد ثلاثي الأبعاد جديد
Scene scene = new Scene();

// تهيئة ملف التعريف الأساسي ليتم بُثقَه
var profile = new RectangleShape()
{
	RoundingRadius = 0.3
};

// إنشاء العقدة اليسرى
var left = scene.RootNode.CreateChildNode();
left.CreateChildNode(new Box(0.01, 3, 3));

// إنشاء العقدة اليمنى
var right = scene.RootNode.CreateChildNode();
right.CreateChildNode(new Box(0.01, 3, 3));
right.Transform.Translation = new Vector3(5, 0, 0);

//تنفيذ بثق خطي على العقدة اليسرى باستخدام خاصية المركز والشرائح
left.CreateChildNode(new LinearExtrusion(profile, 10) { Center = false, Slices = 3, Twist = 20.0 });

// تنفيذ بثق خطي على العقدة اليسرى باستخدام خاصية المركز والشرائح
right.CreateChildNode(new LinearExtrusion(profile, 10) { Center = true, Slices = 3, Twist = 90.0 });

scene
```

### انظر أيضًا

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


