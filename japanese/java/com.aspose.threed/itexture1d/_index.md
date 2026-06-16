---
title: "ITexture1D"
second_title: "Aspose.3D for Java API リファレンス"
description: "1D テクスチャ"
type: docs
weight: 252
url: /ja/java/com.aspose.threed/itexture1d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture1D extends ITextureUnit
```

1D テクスチャ
## メソッド

| メソッド | 説明 |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | 指定されたビットマップからテクスチャコンテンツをロードする |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | テクスチャの内容を外部ファイルに保存します。 |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | テクスチャの内容を外部ファイルに保存します。 |
| [toBitmap()](#toBitmap--) | テクスチャユニットを[TextureData](../../com.aspose.threed/texturedata)インスタンスに変換する |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


指定されたビットマップからテクスチャコンテンツをロードする

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


テクスチャの内容を外部ファイルに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | 保存する結果ビットマップ。 |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


テクスチャの内容を外部ファイルに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | 保存するファイル名。 |
| format | java.lang.String | 画像形式 |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


テクスチャユニットを[TextureData](../../com.aspose.threed/texturedata)インスタンスに変換する

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
