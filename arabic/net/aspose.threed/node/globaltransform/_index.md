---
title: "Node.GlobalTransform"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية Node. تحصل على التحويل العالمي"
type: docs
weight: 70
url: /ar/net/aspose.threed/node/globaltransform/
---
## Node.GlobalTransform property

يحصل على التحويل العالمي.

```csharp
public GlobalTransform GlobalTransform { get; }
```

### Property Value

التحويل العالمي.

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

* class [GlobalTransform](../../globaltransform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


