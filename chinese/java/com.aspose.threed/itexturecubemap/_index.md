---
title: "ITextureCubemap"
second_title: "Aspose.3D for Java API 参考"
description: "立方体贴图"
type: docs
weight: 255
url: /zh/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

立方体贴图
## 方法

| 方法 | 描述 |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | 将数据加载到指定的面 |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | 从指定的 [TextureData](../../com.aspose.threed/texturedata) 加载纹理内容 |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | 从指定文件加载纹理内容 |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | 将指定面保存到内存 |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | 将纹理内容保存到内存。 |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | 将立方体各面的纹理内容保存到外部文件。 |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | 将纹理单元转换为 [TextureData](../../com.aspose.threed/texturedata) 实例 |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


将数据加载到指定的面

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


从指定的 [TextureData](../../com.aspose.threed/texturedata) 加载纹理内容

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


从指定文件加载纹理内容

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


将指定面保存到内存

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


将纹理内容保存到内存。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | 要保存的结果 bitmap。 |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


将立方体各面的纹理内容保存到外部文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | com.aspose.threed.CubeFaceData<java.lang.String> | 要保存的文件名。 |
| 格式 | java.lang.String | 图像格式 |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


将纹理单元转换为 [TextureData](../../com.aspose.threed/texturedata) 实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
