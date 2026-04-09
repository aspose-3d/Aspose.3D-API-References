---
title: ITextureDecoder.Decode
second_title: Aspose.3D for .NET API 参考手册
description: ITextureDecoder 方法。从流中解码纹理，如果解码失败则返回 null
type: docs
weight: 10
url: /zh/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

从流中解码纹理，如果解码失败则返回 null。

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 纹理数据源流 |
| reverseY | Boolean | 翻转纹理 |

### 返回值

已解码的纹理数据，若不受支持则为 null

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 当从流读取数据失败时抛出 |

### 另请参见

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


