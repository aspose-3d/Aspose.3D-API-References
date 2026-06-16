---
title: "فئة HalfSpace"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Entities.HalfSpace فئة. تمثل HalfSpace مساحة لا نهائية تُقسم بواسطة مستوى ويمكن استخدامها مع BooleanOperator"
type: docs
weight: 420
url: /ar/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` يمثل مساحة لا نهائية يتم تقسيمها بواسطة مستوى، يمكن استخدام ذلك مع [`BooleanOperator`](../booleanoperator/)

```csharp
public class HalfSpace : Entity
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | ينشئ مثيلاً جديدًا من `HalfSpace` |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | ينشئ مثيلاً جديدًا من `HalfSpace` باستخدام متجه العمودي المعطى وموقع على مستوى القطع؛ |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | متجه العمودي للمستوى المقسَّم، يُعرَّف المستوى بالمعادلة N * P + D = 0 حيث N هو المتجه العمودي وP هو أي نقطة على المستوى. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | أي نقطة على المستوى المقسَّم، يُعرَّف المستوى بالمعادلة N * P + D = 0 حيث N هو المتجه العمودي وP هو أي نقطة على المستوى. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |

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
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


