---
title: "ITextureEncoder"
second_title: "Aspose.3D for Java API 参考"
description: "外部纹理编码器应实现此接口以进行编码。"
type: docs
weight: 257
url: /zh/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

外部纹理编码器应实现此接口以进行编码。
## 方法

| 方法 | 描述 |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | 将纹理数据编码到流中 |
| [getFileExtension()](#getFileExtension--) | 此编码器的文件扩展名（不含点） |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


将纹理数据编码到流中

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | 待编码的纹理数据 |
| stream | [Stream](../../com.aspose.threed/stream) | 输出流 |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


此编码器的文件扩展名（不含点）

**Returns:**
java.lang.String - 此编码器的文件扩展名（不含点）
