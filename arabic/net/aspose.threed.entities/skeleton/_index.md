---
title: "الفئة Skeleton"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.Skeleton. الهيكل العظمي يُستخدم أساساً من قبل برامج CAD لمساعدة المصمم على تعديل تحويلات الهيكل العظمي، وهو عادةً غير مفيد خارج برامج CAD. لجعل تسلسل الهيكل العظمي يعمل ككائن واحد في برنامج CAD، من الضروري وضع علامة على عقدة الهيكل العظمي العليا كجذر عن طريق تعيين النوع إلى Skeleton وتعيين جميع الأطفال إلى Bone."
type: docs
weight: 710
url: /ar/net/aspose.threed.entities/skeleton/
---
## Skeleton class

يُستخدم `Skeleton` أساسًا من قبل برامج CAD لمساعدة المصمم على تعديل تحويل الهيكل العظمي، وهو عادةً غير مفيد خارج برامج CAD. لجعل تسلسل هيكل العظام يعمل ككائن واحد في برنامج CAD، من الضروري تعيين عقدة `Skeleton` العليا كجذر عن طريق ضبط [`Type`](./type/) إلى Skeleton، وتعيين جميع الأطفال إلى Bone.

```csharp
public class Skeleton : Entity
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Skeleton](skeleton/#constructor)() | ينشئ مثيلًا جديدًا من الفئة `Skeleton`. |
| [Skeleton](skeleton/#constructor_1)(string) | ينشئ مثيلًا جديدًا من الفئة `Skeleton`. |
| [Skeleton](skeleton/#constructor_2)(string, SkeletonType) | ينشئ مثيلًا جديدًا من الفئة `Skeleton`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Size](../../aspose.threed.entities/skeleton/size/) { get; set; } | يحصل أو يضبط حجم عقدة الطرف المستخدمة في برامج CAD لتمثيل حجم العظم. |
| [Type](../../aspose.threed.entities/skeleton/type/) { get; set; } | يحصل أو يضبط نوع الهيكل العظمي. |

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


