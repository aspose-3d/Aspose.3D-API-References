---
title: الفئة Group
second_title: مرجع API Aspose.3D لـ .NET
description: فئة Aspose.ThreeD.Group. تمثل Group العلاقات المنطقية لـ Node
type: docs
weight: 1570
url: /ar/net/aspose.threed/group/
---
## Group class

`Group` تمثل العلاقات المنطقية لـ [`Node`](../node/).

```csharp
public class Group : A3DObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Group](group/)(string) | إنشاء مثيل جديد من `Group` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Groups](../../aspose.threed/group/groups/) { get; } | المجموعات الفرعية |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Nodes](../../aspose.threed/group/nodes/) { get; } | العقد في هذه المجموعة |
| [Parent](../../aspose.threed/group/parent/) { get; } | المجموعة الأصلية للمجموعة الحالية |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| override [ToString](../../aspose.threed/group/tostring/)() | يحصل على تمثيل السلسلة لـ `Group` |

### انظر أيضًا

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


