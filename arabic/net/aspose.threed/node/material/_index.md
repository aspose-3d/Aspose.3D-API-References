---
title: "Node.Material"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "خاصية Node. تحصل أو تعين المادة الأولى المرتبطة بهذه العقدة؛ إذا تم التعيين سيُمسح باقي المواد"
type: docs
weight: 80
url: /ar/net/aspose.threed/node/material/
---
## Node.Material property

تحصل أو تعين المادة الأولى المرتبطة بهذه العقدة؛ إذا تم التعيين، سيُمسح باقي المواد

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


