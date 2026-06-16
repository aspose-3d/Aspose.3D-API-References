---
title: "Node.ChildNodes"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية Node. تحصل على العقد الفرعية"
type: docs
weight: 30
url: /ar/net/aspose.threed/node/childnodes/
---
## Node.ChildNodes property

يحصل على عقد الأطفال.

```csharp
public IList<Node> ChildNodes { get; }
```

### Property Value

العقد.

## أمثلة

الكود التالي يوضح كيفية تعداد العقدة الفرعية للجذر

```csharp
Scene scene = Scene.FromFile("test.fbx");
foreach(var child in scene.RootNode.ChildNodes)
{
    //قم بعملك
}
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


