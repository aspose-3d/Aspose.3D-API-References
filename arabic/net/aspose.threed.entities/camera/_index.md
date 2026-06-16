---
title: "الفئة Camera"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Entities.Camera. تصف الكاميرا نقطة نظر المشاهد التي تنظر إلى المشهد"
type: docs
weight: 300
url: /ar/net/aspose.threed.entities/camera/
---
## Camera class

الكاميرا تصف نقطة عين المشاهد التي تنظر إلى المشهد.

```csharp
public class Camera : Frustum
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Camera](camera/#constructor)() | يُنشئ مثلاً جديداً من الفئة `Camera`. |
| [Camera](camera/#constructor_1)(ProjectionType) | يُنشئ مثلاً جديداً من الفئة `Camera`. |
| [Camera](camera/#constructor_2)(string) | يُنشئ مثلاً جديداً من الفئة `Camera`. |
| [Camera](camera/#constructor_3)(string, ProjectionType) | يُنشئ مثلاً جديداً من الفئة `Camera`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ApertureMode](../../aspose.threed.entities/camera/aperturemode/) { get; set; } | يحصل أو يعيّن وضع فتحة الكاميرا |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | الحصول على أو تعيين نسبة العرض إلى الارتفاع للمخروط. |
| [AspectRatio](../../aspose.threed.entities/camera/aspectratio/) { get; set; } | يحصل أو يعيّن نسبة أبعاد مستوى العرض. |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | يحصل أو يضبط الاتجاه الذي تنظر إليه الكاميرا. التغييرات على هذه الخاصية ستؤثر أيضًا على [`LookAt`](../frustum/lookat/) و [`Target`](../frustum/target/). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | يحصل أو يضبط مسافة المستوى البعيد للمقاطع. |
| [FieldOfView](../../aspose.threed.entities/camera/fieldofview/) { get; set; } | يحصل أو يعيّن مجال رؤية الكاميرا بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode أفقيًا أو عموديًا |
| [FieldOfViewX](../../aspose.threed.entities/camera/fieldofviewx/) { get; set; } | يحصل أو يعيّن المجال الأفقي لرؤية الكاميرا بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode HorizAndVert |
| [FieldOfViewY](../../aspose.threed.entities/camera/fieldofviewy/) { get; set; } | يحصل أو يعيّن المجال العمودي لرؤية الكاميرا بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode HorizAndVert |
| [Height](../../aspose.threed.entities/camera/height/) { get; set; } | يحصل أو يعيّن ارتفاع مستوى العرض مقاسًا بالبوصة |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | يحصل أو يضبط الموضع المستهدف الذي تنظر إليه الكاميرا. |
| [Magnification](../../aspose.threed.entities/camera/magnification/) { get; set; } | يحصل أو يعيّن التكبير المستخدم في الكاميرا المتعامدة |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | يحصل أو يضبط مسافة المستوى القريب للمقاطع. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | يحصل أو يضبط الارتفاع عندما يكون المقاطع في الإسقاط المتعامد. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [ProjectionType](../../aspose.threed.entities/camera/projectiontype/) { get; set; } | يحصل أو يعيّن نوع إسقاط الكاميرا. بشكل افتراضي يُستخدم الإسقاط المنظوري. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | يحصل أو يضبط وضعية توجيه المقاطع. هذه الخاصية تعمل فقط عندما يكون [`Target`](../frustum/target/) فارغًا. إذا كانت القيمة FixedTarget، يتم دائمًا حساب الاتجاه بواسطة الخاصية [`LookAt`](../frustum/lookat/). وإلا فإن [`LookAt`](../frustum/lookat/) يتم دائمًا حسابه بواسطة [`Direction`](../frustum/direction/). |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | يحصل أو يضبط الهدف الذي تنظر إليه الكاميرا. إذا كان المستخدم يدعم هذه الخاصية، يجب أن تكون قبل خاصية [`LookAt`](../frustum/lookat/). |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | يحصل أو يضبط اتجاه الأعلى للكاميرا |
| [Width](../../aspose.threed.entities/camera/width/) { get; set; } | يحصل أو يعيّن عرض مستوى العرض مقاسًا بالبوصة |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [MoveForward](../../aspose.threed.entities/camera/moveforward/)(double) | حرك الكاميرا إلى الأمام باتجاه اتجاهها أو هدفها. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

### انظر أيضًا

* class [Frustum](../frustum/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


