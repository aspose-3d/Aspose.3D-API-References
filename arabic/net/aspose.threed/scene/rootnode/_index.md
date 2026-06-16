---
title: "Scene.RootNode"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية Scene. تحصل على العقدة الجذرية للمشهد"
type: docs
weight: 90
url: /ar/net/aspose.threed/scene/rootnode/
---
## Scene.RootNode property

يحصل على عقدة الجذر للمشهد.

```csharp
public Node RootNode { get; }
```

### Property Value

العقدة الجذرية.

## أمثلة

الكود التالي يوضح كيفية إنشاء عقدة مع كيان Box مرفق بالعقدة الجذرية.

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box());
scene.Save("box.stl");
```

### انظر أيضًا

* class [Node](../../node/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


