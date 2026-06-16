---
title: "Node.CreateChildNode"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Node. تنشئ عقدة فرعية"
type: docs
weight: 170
url: /ar/net/aspose.threed/node/createchildnode/
---
## CreateChildNode() {#createchildnode}

ينشئ عقدة فرعية

```csharp
public Node CreateChildNode()
```

### قيمة الإرجاع

العقدة الفرعية الجديدة.

## أمثلة

يعرض الكود التالي كيفية إنشاء عقدة فرعية جديدة تحت العقدة الجذرية.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode();
node.Entity = new Box();
scene.Save("output.fbx");
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string) {#createchildnode_2}

إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة

```csharp
public Node CreateChildNode(string nodeName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| nodeName | سلسلة | اسم العقدة الفرعية الجديدة |

### قيمة الإرجاع

العقدة الفرعية الجديدة.

## أمثلة

يعرض الكود التالي كيفية إنشاء عقدة فرعية جديدة تحت العقدة الجذرية.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(Entity) {#createchildnode_1}

إنشاء عقدة فرعية جديدة مع إرفاق الكيان المحدد

```csharp
public Node CreateChildNode(Entity entity)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان الافتراضي المرفق بالعقدة |

### قيمة الإرجاع

العقدة الفرعية الجديدة.

## أمثلة

يعرض الكود التالي كيفية إنشاء عقدة فرعية جديدة تحت العقدة الجذرية.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode(new Box());
scene.Save("output.fbx");
```

### انظر أيضًا

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity) {#createchildnode_3}

إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة

```csharp
public Node CreateChildNode(string nodeName, Entity entity)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| nodeName | سلسلة | اسم العقدة الفرعية الجديدة |
| كيان | كيان | الكيان الافتراضي المرفق بالعقدة |

### قيمة الإرجاع

العقدة الفرعية الجديدة.

### انظر أيضًا

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity, Material) {#createchildnode_4}

إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة، وإرفاق الكيان المحدد ومادة

```csharp
public Node CreateChildNode(string nodeName, Entity entity, Material material)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| nodeName | سلسلة | اسم العقدة الفرعية الجديدة |
| كيان | كيان | الكيان الافتراضي المرفق بالعقدة |
| مادة | المادة | المادة المرفقة بالعقدة |

### قيمة الإرجاع

العقدة الفرعية الجديدة.

### انظر أيضًا

* class [Entity](../../entity/)
* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


