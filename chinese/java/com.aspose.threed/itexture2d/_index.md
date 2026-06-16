---
title: "ITexture2D"
second_title: "Aspose.3D for Java API 参考"
description: "2D 纹理"
type: docs
weight: 253
url: /zh/java/com.aspose.threed/itexture2d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture2D extends ITextureUnit
```

2D 纹理
## 方法

| 方法 | 描述 |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | 从指定的 Bitmap 加载纹理内容 |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | 将纹理内容保存到外部文件。 |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | 将纹理内容保存到外部文件。 |
| [toBitmap()](#toBitmap--) | 将纹理单元转换为 [TextureData](../../com.aspose.threed/texturedata) 实例 |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


从指定的 Bitmap 加载纹理内容

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


将纹理内容保存到外部文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | 要保存的结果 bitmap。 |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


将纹理内容保存到外部文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 要保存的文件名。 |
| 格式 | java.lang.String | 图像格式 |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


将纹理单元转换为 [TextureData](../../com.aspose.threed/texturedata) 实例

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
