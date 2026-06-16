---
title: "Node.Transform"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية Node. تحصل على التحويل المحلي"
type: docs
weight: 120
url: /ar/net/aspose.threed/node/transform/
---
## Node.Transform property

يحصل على التحويل المحلي.

```csharp
public Transform Transform { get; }
```

### Property Value

التحويل.

## أمثلة

يعرض الكود التالي كيفية تغيير تحويل العقدة:

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//ضع الصندوق عند (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### انظر أيضًا

* class [Transform](../../transform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


