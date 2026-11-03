---
title: "Transform.TransformMatrix"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "خاصية Transform. تحصل أو تعين مصفوفة التحويل"
type: docs
weight: 130
url: /ar/net/aspose.threed/transform/transformmatrix/
---
## Transform.TransformMatrix property

تحصل أو تعين مصفوفة التحويل.

```csharp
public Matrix4 TransformMatrix { get; set; }
```

## ملاحظات

التعيين على هذا سيعيد ضبط [`Translation`](../translation/)، [`Scaling`](../scaling/) و[`Rotation`](../rotation/)، بينما لن تتأثر [`GeometricRotation`](../geometricrotation/)، [`GeometricScaling`](../geometricscaling/) و[`GeometricTranslation`](../geometrictranslation/).

## أمثلة

```csharp
Node node = new Node();
node.Transform.TransformMatrix = Matrix4.Identity;
```

### انظر أيضًا

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


