---
title: "Node.Visible"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية Node. تحصل أو تعيين لإظهار العقدة"
type: docs
weight: 130
url: /ar/net/aspose.threed/node/visible/
---
## Node.Visible property

الحصول أو الضبط لإظهار العقدة

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


