---
title: ITextureUnit
second_title: Aspose.3D for Java API-referentie
description: vertegenwoordigt een textuur in het geheugen die gedeeld wordt tussen GPU en CPU en kan worden bemonsterd door de shader waarbij de  alleen een verwijzing naar een extern bestand vertegenwoordigt.
type: docs
weight: 258
url: /nl/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDepth()](#getDepth--) | Haalt de hoogte van deze textuur op, voor niet-3D texturen is deze altijd 1. |
| [getHeight()](#getHeight--) | Haalt de hoogte van deze textuur op. |
| [getMagnification()](#getMagnification--) | Haalt de filtermodus voor vergroting op. |
| [getMinification()](#getMinification--) | Haalt de filtermodus voor verkleining op. |
| [getMipmap()](#getMipmap--) | Haalt de filtermodus voor mipmap op. |
| [getScale()](#getScale--) | Haalt de schaal van de UV-coördinaat op. |
| [getScroll()](#getScroll--) | Haalt de scroll van de UV-coördinaat op. |
| [getType()](#getType--) | Haalt het type van deze texture‑eenheid op. |
| [getUWrap()](#getUWrap--) | Haalt de wrap‑modus voor de U‑coördinaat van de textuur op. |
| [getVWrap()](#getVWrap--) | Haalt de wrap‑modus voor de V‑coördinaat van de textuur op. |
| [getWWrap()](#getWWrap--) | Haalt de wrap‑modus voor de W‑coördinaat van de textuur op. |
| [getWidth()](#getWidth--) | Haalt de breedte van deze textuur op. |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | Stelt de filtermodus voor vergroting in. |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | Stelt de filtermodus voor verkleining in. |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | Stelt de filtermodus voor mipmap in. |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | Stelt de schaal van de UV-coördinaat in. |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | Stelt de scroll van de UV-coördinaat in. |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | Stelt de wrap‑modus voor de U‑coördinaat van de textuur in. |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | Stelt de wrap‑modus voor de V‑coördinaat van de textuur in. |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | Stelt de wrap‑modus voor de W‑coördinaat van de textuur in. |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


Haalt de hoogte van deze textuur op, voor niet-3D texturen is deze altijd 1.

**Returns:**
int - de hoogte van deze textuur, voor niet-3D texturen is deze altijd 1.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Haalt de hoogte van deze textuur op.

**Returns:**
int - de hoogte van deze textuur.
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


Haalt de filtermodus voor vergroting op.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


Haalt de filtermodus voor verkleining op.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


Haalt de filtermodus voor mipmap op.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


Haalt de schaal van de UV-coördinaat op.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


Haalt de scroll van de UV-coördinaat op.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


Haalt het type van deze texture‑eenheid op.

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


Haalt de wrap‑modus voor de U‑coördinaat van de textuur op.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


Haalt de wrap‑modus voor de V‑coördinaat van de textuur op.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


Haalt de wrap‑modus voor de W‑coördinaat van de textuur op.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Haalt de breedte van deze textuur op.

**Returns:**
int - de breedte van deze textuur.
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


Stelt de filtermodus voor vergroting in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nieuwe waarde |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


Stelt de filtermodus voor verkleining in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nieuwe waarde |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


Stelt de filtermodus voor mipmap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nieuwe waarde |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


Stelt de schaal van de UV-coördinaat in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nieuwe waarde |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


Stelt de scroll van de UV-coördinaat in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nieuwe waarde |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


Stelt de wrap‑modus voor de U‑coördinaat van de textuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nieuwe waarde |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


Stelt de wrap‑modus voor de V‑coördinaat van de textuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nieuwe waarde |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


Stelt de wrap‑modus voor de W‑coördinaat van de textuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nieuwe waarde |

