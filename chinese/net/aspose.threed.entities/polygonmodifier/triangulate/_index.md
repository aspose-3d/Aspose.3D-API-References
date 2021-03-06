---
title: Triangulate
second_title: Aspose.3D for .NET API 参考
description: 将所有基于多边形的网格转换为全三角形网格
type: docs
weight: 70
url: /zh/net/aspose.threed.entities/polygonmodifier/triangulate/
---
## Triangulate(Scene) {#triangulate_5}

将所有基于多边形的网格转换为全三角形网格

```csharp
public static void Triangulate(Scene scene)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| scene | Scene | 要处理的场景 |

### 也可以看看

* class [Scene](../../../aspose.threed/scene)
* class [PolygonModifier](../../polygonmodifier)
* 命名空间 [Aspose.ThreeD.Entities](../../polygonmodifier)
* 部件 [Aspose.3D](../../../)

---

## Triangulate(Mesh) {#triangulate}

将基于多边形的网格转换为全三角形网格

```csharp
public static Mesh Triangulate(Mesh mesh)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mesh | Mesh | 原始非三角形网格 |

### 返回值

生成的新三角形网格

### 也可以看看

* class [Mesh](../../mesh)
* class [PolygonModifier](../../polygonmodifier)
* 命名空间 [Aspose.ThreeD.Entities](../../polygonmodifier)
* 部件 [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) {#triangulate_4}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, IList<int[]> polygons, 
    bool generateNormals, out Vector3[] nor_out)
```

### 也可以看看

* struct [Vector4](../../../aspose.threed.utilities/vector4)
* struct [Vector3](../../../aspose.threed.utilities/vector3)
* class [PolygonModifier](../../polygonmodifier)
* 命名空间 [Aspose.ThreeD.Entities](../../polygonmodifier)
* 部件 [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) {#triangulate_3}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, IList<int[]> polygons)
```

### 也可以看看

* struct [Vector4](../../../aspose.threed.utilities/vector4)
* class [PolygonModifier](../../polygonmodifier)
* 命名空间 [Aspose.ThreeD.Entities](../../polygonmodifier)
* 部件 [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, int[]) {#triangulate_2}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, int[] polygon)
```

### 也可以看看

* struct [Vector4](../../../aspose.threed.utilities/vector4)
* class [PolygonModifier](../../polygonmodifier)
* 命名空间 [Aspose.ThreeD.Entities](../../polygonmodifier)
* 部件 [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;) {#triangulate_1}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints)
```

### 也可以看看

* struct [Vector4](../../../aspose.threed.utilities/vector4)
* class [PolygonModifier](../../polygonmodifier)
* 命名空间 [Aspose.ThreeD.Entities](../../polygonmodifier)
* 部件 [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
