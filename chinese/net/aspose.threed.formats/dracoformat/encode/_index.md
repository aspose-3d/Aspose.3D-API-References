---
title: "DracoFormat.Encode"
second_title: "Aspose.3D for .NET API 参考"
description: "DracoFormat 方法。将实体编码到指定的流中"
type: docs
weight: 20
url: /zh/net/aspose.threed.formats/dracoformat/encode/
---
## Encode(Entity, Stream, DracoSaveOptions) {#encode_1}

将实体编码到指定的流

```csharp
public void Encode(Entity entity, Stream stream, DracoSaveOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 要编码的实体 |
| stream | Stream | 编码数据将写入的流 |
| 选项 | DracoSaveOptions | 用于编码点云的额外选项 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 当从流读取失败时抛出 |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, DracoSaveOptions) {#encode_2}

将实体编码到指定的文件

```csharp
public void Encode(Entity entity, string fileName, DracoSaveOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 要编码的实体 |
| fileName | 字符串 | 要写入的文件名 |
| 选项 | DracoSaveOptions | 用于编码点云的额外选项 |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, DracoSaveOptions) {#encode}

将实体编码为 Draco 原始数据

```csharp
public byte[] Encode(Entity entity, DracoSaveOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 要编码的实体 |
| 选项 | DracoSaveOptions | 用于编码点云的额外选项 |

### 返回值

以字节表示的编码 Draco 数据

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


