---
title: "Watermark.DecodeWatermark"
second_title: "Aspose.3D for .NET API 参考"
description: "Watermark 方法。解码网格中的水印"
type: docs
weight: 10
url: /zh/net/aspose.threed.utilities/watermark/decodewatermark/
---
## DecodeWatermark(Mesh) {#decodewatermark}

从网格中解码水印

```csharp
public static string DecodeWatermark(Mesh input)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | 网格 | 用于提取水印的网格 |

### 返回值

盲水印，如果未解码水印则为 null

### 异常

| 异常 | 条件 |
| --- | --- |
| UnauthorizedAccessException | 该网格受密码保护，提供的密码不正确。 |

## 备注

[`EncodeWatermark`](../encodewatermark/) 和 `DecodeWatermark` 都会执行许可证检查。试用时会抛出异常，您可以使用 [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) 来抑制该异常，但这不会解除此处的限制。使用这些功能而不受任何限制需要有效许可证。

## 示例

以下代码展示了如何从 3D 文件中保存的网格解码盲水印

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh);
```

### 另请参见

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## DecodeWatermark(Mesh, string) {#decodewatermark_1}

从网格中解码水印

```csharp
public static string DecodeWatermark(Mesh input, string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | 网格 | 用于提取水印的网格 |
| 密码 | 字符串 | 用于解密水印的密码 |

### 返回值

盲水印，如果未解码水印则为 null

### 异常

| 异常 | 条件 |
| --- | --- |
| UnauthorizedAccessException | 该网格受密码保护，提供的密码不正确。 |

## 示例

以下代码展示了如何从 3D 文件中保存的网格解码盲水印

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh, "password");
```

### 另请参见

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


