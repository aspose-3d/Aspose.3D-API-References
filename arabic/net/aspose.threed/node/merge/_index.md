---
title: "Node.Merge"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Node. فك كل شيء تحت العقدة وإرفاقه بالعقدة الحالية"
type: docs
weight: 220
url: /ar/net/aspose.threed/node/merge/
---
## Node.Merge method

فصل كل شيء تحت العقدة وإرفاقه إلى العقدة الحالية.

```csharp
public void Merge(Node node)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| عقدة | عقدة |  |

## أمثلة

الكود التالي يوضح كيفية دمج ملفين ثلاثيين الأبعاد في ملف واحد

```csharp
Scene scene1 = Scene.FromFile("scene1.fbx");
Scene scene2 = Scene.FromFile("scene2.fbx");
scene1.RootNode.Merge(scene2.RootNode);
scene1.Save("merged.fbx");
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


