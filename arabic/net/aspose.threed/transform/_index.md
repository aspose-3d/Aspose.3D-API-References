---
title: "الفئة Transform"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Transform. يحتوي التحويل على معلومات تسمح بالوصول إلى كائنات الترجمة/التحجيم/الدوران أو مصفوفة التحويل بأقل تكلفة. يُستخدم هذا بواسطة التحويل المحلي"
type: docs
weight: 2650
url: /ar/net/aspose.threed/transform/
---
## Transform class

يحتوي التحويل على معلومات تسمح بالوصول إلى ترجمة/تحجيم/دوران الكائن أو مصفوفة التحويل بأقل تكلفة. يُستخدم هذا في التحويل المحلي.

```csharp
public class Transform : A3DObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EulerAngles](../../aspose.threed/transform/eulerangles/) { get; set; } | يحصل أو يعيّن الدوران الممثّل بزاويا أويلر، مقاسًا بالدرجة |
| [GeometricRotation](../../aspose.threed/transform/geometricrotation/) { get; set; } | يحصل أو يعيّن دوران أويلر الهندسي (مقاسًا بالدرجة). التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع ملفات لا تدعم ذلك |
| [GeometricScaling](../../aspose.threed/transform/geometricscaling/) { get; set; } | يحصل أو يعيّن التحجيم الهندسي. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع ملفات لا تدعم ذلك |
| [GeometricTranslation](../../aspose.threed/transform/geometrictranslation/) { get; set; } | يحصل أو يعيّن الترجمة الهندسية. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع ملفات لا تدعم ذلك |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [PostRotation](../../aspose.threed/transform/postrotation/) { get; set; } | يحصل أو يعيّن الدوران اللاحق الممثّل بالدرجة |
| [PreRotation](../../aspose.threed/transform/prerotation/) { get; set; } | يحصل أو يعيّن الدوران السابق الممثّل بالدرجة |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Rotation](../../aspose.threed/transform/rotation/) { get; set; } | يحصل أو يعيّن الدوران الممثّل بالكواترنيون. |
| [RotationOffset](../../aspose.threed/transform/rotationoffset/) { get; set; } | يحصل أو يعيّن إزاحة الدوران |
| [RotationPivot](../../aspose.threed/transform/rotationpivot/) { get; set; } | يحصل أو يعيّن محور الدوران |
| [Scaling](../../aspose.threed/transform/scaling/) { get; set; } | يحصل أو يعيّن التحجيم |
| [ScalingOffset](../../aspose.threed/transform/scalingoffset/) { get; set; } | يحصل أو يعيّن إزاحة التحجيم |
| [ScalingPivot](../../aspose.threed/transform/scalingpivot/) { get; set; } | يحصل أو يعيّن محور التحجيم |
| [TransformMatrix](../../aspose.threed/transform/transformmatrix/) { get; set; } | يحصل أو يعيّن مصفوفة التحويل. |
| [Translation](../../aspose.threed/transform/translation/) { get; set; } | يحصل أو يعيّن الترجمة |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetEulerAngles](../../aspose.threed/transform/seteulerangles/)(double, double, double) | يضبط زوايا أويلر بالدرجات للتحويل الحالي. |
| [SetGeometricRotation](../../aspose.threed/transform/setgeometricrotation/)(double, double, double) | يضبط دوران أويلر الهندسي (مقاسًا بالدرجة). التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع ملفات لا تدعم ذلك |
| [SetGeometricScaling](../../aspose.threed/transform/setgeometricscaling/)(double, double, double) | يضبط التحجيم الهندسي. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع ملفات لا تدعم ذلك |
| [SetGeometricTranslation](../../aspose.threed/transform/setgeometrictranslation/)(double, double, double) | يضبط الترجمة الهندسية. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع ملفات لا تدعم ذلك |
| [SetPostRotation](../../aspose.threed/transform/setpostrotation/)(double, double, double) | يضبط الدوران اللاحق الممثّل بالدرجة |
| [SetPreRotation](../../aspose.threed/transform/setprerotation/)(double, double, double) | يضبط الدوران السابق الممثّل بالدرجة |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| [SetRotation](../../aspose.threed/transform/setrotation/)(double, double, double, double) | يضبط الدوران (كمكوّنات كواترنيون) للتحويل الحالي. |
| [SetScale](../../aspose.threed/transform/setscale/)(double, double, double) | يضبط مقياس التحويل الحالي. |
| [SetTranslation](../../aspose.threed/transform/settranslation/)(double, double, double) | يضبط ترجمة التحويل الحالي. |

## أمثلة

يعرض الكود التالي كيفية تغيير تحويل العقدة:

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


