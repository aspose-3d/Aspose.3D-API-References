---
title: "Node.Excluded"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية Node. تحصل أو تعيين ما إذا كان يجب استبعاد هذه العقدة وجميع العقد/الكيانات الفرعية أثناء التصدير"
type: docs
weight: 60
url: /ar/net/aspose.threed/node/excluded/
---
## Node.Excluded property

يحصل أو يعيّن ما إذا كان يجب استبعاد هذه العقدة وجميع العقد/الكيانات الفرعية أثناء التصدير.

```csharp
public bool Excluded { get; set; }
```

## أمثلة

الكود التالي يوضح كيفية استبعاد العقدة المحددة من التصدير

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode("excluded", new Box()).Excluded = true;
scene.RootNode.CreateChildNode("not excluded", new Box());
scene.Save("output.usdz");
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


