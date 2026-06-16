---
title: "PdfFormat.ExtractScene"
second_title: "Aspose.3D for .NET API 参考"
description: "PdfFormat 方法。从 PDF 文件中提取 3D 场景"
type: docs
weight: 20
url: /zh/net/aspose.threed.formats/pdfformat/extractscene/
---
## ExtractScene(string) {#extractscene_1}

从 PDF 文件中提取 3D 场景。

```csharp
public List<Scene> ExtractScene(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 输入 PDF 文件的文件名 |

### 返回值

Aspose.3D 支持的已解码 3D 场景列表

## 示例

以下代码展示了如何从 3D PDF 文件中提取所有支持的 3D 场景，并将其写入 obj 格式。

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### 另请参见

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(string, byte[]) {#extractscene_2}

从 PDF 文件中提取 3D 场景。

```csharp
public List<Scene> ExtractScene(string fileName, byte[] password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 输入 PDF 文件的文件名 |
| 密码 | Byte[] | PDF 文件的密码 |

### 返回值

Aspose.3D 支持的已解码 3D 场景列表

## 示例

以下代码展示了如何从 3D PDF 文件中提取所有支持的 3D 场景，并将其写入 obj 格式。

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### 另请参见

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(Stream, byte[]) {#extractscene}

从 PDF 流中提取原始 3D 内容。

```csharp
public List<Scene> ExtractScene(Stream stream, byte[] password = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输入 PDF 文件的流 |
| 密码 | Byte[] | PDF 文件的密码 |

### 返回值

Aspose.3D 支持的已解码 3D 场景列表

## 示例

以下代码展示了如何从 3D PDF 文件中提取所有支持的 3D 场景，并将其写入 obj 格式。

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### 另请参见

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


