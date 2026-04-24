---
title: فئة SceneObject
second_title: مرجع API Aspose.3D لـ .NET
description: فئة Aspose.ThreeD.SceneObject. الفئة الجذرية للكائنات التي سيتم تخزينها داخل المشهد
type: docs
weight: 2510
url: /ar/net/aspose.threed/sceneobject/
---
## SceneObject class

الفئة الجذرية للكائنات التي سيتم تخزينها داخل المشهد.

```csharp
public abstract class SceneObject : A3DObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SceneObject](sceneobject/#constructor)() | تهيئة كائن SceneObject. |
| [SceneObject](sceneobject/#constructor_1)(string) | تهيئة كائن SceneObject باسم افتراضي |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


