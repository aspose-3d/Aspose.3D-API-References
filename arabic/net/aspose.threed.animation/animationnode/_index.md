---
title: "الفئة AnimationNode"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Animation.AnimationNode. يدعم Aspose.3Ds هيكلية الرسوم المتحركة حيث يمكن تكوين كل حركة من عدة حركات وتعريف إطارات المفاتيح الخاصة بها. يحدد AnimationNode تحويل قيمة خاصية ما عبر الزمن؛ على سبيل المثال يمكن استخدام عقدة الحركة للتحكم في تحويل عقدة أو الخصائص الرقمية لكائنات A3DObject الأخرى."
type: docs
weight: 40
url: /ar/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

يدعم Aspose.3D هيكلية الرسوم المتحركة، حيث يمكن تكوين كل حركة من عدة حركات وتعريف إطارات المفاتيح الخاصة بها. يحدد `AnimationNode` تحويل قيمة خاصية ما عبر الزمن؛ على سبيل المثال يمكن استخدام عقدة الحركة للتحكم في تحويل عقدة أو الخصائص الرقمية لكائن [`A3DObject`](../../aspose.threed/a3dobject/) آخر.

```csharp
public class AnimationNode : A3DObject
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [AnimationNode](animationnode/#constructor)() | ينشئ مثيلًا جديدًا للفئة `AnimationNode`. |
| [AnimationNode](animationnode/#constructor_1)(string) | ينشئ مثيلًا جديدًا للفئة `AnimationNode`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints/) { get; } | يحصل على نقاط ربط الخاصية الحالية. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations/) { get; } | يحصل على عقد الرسوم المتحركة الفرعية تحت الرسوم المتحركة الحالية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint/)(A3DObject, string) | ينشئ BindPoint بناءً على نوع بيانات الخاصية. |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint/)(A3DObject, string) | يبحث عن نقطة الربط حسب الهدف والاسم. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint/)(A3DObject, string, bool) | يحصل على نقطة ربط الرسوم المتحركة للخاصية المحددة. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence)(A3DObject, string, bool) | يحصل على تسلسل الإطار الرئيسي للخاصية المحددة. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence_1)(A3DObject, string, string, bool) | يحصل على تسلسل الإطار الرئيسي للخاصية والقناة المحددة. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


