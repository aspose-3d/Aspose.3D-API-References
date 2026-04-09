---
title: ITextureCubemap
second_title: Aspose.3D for Java API リファレンス
description: キューブマップテクスチャ
type: docs
weight: 255
url: /ja/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

キューブマップテクスチャ
## Methods

| Method | 説明 |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | 指定された面にデータをロードします |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | 指定された [TextureData](../../com.aspose.threed/texturedata) からテクスチャ コンテンツをロードします |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | 指定されたファイルからテクスチャコンテンツを読み込む |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | 指定された面をメモリに保存する |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | テクスチャコンテンツをメモリに保存する。 |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | キューブの各面のテクスチャコンテンツを外部ファイルに保存する。 |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | Convert the texture unit to [TextureData](../../com.aspose.threed/texturedata) instance |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


指定された面にデータをロードします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


指定された [TextureData](../../com.aspose.threed/texturedata) からテクスチャ コンテンツをロードします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| データ | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


指定されたファイルからテクスチャコンテンツを読み込む

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


指定された面をメモリに保存する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


テクスチャコンテンツをメモリに保存する。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | Result bitmap to save. |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


キューブの各面のテクスチャコンテンツを外部ファイルに保存する。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| path | com.aspose.threed.CubeFaceData<java.lang.String> | 保存するファイル名。 |
| format | java.lang.String | Image format |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


Convert the texture unit to [TextureData](../../com.aspose.threed/texturedata) instance

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
