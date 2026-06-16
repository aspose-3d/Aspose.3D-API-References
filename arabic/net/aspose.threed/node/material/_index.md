---
title: "Node.Material"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية Node. تحصل أو تعيين المادة الأولى المرتبطة بهذه العقدة؛ إذا تم التعيين سيُمسح باقي المواد"
type: docs
weight: 80
url: /ar/net/aspose.threed/node/material/
---
## Node.Material property

يحصل أو يعيّن المادة الأولى المرتبطة بهذه العقدة، إذا تم التعيين، سيُمسح المواد الأخرى

```csharp
public Material Material { get; set; }
```

### Property Value

المادة.

## أمثلة

```csharp
Scene scene = new Scene();
var node = scene.RootNode.CreateChildNode(new Box());
node.Material = new LambertMaterial();
```

### انظر أيضًا

* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


