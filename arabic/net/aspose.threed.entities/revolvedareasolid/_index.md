---
title: RevolvedAreaSolid
second_title: Aspose.3D لمرجع .NET API
description: تمثل هذه الفئة نموذجًا صلبًا من خلال تدوير مقطع عرضي يوفره ملف تعريف حول محور.
type: docs
weight: 620
url: /ar/net/aspose.threed.entities/revolvedareasolid/
---
## RevolvedAreaSolid class

تمثل هذه الفئة نموذجًا صلبًا من خلال تدوير مقطع عرضي يوفره ملف تعريف حول محور.

```csharp
public class RevolvedAreaSolid : Entity, IMeshConvertible
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [RevolvedAreaSolid](revolvedareasolid)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AngleEnd](../../aspose.threed.entities/revolvedareasolid/angleend) { get; set; } | الحصول على أو تحديد زاوية نهاية الإجراء الدوار ، مقاسة بالراديان ، والقيمة الافتراضية هي pi . |
| [AngleStart](../../aspose.threed.entities/revolvedareasolid/anglestart) { get; set; } | الحصول على أو تعيين زاوية البداية للإجراء الدوار ، المقاسة بالراديان ، والقيمة الافتراضية هي 0. |
| [Axis](../../aspose.threed.entities/revolvedareasolid/axis) { get; set; } | الحصول على أو تحديد اتجاه المحور ، القيمة الافتراضية هي (0 ، 1 ، 0) . |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | الحصول على أو تعيين ما إذا كان سيتم استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | الحصول على الاسم أو تعيينه . |
| [Origin](../../aspose.threed.entities/revolvedareasolid/origin) { get; set; } | الحصول على أو تحديد نقطة الأصل للدوران ، القيمة الافتراضية هي (0 ، 0 ، 0) . |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | الحصول على العقدة الأصلية الأولى أو تعيينها ، إذا تم تعيين العقدة الأصلية الأولى ، فسيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | للحصول على جميع العقد الأصلية ، يمكن إرفاق كيان بالعقد الأصلية المتعددة من أجل هندسة instancing |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | الحصول على مجموعة من كافة الخصائص . |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Shape](../../aspose.threed.entities/revolvedareasolid/shape) { get; set; } | الحصول على أو تعيين ملف التعريف الأساسي المستخدم للدوران. |

## طُرق

| اسم | وصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | البحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (تم إنشاؤها بواسطة CreateDynamicProperty / SetProperty) أو خاصية أصلية (محددة باسمها) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | الحصول على المربع المحيط للكيان الحالي في نظام إحداثيات مساحة الكائن. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey)() | الحصول على مفتاح عارض الكيان المسجل في العارض |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | الحصول على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | يزيل خاصية ديناميكية . |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | إزالة الخاصية المحددة المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | يحدد قيمة الخاصية المحددة |
| [ToMesh](../../aspose.threed.entities/revolvedareasolid/tomesh)() | تحويل ملف[`RevolvedAreaSolid`](../revolvedareasolid) في شبكة . |

### أنظر أيضا

* class [Entity](../../aspose.threed/entity)
* interface [IMeshConvertible](../imeshconvertible)
* مساحة الاسم [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* المجسم [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->