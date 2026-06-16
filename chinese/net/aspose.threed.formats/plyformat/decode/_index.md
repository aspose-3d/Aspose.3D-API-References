---
title: "PlyFormat.Decode"
second_title: "Aspose.3D for .NET API 参考"
description: "PlyFormat 方法。 从指定流解码点云或网格"
type: docs
weight: 10
url: /zh/net/aspose.threed.formats/plyformat/decode/
---
## Decode(string) {#decode_2}

从指定的流中解码点云或网格。

```csharp
public Geometry Decode(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 输入流 |

### 返回值

一个 [`Mesh`](../../../aspose.threed.entities/mesh/) 或 [`PointCloud`](../../../aspose.threed.entities/pointcloud/) 实例

## 示例

以下代码展示了如何从 PLY 文件解码网格：

```csharp
//生成用于解码的测试文件
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//解码文件
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### 另请参见

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(string, PlyLoadOptions) {#decode_3}

从指定的流中解码点云或网格。

```csharp
public Geometry Decode(string fileName, PlyLoadOptions opt)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 输入流 |
| opt | PlyLoadOptions | PLY 格式的加载选项 |

### 返回值

一个 [`Mesh`](../../../aspose.threed.entities/mesh/) 或 [`PointCloud`](../../../aspose.threed.entities/pointcloud/) 实例

## 示例

以下代码展示了如何从 PLY 文件解码网格：

```csharp
//生成用于解码的测试文件
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//解码文件
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### 另请参见

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream) {#decode}

从指定的流中解码点云或网格。

```csharp
public Geometry Decode(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输入流 |

### 返回值

一个 [`Mesh`](../../../aspose.threed.entities/mesh/) 或 [`PointCloud`](../../../aspose.threed.entities/pointcloud/) 实例

## 示例

以下代码展示了如何从 PLY 文件解码网格：

```csharp
//生成用于解码的测试文件
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//解码文件
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### 另请参见

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream, PlyLoadOptions) {#decode_1}

从指定的流中解码点云或网格。

```csharp
public Geometry Decode(Stream stream, PlyLoadOptions opt)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输入流 |
| opt | PlyLoadOptions | PLY 格式的加载选项 |

### 返回值

一个 [`Mesh`](../../../aspose.threed.entities/mesh/) 或 [`PointCloud`](../../../aspose.threed.entities/pointcloud/) 实例

## 示例

以下代码展示了如何从 PLY 文件解码网格：

```csharp
//生成用于解码的测试文件
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//解码文件
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### 另请参见

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


