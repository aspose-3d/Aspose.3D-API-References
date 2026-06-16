---
title: "الفئة Light"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Entities.Light. الضوء يضيء المشهد"
type: docs
weight: 460
url: /ar/net/aspose.threed.entities/light/
---
## Light class

الضوء يضيء المشهد.

الصيغة لحساب التوهين الكلي للضوء هي: `A = ConstantAttenuation + (Dist * LinearAttenuation) + ((Dist^2) * QuadraticAttenuation)`

```csharp
public class Light : Frustum
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Light](light/#constructor)() | يُنشئ نسخة جديدة من الفئة `Light`. |
| [Light](light/#constructor_1)(string) | يُنشئ نسخة جديدة من الفئة `Light`. |
| [Light](light/#constructor_2)(string, LightType) | يُنشئ نسخة جديدة من الفئة `Light`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | الحصول على أو تعيين نسبة العرض إلى الارتفاع للمخروط. |
| [CastLight](../../aspose.threed.entities/light/castlight/) { get; set; } | الحصول على أو تعيين ما إذا كان مثال الضوء الحالي يمكنه إضاءة كائنات أخرى. |
| [CastShadows](../../aspose.threed.entities/light/castshadows/) { get; set; } | يحصل أو يضبط ما إذا كان الضوء يمكنه إلقاء ظلال على كائنات أخرى. |
| [Color](../../aspose.threed.entities/light/color/) { get; set; } | يحصل أو يضبط لون الضوء |
| [ConstantAttenuation](../../aspose.threed.entities/light/constantattenuation/) { get; set; } | يحصل أو يضبط التوهين الثابت لحساب التوهين الكلي للضوء |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | يحصل أو يضبط الاتجاه الذي تنظر إليه الكاميرا. التغييرات على هذه الخاصية ستؤثر أيضًا على [`LookAt`](../frustum/lookat/) و [`Target`](../frustum/target/). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [Falloff](../../aspose.threed.entities/light/falloff/) { get; set; } | يحصل أو يضبط زاوية مخروط التلاشي (بالدرجات). |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | يحصل أو يضبط مسافة المستوى البعيد للمقاطع. |
| [HotSpot](../../aspose.threed.entities/light/hotspot/) { get; set; } | يحصل أو يضبط زاوية مخروط النقطة الساخنة (بالدرجات). |
| [Intensity](../../aspose.threed.entities/light/intensity/) { get; set; } | يحصل أو يضبط شدة الضوء، القيمة الافتراضية هي 100 |
| [LightType](../../aspose.threed.entities/light/lighttype/) { get; set; } | يحصل أو يضبط نوع الضوء |
| [LinearAttenuation](../../aspose.threed.entities/light/linearattenuation/) { get; set; } | يحصل أو يضبط التوهين الخطي لحساب التوهين الكلي للضوء |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | يحصل أو يضبط الموضع المستهدف الذي تنظر إليه الكاميرا. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | يحصل أو يضبط مسافة المستوى القريب للمقاطع. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | يحصل أو يضبط الارتفاع عندما يكون المقاطع في الإسقاط المتعامد. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [QuadraticAttenuation](../../aspose.threed.entities/light/quadraticattenuation/) { get; set; } | يحصل أو يضبط التوهين التربيعي لحساب التوهين الكلي للضوء |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | يحصل أو يضبط وضعية توجيه المقاطع. هذه الخاصية تعمل فقط عندما يكون [`Target`](../frustum/target/) فارغًا. إذا كانت القيمة FixedTarget، يتم دائمًا حساب الاتجاه بواسطة الخاصية [`LookAt`](../frustum/lookat/). وإلا فإن [`LookAt`](../frustum/lookat/) يتم دائمًا حسابه بواسطة [`Direction`](../frustum/direction/). |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [ShadowColor](../../aspose.threed.entities/light/shadowcolor/) { get; set; } | يحصل أو يضبط لون الظل. |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | يحصل أو يضبط الهدف الذي تنظر إليه الكاميرا. إذا كان المستخدم يدعم هذه الخاصية، يجب أن تكون قبل خاصية [`LookAt`](../frustum/lookat/). |
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

* class [Frustum](../frustum/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


