---
title: "PolygonModifier.Scale"
second_title: "Aspose.3D for .NET API 参考"
description: "PolygonModifier 方法。缩放所有几何体，缩放控制点而不是此场景中的变换矩阵。"
type: docs
weight: 60
url: /zh/net/aspose.threed.entities/polygonmodifier/scale/
---
## Scale(Scene, Vector3) {#scale}

在此场景中缩放所有几何体（缩放控制点而不是变换矩阵）

```csharp
public static Scene Scale(Scene scene, Vector3 scale)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 场景 | 场景 | 要缩放的场景 |
| 缩放 | Vector3 | 缩放因子 |

## 示例

以下代码展示了如何将场景中所有几何体缩放 10 倍。

```csharp
//加载用于缩放的测试文件
var scene = Scene.FromFile("input.fbx");
//将所有几何体缩放 10 倍。
PolygonModifier.Scale(scene, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### 另请参见

* class [Scene](../../../aspose.threed/scene/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Scale(Node, Vector3) {#scale_1}

在此节点中缩放所有几何体（缩放控制点而非变换矩阵）

```csharp
public static void Scale(Node node, Vector3 scale)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | 节点 | 要缩放的节点 |
| 缩放 | Vector3 | 缩放因子 |

## 示例

以下代码展示了如何将场景中所有几何体缩放 10 倍。

```csharp
//加载用于缩放的测试文件
var scene = Scene.FromFile("input.fbx");
//将所有几何体缩放 10 倍。
PolygonModifier.Scale(scene.RootNode, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### 另请参见

* class [Node](../../../aspose.threed/node/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


