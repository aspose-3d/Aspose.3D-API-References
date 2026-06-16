---
title: "PolygonModifier.SplitMesh"
second_title: "Aspose.3D for .NET API 参考"
description: "PolygonModifier 方法。通过 VertexElementMaterial 将网格拆分为子网格。每个子网格只使用一种材质。在节点上执行网格拆分。"
type: docs
weight: 70
url: /zh/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

通过 [`VertexElementMaterial`](../../vertexelementmaterial/) 将网格拆分为子网格。每个子网格只使用一种材质。在节点上执行网格拆分。

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | 节点 |  |
| 策略 | SplitMeshPolicy |  |
| createChildNodes | Boolean | 为每个子网格创建子节点。 |
| removeOldMesh | Boolean | 在拆分后移除旧网格；如果此参数为 false，旧网格和新网格将共存。 |

## 示例

以下代码演示了如何使用材质索引将盒子拆分为子网格。

```csharp
// 创建一个盒子网格（盒子由 6 个平面组成）
Mesh box = (new Box()).ToMesh();
// 在此网格上创建材质元素
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// 并为每个平面指定不同的材质索引
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// 现在将其拆分为 6 个子网格，我们在每个平面上指定了 6 种不同的材质，每个平面将成为一个子网格。
// 我们使用了 CloneData 策略，每个平面将拥有相同的控制点信息或基于控制点的顶点元素信息。
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// 现在将其拆分为 2 个子网格，第一块网格将包含 0/1/2 平面，第二块网格将包含第 3/4/5 平面。
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// 我们使用了 CompactData 策略，每个平面将拥有各自的控制点信息或基于控制点的顶点元素信息。
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### 另请参见

* class [Node](../../../aspose.threed/node/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Scene, SplitMeshPolicy, bool) {#splitmesh_2}

通过 [`VertexElementMaterial`](../../vertexelementmaterial/) 将网格拆分为子网格。每个子网格只使用一种材质。在场景的所有节点上执行网格拆分。

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 场景 | 场景 |  |
| 策略 | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

## 示例

以下代码演示了如何使用材质索引将盒子拆分为子网格。

```csharp
// 创建一个盒子网格（盒子由 6 个平面组成）
Mesh box = (new Box()).ToMesh();
// 在此网格上创建材质元素
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// 并为每个平面指定不同的材质索引
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// 现在将其拆分为 6 个子网格，我们在每个平面上指定了 6 种不同的材质，每个平面将成为一个子网格。
// 我们使用了 CloneData 策略，每个平面将拥有相同的控制点信息或基于控制点的顶点元素信息。
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// 现在将其拆分为 2 个子网格，第一块网格将包含 0/1/2 平面，第二块网格将包含第 3/4/5 平面。
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// 我们使用了 CompactData 策略，每个平面将拥有各自的控制点信息或基于控制点的顶点元素信息。
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### 另请参见

* class [Scene](../../../aspose.threed/scene/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Mesh, SplitMeshPolicy) {#splitmesh}

通过 [`VertexElementMaterial`](../../vertexelementmaterial/) 将网格拆分为子网格。每个子网格只使用一种材质。原始网格不会被更改。

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### 返回值

新拆分的网格

## 示例

以下代码演示了如何使用材质索引将盒子拆分为子网格。

```csharp
// 创建一个盒子网格（盒子由 6 个平面组成）
Mesh box = (new Box()).ToMesh();
// 在此网格上创建材质元素
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// 并为每个平面指定不同的材质索引
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// 现在将其拆分为 6 个子网格，我们在每个平面上指定了 6 种不同的材质，每个平面将成为一个子网格。
// 我们使用了 CloneData 策略，每个平面将拥有相同的控制点信息或基于控制点的顶点元素信息。
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// 现在将其拆分为 2 个子网格，第一块网格将包含 0/1/2 平面，第二块网格将包含第 3/4/5 平面。
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// 我们使用了 CompactData 策略，每个平面将拥有各自的控制点信息或基于控制点的顶点元素信息。
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### 另请参见

* class [Mesh](../../mesh/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


