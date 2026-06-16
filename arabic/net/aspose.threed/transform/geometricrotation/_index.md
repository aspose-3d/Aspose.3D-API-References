---
title: "Transform.GeometricRotation"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية Transform. تحصل أو تعين دوران أويلر الهندسي مقاسًا بالدرجة. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه"
type: docs
weight: 20
url: /ar/net/aspose.threed/transform/geometricrotation/
---
## Transform.GeometricRotation property

يحصل أو يعيّن دوران أويلر الهندسي (مقاسًا بالدرجة). التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع ملفات لا تدعم ذلك

```csharp
public Vector3 GeometricRotation { get; set; }
```

## أمثلة

```csharp
Node node = new Node();
node.getTransform().setGeometricRotation(new Vector3(90, 0, 0));
```

### انظر أيضًا

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


