---
title: "DracoFormat.Decode"
second_title: "Aspose.3D for .NET API 参考"
description: "DracoFormat 方法。根据指定的文件名解码点云或网格"
type: docs
weight: 10
url: /zh/net/aspose.threed.formats/dracoformat/decode/
---
## Decode(string) {#decode_1}

从指定的文件名解码点云或网格

```csharp
public Geometry Decode(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名包含 drc 文件 |

### 返回值

一个基于文件内容的 [`Mesh`](../../../aspose.threed.entities/mesh/) 或 [`PointCloud`](../../../aspose.threed.entities/pointcloud/) 实例

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 当从文件读取失败时抛出 |

## 示例

以下代码展示了如何对 Mesh 进行编码和解码为/从字节数组：

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//将网格编码为 Draco 格式
byte[] draco = FileFormat.Draco.Encode(mesh);
//从 Draco 格式解码网格
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### 另请参见

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(byte[]) {#decode}

从内存数据解码点云或网格

```csharp
public Geometry Decode(byte[] data)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | Byte[] | 原始 drc 字节 |

### 返回值

一个基于内容的 [`Mesh`](../../../aspose.threed.entities/mesh/) 或 [`PointCloud`](../../../aspose.threed.entities/pointcloud/) 实例

### 异常

| 异常 | 条件 |
| --- | --- |
| [ImportException](../../../aspose.threed/importexception/) | 当数据格式错误时抛出。 |

## 示例

以下代码展示了如何对 Mesh 进行编码和解码为/从字节数组：

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//将网格编码为 Draco 格式
byte[] draco = FileFormat.Draco.Encode(mesh);
//从 Draco 格式解码网格
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### 另请参见

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


