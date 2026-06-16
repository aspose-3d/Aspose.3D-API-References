---
title: "Node.EvaluateGlobalTransform"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Node. تقييم التحويل العالمي تشمل التحويل الهندسي أم لا"
type: docs
weight: 180
url: /ar/net/aspose.threed/node/evaluateglobaltransform/
---
## Node.EvaluateGlobalTransform method

تقييم التحويل العالمي، تضمين التحويل الهندسي أم لا.

```csharp
public Matrix4 EvaluateGlobalTransform(bool withGeometricTransform)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| withGeometricTransform | Boolean | ما إذا كان التحويل الهندسي مطلوبًا. |

### قيمة الإرجاع

مصفوفة التحويل العالمي.

## أمثلة

يعرض الكود التالي كيفية قراءة مصفوفة التحويل العالمي للعقدة.

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//ضع الصندوق عند (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
Matrix4 mat = boxNode.EvaluateGlobalTransform(true);
Console.WriteLine($"The box's global transform matrix is {mat}");
```

### انظر أيضًا

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


