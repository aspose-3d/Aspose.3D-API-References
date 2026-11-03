---
title: "Node.Entity"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "خاصية Node. تحصل أو تعيّن الكيان الأول المرتبط بهذه العقدة؛ إذا تم التعيين سيُمسح الكيانات الأخرى"
type: docs
weight: 50
url: /ar/net/aspose.threed/node/entity/
---
## Node.Entity property

تحصل أو تعيّن الكيان الأول المرتبط بهذه العقدة؛ إذا تم التعيين، سيُمسح الكيانات الأخرى.

```csharp
public Entity Entity { get; set; }
```

### Property Value

كيان العقدة.

## أمثلة

الكود التالي يوضح كيفية إنشاء عقدة فرعية جديدة تحت العقدة الجذرية.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### انظر أيضًا

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


