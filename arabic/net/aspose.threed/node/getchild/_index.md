---
title: "Node.GetChild"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Node. يسترجع العقدة الفرعية عند الفهرس المحدد"
type: docs
weight: 200
url: /ar/net/aspose.threed/node/getchild/
---
## GetChild(int) {#getchild}

يسترجع العقدة الفرعية عند الفهرس المحدد.

```csharp
public Node GetChild(int index)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | الفهرس. |

### قيمة الإرجاع

العقدة الفرعية.

## أمثلة

الكود التالي يوضح كيفية الحصول على عقدة فرعية عند الفهرس المحدد.

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

يسترجع العقدة الفرعية بالاسم المحدد

```csharp
public Node GetChild(string nodeName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| nodeName | String | اسم العنصر الفرعي للعثور عليه. |

### قيمة الإرجاع

العقدة الفرعية.

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


