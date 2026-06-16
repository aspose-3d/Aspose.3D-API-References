---
title: "الفئة Frustum"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.Frustum. الفئة الأساسية للكاميرا والإضاءة"
type: docs
weight: 400
url: /ar/net/aspose.threed.entities/frustum/
---
## Frustum class

الفئة الأساسية لـ [`Camera`](../camera/) و [`Light`](../light/)

```csharp
public abstract class Frustum : Entity, IOrientable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | الحصول على أو تعيين نسبة العرض إلى الارتفاع للمخروط. |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | يحصل أو يضبط الاتجاه الذي تنظر إليه الكاميرا. التغييرات في هذه الخاصية ستؤثر أيضًا على [`LookAt`](./lookat/) و [`Target`](./target/). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | يحصل أو يضبط مسافة المستوى البعيد للمقاطع. |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | يحصل أو يضبط الموضع المستهدف الذي تنظر إليه الكاميرا. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | يحصل أو يضبط مسافة المستوى القريب للمقاطع. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | يحصل أو يضبط الارتفاع عندما يكون المقاطع في الإسقاط المتعامد. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | يحصل أو يضبط وضعية توجيه الـ frustum. هذه الخاصية تعمل فقط عندما يكون [`Target`](./target/) فارغًا. إذا كانت القيمة FixedTarget، يتم دائمًا حساب الاتجاه بواسطة الخاصية [`LookAt`](./lookat/). وإلا يتم دائمًا حساب [`LookAt`](./lookat/) بواسطة [`Direction`](./direction/). |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | يحصل أو يضبط الهدف الذي تنظر إليه الكاميرا. إذا كان المستخدم يدعم هذه الخاصية، يجب أن تكون قبل خاصية [`LookAt`](./lookat/). |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | يحصل أو يضبط اتجاه الأعلى للكاميرا |

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

### انظر أيضًا

* class [Entity](../../aspose.threed/entity/)
* interface [IOrientable](../iorientable/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


