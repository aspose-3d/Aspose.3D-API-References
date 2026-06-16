---
title: "Node.GetChild"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Node. تحصل على العقدة الفرعية في الفهرس المحدد"
type: docs
weight: 200
url: /ar/net/aspose.threed/node/getchild/
---
## GetChild(int) {#getchild}

الحصول على العقدة الفرعية عند الفهرس المحدد.

```csharp
public Node GetChild(int index)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المؤشر | Int32 | الفهرس. |

### قيمة الإرجاع

العنصر الفرعي.

## أمثلة

الكود التالي يوضح كيفية الحصول على عقدة فرعية في الفهرس المحدد.

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild(0);
Console.WriteLine($"The first node of the file is {node.Name}");
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## GetChild(string) {#getchild_1}

الحصول على العقدة الفرعية بالاسم المحدد

```csharp
public Node GetChild(string nodeName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| nodeName | سلسلة | اسم العنصر الفرعي للبحث عنه |

### قيمة الإرجاع

العنصر الفرعي.

## أمثلة

الكود التالي يوضح كيفية الحصول على عقدة فرعية بالاسم المحدد

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild("box");
Console.WriteLine($"The box node's translation is {node.Transform.Translation}");
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


