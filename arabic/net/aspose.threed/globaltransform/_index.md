---
title: "الفئة GlobalTransform"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.GlobalTransform. التحويل العالمي مشابه لـ Transform لكنه ثابت بينما يمثل التحويل النهائي المُقَيم. نظام الإحداثيات الأيمن يُستخدم أثناء تقييم التحويل العالمي"
type: docs
weight: 1560
url: /ar/net/aspose.threed/globaltransform/
---
## GlobalTransform class

التحويل العالمي مشابه لـ [`Transform`](../transform/) لكنه ثابت بينما يمثل التحويل النهائي المُقَيم. نظام الإحداثيات الأيمن يُستخدم أثناء تقييم التحويل العالمي

```csharp
public class GlobalTransform
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EulerAngles](../../aspose.threed/globaltransform/eulerangles/) { get; } | الحصول على الدوران الممثّل بزايا أويلر، مقاسًا بالدرجة |
| [Rotation](../../aspose.threed/globaltransform/rotation/) { get; } | الحصول على الدوران الممثّل بالـ quaternion. |
| [Scale](../../aspose.threed/globaltransform/scale/) { get; } | يحصل على المقياس |
| [TransformMatrix](../../aspose.threed/globaltransform/transformmatrix/) { get; } | يحصل على مصفوفة التحويل. |
| [Translation](../../aspose.threed/globaltransform/translation/) { get; } | يحصل على الإزاحة |

## أمثلة

الكود التالي يوضح كيفية قراءة التحويل العالمي للعقدة

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//ضع الصندوق عند (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### انظر أيضًا

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


