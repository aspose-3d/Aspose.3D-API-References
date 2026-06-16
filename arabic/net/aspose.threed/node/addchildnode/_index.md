---
title: "Node.AddChildNode"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Node. أضف عقدة فرعية إلى هذه العقدة"
type: docs
weight: 150
url: /ar/net/aspose.threed/node/addchildnode/
---
## Node.AddChildNode method

إضافة عقدة فرعية إلى هذه العقدة

```csharp
public void AddChildNode(Node node)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| عقدة | عقدة | العقدة الفرعية المراد إرفاقها |

## أمثلة

الكود التالي يوضح كيفية الحصول على جميع الشبكات من المشهد

```csharp
Scene scene = Scene.FromFile("input.fbx");
var newNode = new Node();
//أضف عقدة جديدة يدويًا
scene.RootNode.AddChildNode(newNode);
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


