---
title: "Scene.RootNode"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "خاصية Scene. يحصل على العقدة الجذرية للمشهد"
type: docs
weight: 90
url: /ar/net/aspose.threed/scene/rootnode/
---
## Scene.RootNode property

يحصل على العقدة الجذرية للمشهد.

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


