---
title: "Node.AddChildNode"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Node. أضف عقدة فرعية إلى هذه العقدة"
type: docs
weight: 150
url: /ar/net/aspose.threed/node/addchildnode/
---
## Node.AddChildNode method

أضف عقدة فرعية إلى هذه العقدة

```csharp
public void AddChildNode(Node node)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| العقدة | Node | العقدة الفرعية التي سيتم إرفاقها |

## أمثلة

الكود التالي يوضح كيفية الحصول على جميع المجسمات من المشهد

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


