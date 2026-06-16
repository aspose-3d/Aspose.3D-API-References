---
title: "Node.GetChild"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 方法。获取指定索引处的子节点"
type: docs
weight: 200
url: /zh/net/aspose.threed/node/getchild/
---
## GetChild(int) {#getchild}

获取指定索引处的子节点。

```csharp
public Node GetChild(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | Int32 | 索引。 |

### 返回值

子节点。

## 示例

以下代码演示如何获取指定索引处的子节点。

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild(0);
Console.WriteLine($"The first node of the file is {node.Name}");
```

### 另请参见

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## GetChild(string) {#getchild_1}

获取具有指定名称的子节点

```csharp
public Node GetChild(string nodeName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | 字符串 | 要查找的子节点名称。 |

### 返回值

子节点。

## 示例

以下代码演示如何获取具有指定名称的子节点

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild("box");
Console.WriteLine($"The box node's translation is {node.Transform.Translation}");
```

### 另请参见

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


