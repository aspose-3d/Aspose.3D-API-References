---
title: "Node.Visible"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "خاصية Node. تحصل أو تعين لإظهار العقدة"
type: docs
weight: 130
url: /ar/net/aspose.threed/node/visible/
---
## Node.Visible property

تحصل أو تعين لإظهار العقدة

```csharp
public bool Visible { get; set; }
```

## أمثلة

الكود التالي يوضح كيفية إنشاء عقدة غير مرئية

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("test-node", new Box());
node.Visible = false;
scene.Save("output.fbx");
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


