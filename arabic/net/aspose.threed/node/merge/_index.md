---
title: "Node.Merge"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Node. افصل كل شيء تحت العقدة وأرفقه بالعقدة الحالية"
type: docs
weight: 220
url: /ar/net/aspose.threed/node/merge/
---
## Node.Merge method

افصل كل شيء تحت العقدة وأرفقه بالعقدة الحالية.

```csharp
public void Merge(Node node)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| العقدة | Node |  |

## أمثلة

الكود التالي يوضح كيفية دمج ملفين ثلاثي الأبعاد في ملف واحد

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


