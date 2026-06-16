---
title: "ITextureUnit"
second_title: "Aspose.3D for Java API Referansı"
description: "GPU ve CPU arasında paylaşılan bellekte bir dokuyu temsil eder ve gölgelendirici tarafından örneklenebilir; burada  yalnızca harici bir dosyaya referansı temsil eder."
type: docs
weight: 258
url: /tr/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDepth()](#getDepth--) | Bu dokunun yüksekliğini alır, 3D olmayan dokular için her zaman 1'dir. |
| [getHeight()](#getHeight--) | Bu dokunun yüksekliğini alır. |
| [getMagnification()](#getMagnification--) | Büyütme için filtre modunu alır. |
| [getMinification()](#getMinification--) | Küçültme için filtre modunu alır. |
| [getMipmap()](#getMipmap--) | Mipmap için filtre modunu alır. |
| [getScale()](#getScale--) | UV koordinatının ölçeğini alır. |
| [getScroll()](#getScroll--) | UV koordinatının kaydırmasını alır. |
| [getType()](#getType--) | Bu doku biriminin tipini alır. |
| [getUWrap()](#getUWrap--) | dokunun U koordinatı için sarma modunu alır. |
| [getVWrap()](#getVWrap--) | dokunun V koordinatı için sarma modunu alır. |
| [getWWrap()](#getWWrap--) | dokunun W koordinatı için sarma modunu alır. |
| [getWidth()](#getWidth--) | Bu dokunun genişliğini alır. |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | Büyütme için filtre modunu ayarlar. |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | Küçültme için filtre modunu ayarlar. |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | Mipmap için filtre modunu ayarlar. |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | UV koordinatının ölçeğini ayarlar. |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | UV koordinatının kaydırmasını ayarlar. |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | dokunun U koordinatı için sarma modunu ayarlar. |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | dokunun V koordinatı için sarma modunu ayarlar. |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | dokunun W koordinatı için sarma modunu ayarlar. |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


Bu dokunun yüksekliğini alır, 3D olmayan dokular için her zaman 1'dir.

**Returns:**
int - bu dokunun yüksekliği, 3D olmayan dokular için her zaman 1'dir.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Bu dokunun yüksekliğini alır.

**Returns:**
int - bu dokunun yüksekliği.
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


Büyütme için filtre modunu alır.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


Küçültme için filtre modunu alır.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


Mipmap için filtre modunu alır.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


UV koordinatının ölçeğini alır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


UV koordinatının kaydırmasını alır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


Bu doku biriminin tipini alır.

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


dokunun U koordinatı için sarma modunu alır.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


dokunun V koordinatı için sarma modunu alır.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


dokunun W koordinatı için sarma modunu alır.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Bu dokunun genişliğini alır.

**Returns:**
int - bu dokunun genişliği.
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


Büyütme için filtre modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Yeni değer |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


Küçültme için filtre modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Yeni değer |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


Mipmap için filtre modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Yeni değer |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


UV koordinatının ölçeğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


UV koordinatının kaydırmasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


dokunun U koordinatı için sarma modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Yeni değer |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


dokunun V koordinatı için sarma modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Yeni değer |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


dokunun W koordinatı için sarma modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Yeni değer |

