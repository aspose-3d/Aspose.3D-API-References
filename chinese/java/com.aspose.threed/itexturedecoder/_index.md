---
title: "ITextureDecoder"
second_title: "Aspose.3D for Java API 参考"
description: "外部纹理解码器应实现此接口以进行解码。"
type: docs
weight: 256
url: /zh/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

外部纹理解码器应实现此接口以进行解码。
## 方法

| 方法 | 描述 |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | 从流中解码纹理，如果解码失败则返回 null。 |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


从流中解码纹理，如果解码失败则返回 null。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 纹理数据源流 |
| reverseY | 布尔 | 翻转纹理 |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
