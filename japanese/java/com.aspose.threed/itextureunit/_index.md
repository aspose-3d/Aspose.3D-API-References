---
title: ITextureUnit
second_title: Aspose.3D for Java API リファレンス
description: GPU と CPU の間で共有され、シェーダーによってサンプリング可能なメモリ内のテクスチャを表します。ここで、  は外部ファイルへの参照のみを表します。
type: docs
weight: 258
url: /ja/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## Methods

| Method | 説明 |
| --- | --- |
| [getDepth()](#getDepth--) | このテクスチャの高さを取得します。3D でないテクスチャの場合は常に 1 です。 |
| [getHeight()](#getHeight--) | このテクスチャの高さを取得します。 |
| [getMagnification()](#getMagnification--) | 拡大時のフィルターモードを取得します。 |
| [getMinification()](#getMinification--) | 縮小時のフィルターモードを取得します。 |
| [getMipmap()](#getMipmap--) | ミップマップのフィルターモードを取得します。 |
| [getScale()](#getScale--) | UV 座標のスケールを取得します。 |
| [getScroll()](#getScroll--) | UV 座標のスクロールを取得します。 |
| [getType()](#getType--) | このテクスチャユニットのタイプを取得します。 |
| [getUWrap()](#getUWrap--) | テクスチャの U 座標のラップモードを取得します。 |
| [getVWrap()](#getVWrap--) | テクスチャの V 座標のラップモードを取得します。 |
| [getWWrap()](#getWWrap--) | テクスチャの W 座標のラップモードを取得します。 |
| [getWidth()](#getWidth--) | このテクスチャの幅を取得します。 |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | 拡大時のフィルターモードを設定します。 |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | 縮小時のフィルターモードを設定します。 |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | ミップマップのフィルターモードを設定します。 |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | UV 座標のスケールを設定します。 |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | UV 座標のスクロールを設定します。 |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | テクスチャの U 座標のラップモードを設定します。 |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | テクスチャの V 座標のラップモードを設定します。 |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | テクスチャの W 座標のラップモードを設定します。 |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


このテクスチャの高さを取得します。3D でないテクスチャの場合は常に 1 です。

**Returns:**
int - このテクスチャの高さ。3D でないテクスチャの場合は常に 1 です。
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


このテクスチャの高さを取得します。

**Returns:**
int - このテクスチャの高さ。
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


拡大時のフィルターモードを取得します。

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


縮小時のフィルターモードを取得します。

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


ミップマップのフィルターモードを取得します。

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


UV 座標のスケールを取得します。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


UV 座標のスクロールを取得します。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


このテクスチャユニットのタイプを取得します。

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


テクスチャの U 座標のラップモードを取得します。

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


テクスチャの V 座標のラップモードを取得します。

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


テクスチャの W 座標のラップモードを取得します。

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


このテクスチャの幅を取得します。

**Returns:**
int - このテクスチャの幅。
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


拡大時のフィルターモードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 新しい値 |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


縮小時のフィルターモードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 新しい値 |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


ミップマップのフィルターモードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 新しい値 |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


UV 座標のスケールを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


UV 座標のスクロールを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


テクスチャの U 座標のラップモードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 新しい値 |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


テクスチャの V 座標のラップモードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 新しい値 |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


テクスチャの W 座標のラップモードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 新しい値 |

