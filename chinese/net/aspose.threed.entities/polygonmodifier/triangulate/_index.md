---
title: "PolygonModifier.Triangulate"
second_title: "Aspose.3D for .NET API 参考"
description: "PolygonModifier 方法。将所有基于多边形的网格转换为完整的三角形网格"
type: docs
weight: 80
url: /zh/net/aspose.threed.entities/polygonmodifier/triangulate/
---
## Triangulate(Scene) {#triangulate_5}

将所有基于多边形的网格转换为完整的三角形网格

```csharp
public static void Triangulate(Scene scene)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 场景 | 场景 | 要处理的场景 |

## 示例

以下代码展示了如何将场景中的所有对象合并为单个网格。

```csharp
var mesh = new Cylinder().ToMesh();

//将此基于四边形的网格三角化为基于三角形的
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### 另请参见

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(Mesh) {#triangulate}

将基于多边形的网格转换为完整的三角形网格

```csharp
public static Mesh Triangulate(Mesh mesh)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 网格 | 网格 | 原始的非三角形网格 |

### 返回值

生成的新三角形网格

## 示例

以下代码展示了如何将场景中的所有对象合并为单个网格。

```csharp
var mesh = new Cylinder().ToMesh();

//将此基于四边形的网格三角化为基于三角形的
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### 另请参见

* class [Mesh](../../mesh/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) {#triangulate_4}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, IList<int[]> polygons, 
    bool generateNormals, out Vector3[] nor_out)
```

### 另请参见

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) {#triangulate_3}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, IList<int[]> polygons)
```

### 另请参见

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, int[]) {#triangulate_2}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, int[] polygon)
```

### 另请参见

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;) {#triangulate_1}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints)
```

### 另请参见

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


