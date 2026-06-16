---
title: "PdfFormat.Extract"
second_title: "Aspose.3D for .NET API 参考"
description: "PdfFormat 方法。从 PDF 文件中提取原始 3D 内容"
type: docs
weight: 10
url: /zh/net/aspose.threed.formats/pdfformat/extract/
---
## Extract(string, byte[]) {#extract_1}

从 PDF 文件中提取原始 3D 内容。

```csharp
public List<byte[]> Extract(string fileName, byte[] password = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 输入 PDF 文件的文件名 |
| 密码 | Byte[] | PDF 文件的密码 |

### 返回值

所有 3D 内容的字节列表，包括 Aspose.3D 不支持的格式。

## 示例

以下代码展示了如何从 3D PDF 文件中提取所有原始 3D 内容并将其写入文件。

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### 另请参见

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## Extract(Stream, byte[]) {#extract}

从 PDF 流中提取原始 3D 内容。

```csharp
public List<byte[]> Extract(Stream stream, byte[] password = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输入 PDF 文件的流 |
| 密码 | Byte[] | PDF 文件的密码 |

### 返回值

所有 3D 内容的字节列表，包括 Aspose.3D 不支持的格式。

## 示例

以下代码展示了如何从 3D PDF 文件中提取所有原始 3D 内容并将其写入文件。

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### 另请参见

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


