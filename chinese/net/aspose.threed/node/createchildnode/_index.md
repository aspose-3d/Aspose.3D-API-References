---
title: "Node.CreateChildNode"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 方法。创建一个子节点"
type: docs
weight: 170
url: /zh/net/aspose.threed/node/createchildnode/
---
## CreateChildNode() {#createchildnode}

创建子节点

```csharp
public Node CreateChildNode()
```

### 返回值

新的子节点。

## 示例

以下代码展示了如何在根节点下创建新的子节点

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode();
node.Entity = new Box();
scene.Save("output.fbx");
```

### 另请参见

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string) {#createchildnode_2}

创建一个具有给定节点名称的新子节点

```csharp
public Node CreateChildNode(string nodeName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | 字符串 | 新的子节点名称 |

### 返回值

新的子节点。

## 示例

以下代码展示了如何在根节点下创建新的子节点

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### 另请参见

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(Entity) {#createchildnode_1}

创建一个附加了给定实体的新子节点

```csharp
public Node CreateChildNode(Entity entity)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 附加到节点的默认实体 |

### 返回值

新的子节点。

## 示例

以下代码展示了如何在根节点下创建新的子节点

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode(new Box());
scene.Save("output.fbx");
```

### 另请参见

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity) {#createchildnode_3}

创建一个具有给定节点名称的新子节点

```csharp
public Node CreateChildNode(string nodeName, Entity entity)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | 字符串 | 新的子节点名称 |
| 实体 | 实体 | 附加到节点的默认实体 |

### 返回值

新的子节点。

### 另请参见

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity, Material) {#createchildnode_4}

创建一个具有给定节点名称的新子节点，并附加指定的实体和材质

```csharp
public Node CreateChildNode(string nodeName, Entity entity, Material material)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | 字符串 | 新的子节点名称 |
| 实体 | 实体 | 附加到节点的默认实体 |
| 材质 | 材质 | 附加到节点的材质 |

### 返回值

新的子节点。

### 另请参见

* class [Entity](../../entity/)
* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


