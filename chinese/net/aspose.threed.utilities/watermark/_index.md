---
title: "类 Watermark"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Utilities.Watermark 类。用于对网格进行盲水印的编码/解码的实用工具"
type: docs
weight: 2950
url: /zh/net/aspose.threed.utilities/watermark/
---
## Watermark class

用于对网格进行盲水印编码/解码的实用程序。

```csharp
public class Watermark
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark)(Mesh) | 从网格中解码水印 |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark_1)(Mesh, string) | 从网格中解码水印 |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark)(Mesh, string) | 将文本编码到网格的盲水印中。 |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_1)(Mesh, string, string) | 将文本编码到网格的盲水印中。 |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_2)(Mesh, string, string, bool) | 将文本编码到网格的盲水印中。 |

## 备注

[`EncodeWatermark`](./encodewatermark/) 和 [`DecodeWatermark`](./decodewatermark/) 都会执行许可证检查。试用时会抛出异常，您可以使用 [`SuppressTrialException`](../../aspose.threed/trialexception/suppresstrialexception/) 来抑制异常，但这不会解除此处的限制。需要有效许可证才能在没有任何限制的情况下使用这些功能。

## 示例

以下代码展示了如何将盲水印编码到网格中并解码。

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", null);
var watermark = Watermark.DecodeWatermark(encodedMesh, null);
```

### 另请参见

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


