---
title: ITextureUnit
second_title: Referensi API Aspose.3D untuk Java
description: mewakili tekstur dalam memori yang dibagikan antara GPU dan CPU dan dapat di‑sampling oleh shader  di mana  hanya mewakili referensi ke file eksternal.
type: docs
weight: 258
url: /id/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDepth()](#getDepth--) | Mendapatkan tinggi tekstur ini, untuk tekstur non-3D selalu 1. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi tekstur ini. |
| [getMagnification()](#getMagnification--) | Mendapatkan mode filter untuk pembesaran. |
| [getMinification()](#getMinification--) | Mendapatkan mode filter untuk pengecilan. |
| [getMipmap()](#getMipmap--) | Mendapatkan mode filter untuk mipmap. |
| [getScale()](#getScale--) | Mendapatkan skala koordinat UV. |
| [getScroll()](#getScroll--) | Mendapatkan gulir koordinat UV. |
| [getType()](#getType--) | Mendapatkan tipe unit tekstur ini. |
| [getUWrap()](#getUWrap--) | Mendapatkan mode pembungkus untuk koordinat U tekstur. |
| [getVWrap()](#getVWrap--) | Mendapatkan mode pembungkus untuk koordinat V tekstur. |
| [getWWrap()](#getWWrap--) | Mendapatkan mode pembungkus untuk koordinat W tekstur. |
| [getWidth()](#getWidth--) | Mendapatkan lebar tekstur ini. |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | Mengatur mode filter untuk pembesaran. |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | Mengatur mode filter untuk pengecilan. |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | Mengatur mode filter untuk mipmap. |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | Mengatur skala koordinat UV. |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | Mengatur gulir koordinat UV. |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | Mengatur mode pembungkus untuk koordinat U tekstur. |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | Mengatur mode pembungkus untuk koordinat V tekstur. |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | Mengatur mode pembungkus untuk koordinat W tekstur. |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


Mendapatkan tinggi tekstur ini, untuk tekstur non-3D selalu 1.

**Returns:**
int - tinggi tekstur ini, untuk tekstur non-3D selalu 1.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Mendapatkan tinggi tekstur ini.

**Returns:**
int - tinggi tekstur ini.
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


Mendapatkan mode filter untuk pembesaran.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


Mendapatkan mode filter untuk pengecilan.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


Mendapatkan mode filter untuk mipmap.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


Mendapatkan skala koordinat UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


Mendapatkan gulir koordinat UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


Mendapatkan tipe unit tekstur ini.

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


Mendapatkan mode pembungkus untuk koordinat U tekstur.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


Mendapatkan mode pembungkus untuk koordinat V tekstur.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


Mendapatkan mode pembungkus untuk koordinat W tekstur.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Mendapatkan lebar tekstur ini.

**Returns:**
int - lebar tekstur ini.
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


Mengatur mode filter untuk pembesaran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nilai baru |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


Mengatur mode filter untuk pengecilan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nilai baru |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


Mengatur mode filter untuk mipmap.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nilai baru |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


Mengatur skala koordinat UV.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


Mengatur gulir koordinat UV.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


Mengatur mode pembungkus untuk koordinat U tekstur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nilai baru |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


Mengatur mode pembungkus untuk koordinat V tekstur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nilai baru |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


Mengatur mode pembungkus untuk koordinat W tekstur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nilai baru |

