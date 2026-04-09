---
title: الفئة Transform
second_title: مرجع API Aspose.3D لـ .NET
description: فئة Aspose.ThreeD.Transform. يحتوي التحويل على معلومات تسمح بالوصول إلى ترجمة/تحجيم/دوران الكائنات أو مصفوفة التحويل بأقل تكلفة. يُستخدم هذا في التحويل المحلي
type: docs
weight: 2650
url: /ar/net/aspose.threed/transform/
---
## Transform class

يحتوي التحويل على معلومات تسمح بالوصول إلى إزاحة/تحجيم/دوران الكائن أو مصفوفة التحويل بأقل تكلفة. يُستخدم هذا في التحويل المحلي.

```csharp
public class Transform : A3DObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EulerAngles](../../aspose.threed/transform/eulerangles/) { get; set; } | يحصل أو يضبط الدوران الممثل بزايا أويلر، مقاسًا بالدرجة |
| [GeometricRotation](../../aspose.threed/transform/geometricrotation/) { get; set; } | يحصل أو يضبط دوران أويلر الهندسي (مقاسًا بالدرجة). التحويل الهندسي يؤثر فقط على الكيانات المرتبطة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع ملفات لا تدعمه. |
| [GeometricScaling](../../aspose.threed/transform/geometricscaling/) { get; set; } | يحصل أو يضبط التحجيم الهندسي. التحويل الهندسي يؤثر فقط على الكيانات المرتبطة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع ملفات لا تدعمه. |
| [GeometricTranslation](../../aspose.threed/transform/geometrictranslation/) { get; set; } | يحصل أو يضبط الإزاحة الهندسية. التحويل الهندسي يؤثر فقط على الكيانات المرتبطة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع ملفات لا تدعمه. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [PostRotation](../../aspose.threed/transform/postrotation/) { get; set; } | يحصل أو يضبط الدوران اللاحق الممثل بالدرجة |
| [PreRotation](../../aspose.threed/transform/prerotation/) { get; set; } | يحصل أو يضبط الدوران المسبق الممثل بالدرجة |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Rotation](../../aspose.threed/transform/rotation/) { get; set; } | يحصل أو يضبط الدوران الممثل بالـ quaternion. |
| [RotationOffset](../../aspose.threed/transform/rotationoffset/) { get; set; } | الحصول أو تعيين إزاحة الدوران |
| [RotationPivot](../../aspose.threed/transform/rotationpivot/) { get; set; } | الحصول أو تعيين محور الدوران |
| [Scaling](../../aspose.threed/transform/scaling/) { get; set; } | الحصول أو تعيين التحجيم |
| [ScalingOffset](../../aspose.threed/transform/scalingoffset/) { get; set; } | الحصول أو تعيين إزاحة التحجيم |
| [ScalingPivot](../../aspose.threed/transform/scalingpivot/) { get; set; } | الحصول أو تعيين محور التحجيم |
| [TransformMatrix](../../aspose.threed/transform/transformmatrix/) { get; set; } | الحصول أو تعيين مصفوفة التحويل. |
| [Translation](../../aspose.threed/transform/translation/) { get; set; } | الحصول أو تعيين الإزاحة |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [SetEulerAngles](../../aspose.threed/transform/seteulerangles/)(double, double, double) | يضبط زوايا أويلر بالدرجات للتحويل الحالي. |
| [SetGeometricRotation](../../aspose.threed/transform/setgeometricrotation/)(double, double, double) | يضبط دوران أويلر الهندسي (مقاسًا بالدرجة). التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تغيير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه. |
| [SetGeometricScaling](../../aspose.threed/transform/setgeometricscaling/)(double, double, double) | يضبط التحجيم الهندسي. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تغيير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه. |
| [SetGeometricTranslation](../../aspose.threed/transform/setgeometrictranslation/)(double, double, double) | يضبط الإزاحة الهندسية. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تغيير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه. |
| [SetPostRotation](../../aspose.threed/transform/setpostrotation/)(double, double, double) | يضبط ما بعد الدوران الممثل بالدرجة |
| [SetPreRotation](../../aspose.threed/transform/setprerotation/)(double, double, double) | يضبط ما قبل الدوران الممثل بالدرجة |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| [SetRotation](../../aspose.threed/transform/setrotation/)(double, double, double, double) | يضبط الدوران(كمكونات كواترن) للتحويل الحالي. |
| [SetScale](../../aspose.threed/transform/setscale/)(double, double, double) | يضبط مقياس التحويل الحالي. |
| [SetTranslation](../../aspose.threed/transform/settranslation/)(double, double, double) | يضبط إزاحة التحويل الحالي. |

## Examples

الكود التالي يوضح كيفية تغيير تحويل العقدة:

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//ضع الصندوق عند (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### انظر أيضًا

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


