---
title: "Mesh.CreatePolygon"
second_title: "Aspose.3D for .NET API 参考"
description: "Mesh 方法。创建一个新多边形，所有顶点由 indices 定义。若要逐顶点创建多边形，请使用 PolygonBuilder"
type: docs
weight: 60
url: /zh/net/aspose.threed.entities/mesh/createpolygon/
---
## CreatePolygon(int[], int, int) {#createpolygon_3}

创建一个新多边形，所有顶点由 *indices* 定义。若要逐顶点创建多边形，请使用 [`PolygonBuilder`](../../polygonbuilder/)。

```csharp
public void CreatePolygon(int[] indices, int offset, int length)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| indices | Int32[] | 多边形索引数组，每个索引指向构成多边形的控制点。 |
| offset | Int32 | 第一个多边形索引的偏移量 |
| length | Int32 | 索引的长度 |

## 示例

以下代码展示了如何使用控制点的索引创建新多边形。

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### 另请参见

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int[]) {#createpolygon_2}

创建一个新多边形，所有顶点由 *indices* 定义。若要逐顶点创建多边形，请使用 [`PolygonBuilder`](../../polygonbuilder/)。

```csharp
public void CreatePolygon(int[] indices)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| indices | Int32[] | 多边形索引数组，每个索引指向构成多边形的控制点。 |

## 示例

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### 另请参见

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int, int) {#createpolygon_1}

创建一个具有4个顶点的多边形（四边形）

```csharp
public void CreatePolygon(int v1, int v2, int v3, int v4)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v1 | Int32 | 第一个顶点的索引 |
| v2 | Int32 | 第二个顶点的索引 |
| v3 | Int32 | 第三个顶点的索引 |
| v4 | Int32 | 第四个顶点的索引 |

## 示例

以下代码展示了如何使用控制点的索引创建新多边形。

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2, 3);
```

### 另请参见

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int) {#createpolygon}

创建一个具有3个顶点的多边形（三角形）

```csharp
public void CreatePolygon(int v1, int v2, int v3)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v1 | Int32 | 第一个顶点的索引 |
| v2 | Int32 | 第二个顶点的索引 |
| v3 | Int32 | 第三个顶点的索引 |

## 示例

以下代码展示了如何使用控制点的索引创建新多边形。

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2);
```

### 另请参见

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


