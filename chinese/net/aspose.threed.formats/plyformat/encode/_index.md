---
title: "PlyFormat.Encode"
second_title: "Aspose.3D for .NET API 参考"
description: "PlyFormat 方法。 将实体编码并将结果保存到流中"
type: docs
weight: 20
url: /zh/net/aspose.threed.formats/plyformat/encode/
---
## Encode(Entity, Stream) {#encode}

编码实体并将结果保存到流中。

```csharp
public void Encode(Entity entity, Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 要编码的实体 |
| stream | Stream | 写入的流，此方法不会关闭该流 |

## 示例

以下代码展示了如何将网格编码为 PLY 文件：

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//将网格编码为 PLY 格式
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### 另请参见

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, Stream, PlySaveOptions) {#encode_1}

编码实体并将结果保存到流中。

```csharp
public void Encode(Entity entity, Stream stream, PlySaveOptions opt)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 要编码的实体 |
| stream | Stream | 写入的流，此方法不会关闭该流 |
| opt | PlySaveOptions | 保存选项 |

## 示例

以下代码展示了如何将网格编码为 PLY 文件：

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//将网格编码为 PLY 格式
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### 另请参见

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string) {#encode_2}

编码实体并将结果保存到外部文件中。

```csharp
public void Encode(Entity entity, string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 要编码的实体 |
| fileName | 字符串 | 要写入的文件 |

## 示例

以下代码展示了如何将网格编码为 PLY 文件：

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//将网格编码为 PLY 格式
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### 另请参见

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, PlySaveOptions) {#encode_3}

编码实体并将结果保存到外部文件中。

```csharp
public void Encode(Entity entity, string fileName, PlySaveOptions opt)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 要编码的实体 |
| fileName | 字符串 | 要写入的文件 |
| opt | PlySaveOptions | 保存选项 |

## 示例

以下代码展示了如何将网格编码为 PLY 文件：

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//将网格编码为 PLY 格式
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### 另请参见

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


