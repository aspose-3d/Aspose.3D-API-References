---
title: ITextureUnit
second_title: Aspose.3D for Java API-referens
description: representerar en textur i minnet som delas mellan GPU och CPU och kan samplas av shadern där den endast representerar en referens till en extern fil.
type: docs
weight: 258
url: /sv/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDepth()](#getDepth--) | Hämtar höjden på denna textur, för icke-3D-textur är den alltid 1. |
| [getHeight()](#getHeight--) | Hämtar höjden på denna textur. |
| [getMagnification()](#getMagnification--) | Hämtar filtreringsläget för förstoring. |
| [getMinification()](#getMinification--) | Hämtar filtreringsläget för förminskning. |
| [getMipmap()](#getMipmap--) | Hämtar filtreringsläget för mipmap. |
| [getScale()](#getScale--) | Hämtar skalan för UV-koordinaten. |
| [getScroll()](#getScroll--) | Hämtar rullningen för UV-koordinaten. |
| [getType()](#getType--) | Hämtar typen av denna texturenhet. |
| [getUWrap()](#getUWrap--) | Hämtar omslagsläget för texturens U-koordinat. |
| [getVWrap()](#getVWrap--) | Hämtar omslagsläget för texturens V-koordinat. |
| [getWWrap()](#getWWrap--) | Hämtar omslagsläget för texturens W-koordinat. |
| [getWidth()](#getWidth--) | Hämtar bredden på denna textur. |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | Ställer in filtreringsläget för förstoring. |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | Ställer in filtreringsläget för förminskning. |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | Ställer in filtreringsläget för mipmap. |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | Ställer in skalan för UV-koordinaten. |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | Ställer in rullningen för UV-koordinaten. |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | Ställer in omslagsläget för texturens U-koordinat. |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | Ställer in omslagsläget för texturens V-koordinat. |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | Ställer in omslagsläget för texturens W-koordinat. |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


Hämtar höjden på denna textur, för icke-3D-textur är den alltid 1.

**Returns:**
int - höjden på denna textur, för icke-3D-textur är den alltid 1.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Hämtar höjden på denna textur.

**Returns:**
int - höjden på denna textur.
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


Hämtar filtreringsläget för förstoring.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


Hämtar filtreringsläget för förminskning.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


Hämtar filtreringsläget för mipmap.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


Hämtar skalan för UV-koordinaten.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


Hämtar rullningen för UV-koordinaten.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


Hämtar typen av denna texturenhet.

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


Hämtar omslagsläget för texturens U-koordinat.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


Hämtar omslagsläget för texturens V-koordinat.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


Hämtar omslagsläget för texturens W-koordinat.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Hämtar bredden på denna textur.

**Returns:**
int - bredden på denna textur.
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


Ställer in filtreringsläget för förstoring.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nytt värde |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


Ställer in filtreringsläget för förminskning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nytt värde |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


Ställer in filtreringsläget för mipmap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nytt värde |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


Ställer in skalan för UV-koordinaten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nytt värde |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


Ställer in rullningen för UV-koordinaten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nytt värde |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


Ställer in omslagsläget för texturens U-koordinat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nytt värde |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


Ställer in omslagsläget för texturens V-koordinat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nytt värde |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


Ställer in omslagsläget för texturens W-koordinat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nytt värde |

