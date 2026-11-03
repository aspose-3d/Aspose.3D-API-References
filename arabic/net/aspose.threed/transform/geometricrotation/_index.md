---
title: "Transform.GeometricRotation"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "خاصية Transform. يحصل أو يضبط دوران أويلر الهندسي المقاس بالدرجة. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع ملفات لا تدعم ذلك"
type: docs
weight: 20
url: /ar/net/aspose.threed/transform/geometricrotation/
---
## Transform.GeometricRotation property

يحصل أو يضبط دوران أويلر الهندسي (مقاس بالدرجة). التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع ملفات لا تدعم ذلك.

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


