---
title: فئة HalfSpace
second_title: مرجع API Aspose.3D لـ .NET
description: Aspose.ThreeD.Entities.HalfSpace class. يمثل HalfSpace مساحة لا نهائية يتم تقسيمها بواسطة مستوى يمكن استخدامه مع BooleanOperator
type: docs
weight: 420
url: /ar/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` يمثل مساحة لا نهائية يتم تقسيمها بواسطة مستوى، يمكن استخدامه مع [`BooleanOperator`](../booleanoperator/)

```csharp
public class HalfSpace : Entity
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | ينشئ مثيلاً جديدًا من `HalfSpace` |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | ينشئ مثيلاً جديدًا من `HalfSpace` مع متجه عمودي معطى وموقع على مستوى القطع؛ |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | المتجه العمودي للمستوى المقسّم، يُعرّف المستوى كـ N * P + D = 0 حيث N هو المتجه العمودي وP هو أي نقطة على المستوى. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يضبط العقدة الأب الأولى، إذا تم تعيين العقدة الأب الأولى، سيتم فصل هذا الكيان عن باقي العقد الأبوية. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة. |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | أي نقطة على المستوى المقسّم، يُعرّف المستوى كـ N * P + D = 0 حيث N هو المتجه العمودي وP هو أي نقطة على المستوى. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


