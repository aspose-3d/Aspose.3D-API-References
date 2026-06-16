---
title: "الفئة Cylinder"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.Cylinder. أسطوانة معلمة. يمكن استخدامها أيضًا لتمثيل المخروط عندما يكون أحد القيم radiusTop/radiusBottom صفرًا"
type: docs
weight: 360
url: /ar/net/aspose.threed.entities/cylinder/
---
## Cylinder class

أسطوانة معلمة. يمكن استخدامها أيضًا لتمثيل المخروط عندما يكون أحد القيم radiusTop/radiusBottom صفرًا.

```csharp
public class Cylinder : Primitive
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Cylinder](cylinder/#constructor)() | يُنشئ مثلاً جديداً من الفئة `Cylinder`. |
| [Cylinder](cylinder/#constructor_1)(double, double) | يُنشئ مثلاً جديداً من الفئة `Cylinder`. |
| [Cylinder](cylinder/#constructor_2)(double, double, double) | يُنشئ مثلاً جديداً من الفئة `Cylinder`. |
| [Cylinder](cylinder/#constructor_3)(double, double, double, int, int, bool) | يُنشئ مثلاً جديداً من الفئة `Cylinder`. |
| [Cylinder](cylinder/#constructor_4)(string, double, double, double, int, int, bool, double, double) | يُنشئ مثلاً جديداً من الفئة `Cylinder`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | يحصل أو يضبط ما إذا كان هذا الشكل الهندسي يمكنه إلقاء الظل |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [GenerateFanCylinder](../../aspose.threed.entities/cylinder/generatefancylinder/) { get; set; } | يحصل أو يعيّن ما إذا كان سيتم إنشاء أسطوانة بنمط المروحة عندما يكون ThetaLength أقل من 2*PI، وإلا لن يتم قطع النموذج. |
| [Height](../../aspose.threed.entities/cylinder/height/) { get; set; } | يحصل أو يعيّن ارتفاع الأسطوانة. |
| [HeightSegments](../../aspose.threed.entities/cylinder/heightsegments/) { get; set; } | يحصل أو يضبط مقاطع الارتفاع. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [OffsetBottom](../../aspose.threed.entities/cylinder/offsetbottom/) { get; set; } | يحصل أو يعيّن إزاحة تحويل الرؤوس للجانب السفلي. |
| [OffsetTop](../../aspose.threed.entities/cylinder/offsettop/) { get; set; } | الحصول أو تعيين إزاحة تحويل الرؤوس للجانب العلوي. |
| [OpenEnded](../../aspose.threed.entities/cylinder/openended/) { get; set; } | الحصول أو تعيين قيمة تشير إلى ما إذا كان هذا `Cylinder` مفتوح النهاية. القيمة الافتراضية هي false. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [RadialSegments](../../aspose.threed.entities/cylinder/radialsegments/) { get; set; } | الحصول أو تعيين القطاعات الشعاعية. |
| [RadiusBottom](../../aspose.threed.entities/cylinder/radiusbottom/) { get; set; } | الحصول أو تعيين نصف قطر غطاء أسفل الأسطوانة. |
| [RadiusTop](../../aspose.threed.entities/cylinder/radiustop/) { get; set; } | الحصول أو تعيين نصف قطر غطاء أعلى الأسطوانة. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | يحصل أو يعيّن ما إذا كانت هذه الهندسة يمكنها استقبال الظل. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [ShearBottom](../../aspose.threed.entities/cylinder/shearbottom/) { get; set; } | الحصول أو تعيين تحويل القص للجانب السفلي، المتجه يخزن قيمة القص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0). |
| [ShearTop](../../aspose.threed.entities/cylinder/sheartop/) { get; set; } | الحصول أو تعيين تحويل القص للجانب العلوي، المتجه يخزن قيمة القص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0). |
| [ThetaLength](../../aspose.threed.entities/cylinder/thetalength/) { get; set; } | الحصول أو تعيين طول الثيتا. القيمة الافتراضية هي 2π. |
| [ThetaStart](../../aspose.threed.entities/cylinder/thetastart/) { get; set; } | الحصول أو تعيين بداية الثيتا. القيمة الافتراضية هي 0. |

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
| override [ToMesh](../../aspose.threed.entities/cylinder/tomesh/)() | تحويل الكائن الحالي إلى شبكة |

### انظر أيضًا

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


