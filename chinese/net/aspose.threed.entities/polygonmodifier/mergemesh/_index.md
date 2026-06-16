---
title: "PolygonModifier.MergeMesh"
second_title: "Aspose.3D for .NET API 参考"
description: "PolygonModifier 方法。将整个场景转换为单个变换后的网格，尚不支持法线/纹理坐标等顶点元素。"
type: docs
weight: 50
url: /zh/net/aspose.threed.entities/polygonmodifier/mergemesh/
---
## MergeMesh(Scene) {#mergemesh_1}

将整个场景转换为单个已变换的 mesh。尚不支持顶点元素，如法线/纹理坐标。

```csharp
public static Mesh MergeMesh(Scene scene)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 场景 | 场景 | 要合并的场景 |

### 返回值

已合并的网格

## 示例

以下代码展示了如何将场景中的所有对象合并为单个网格。

```csharp
//输入文件可能包含多个对象
var scene = Scene.FromFile("input.fbx");
//现在将它们合并为单个网格
Mesh merged = PolygonModifier.MergeMesh(scene);
//然后我们将其保存为仅包含一个网格的文件
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### 另请参见

* class [Mesh](../../mesh/)
* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(IList&lt;Node&gt;) {#mergemesh_2}

```csharp
public static Mesh MergeMesh(IList<Node> nodes)
```

### 另请参见

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(Node) {#mergemesh}

将整个节点转换为单个已变换的 mesh。尚不支持顶点元素，如法线/纹理坐标。

```csharp
public static Mesh MergeMesh(Node node)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | 节点 | 要合并的节点 |

### 返回值

已合并的网格

## 示例

以下代码展示了如何将节点中的所有对象合并为单个网格。

```csharp
//输入文件可能包含多个对象
var scene = Scene.FromFile("input.fbx");
//现在将它们合并为单个网格
Mesh merged = PolygonModifier.MergeMesh(scene.RootNode);
//然后我们将其保存为仅包含一个网格的文件
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### 另请参见

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


