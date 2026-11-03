---
title: "Node.ChildNodes"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "خاصية Node. يسترجع العقد الفرعية"
type: docs
weight: 30
url: /ar/net/aspose.threed/node/childnodes/
---
## Node.ChildNodes property

يسترجع العقد الفرعية.

```csharp
public IList<Node> ChildNodes { get; }
```

### Property Value

العقد.

## أمثلة

الكود التالي يوضح كيفية تعداد العقد الفرعية للعقدة الجذرية

```csharp
Scene scene = Scene.FromFile("test.fbx");
foreach(var child in scene.RootNode.ChildNodes)
{
    //قم بأعمالك
}
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


