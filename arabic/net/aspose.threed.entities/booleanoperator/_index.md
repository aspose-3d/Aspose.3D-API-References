---
title: الفئة BooleanOperator
second_title: مرجع API Aspose.3D لـ .NET
description: Aspose.ThreeD.Entities.BooleanOperator class. يسمح المشغل البولياني لك بتطبيق عملية بوليانية على مثيلين من IMeshConvertible
type: docs
weight: 280
url: /ar/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

يسمح المشغل البولياني لك بتطبيق عملية بوليانية على مثيلين من [`IMeshConvertible`](../imeshconvertible/).

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | منشئ `BooleanOperator` |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | ينشئ مثيلًا جديدًا من `BooleanOperator` بمعاملين |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | المعامل الأول للمعامل البولياني |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | المعامل البولياني المستخدم في العملية لإنشاء شبكة النتيجة. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يضبط العقدة الأب الأولى، إذا تم تعيين العقدة الأب الأولى، سيتم فصل هذا الكيان عن باقي العقد الأبوية. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | المعامل الثاني للمعامل البولياني |

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
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | نفّذ العملية البوليانية على معاملين |

### انظر أيضًا

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


