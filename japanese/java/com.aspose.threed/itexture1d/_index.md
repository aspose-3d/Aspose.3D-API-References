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
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | 指定されたビットマップからテクスチャコンテンツを読み込む |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | テクスチャコンテンツを外部ファイルに保存する。 |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | テクスチャコンテンツを外部ファイルに保存する。 |
| [toBitmap()](#toBitmap--) | テクスチャユニットを [TextureData](../../com.aspose.threed/texturedata) インスタンスに変換する |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


指定されたビットマップからテクスチャコンテンツを読み込む

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


テクスチャコンテンツを外部ファイルに保存する。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | 保存する結果ビットマップ。 |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


テクスチャコンテンツを外部ファイルに保存する。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| パス | java.lang.String | 保存するファイル名。 |
| 形式 | java.lang.String | 画像形式 |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


テクスチャユニットを [TextureData](../../com.aspose.threed/texturedata) インスタンスに変換する

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
