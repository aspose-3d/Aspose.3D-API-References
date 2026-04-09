---
title: فئة Entity
second_title: مرجع API Aspose.3D لـ .NET
description: فئة Aspose.ThreeD.Entity. الفئة الأساسية لجميع الكيانات. تمثل Entity كائنًا ملموسًا يتم ربطه تحت عقدة مثل Light/Geometry
type: docs
weight: 1030
url: /ar/net/aspose.threed/entity/
---
## Entity class

الفئة الأساسية لجميع الكيانات. تمثل Entity كائنًا ملموسًا يتم ربطه تحت عقدة مثل [`Light`](../../aspose.threed.entities/light/)/[`Geometry`](../../aspose.threed.entities/geometry/).

```csharp
public abstract class Entity : SceneObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Entity](entity/)(string) | يُنشئ مثيلًا جديدًا من الفئة `Entity`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يضبط العقدة الأب الأولى، إذا تم تعيين العقدة الأب الأولى، سيتم فصل هذا الكيان عن باقي العقد الأبوية. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة. |
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

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


