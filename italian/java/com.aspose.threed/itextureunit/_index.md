---
title: ITextureUnit
second_title: Aspose.3D for Java API Reference
description: rappresenta una texture nella memoria condivisa tra GPU e CPU e può essere campionata dallo shader dove il  rappresenta solo un riferimento a un file esterno.
type: docs
weight: 258
url: /it/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDepth()](#getDepth--) | Restituisce l'altezza di questa texture; per le texture non 3D è sempre 1. |
| [getHeight()](#getHeight--) | Restituisce l'altezza di questa texture. |
| [getMagnification()](#getMagnification--) | Restituisce la modalità di filtro per l'ingrandimento. |
| [getMinification()](#getMinification--) | Restituisce la modalità di filtro per la riduzione. |
| [getMipmap()](#getMipmap--) | Restituisce la modalità di filtro per la mipmap. |
| [getScale()](#getScale--) | Restituisce la scala della coordinata UV. |
| [getScroll()](#getScroll--) | Restituisce lo scorrimento della coordinata UV. |
| [getType()](#getType--) | Restituisce il tipo di questa unità di texture. |
| [getUWrap()](#getUWrap--) | Restituisce la modalità di wrap per la coordinata U della texture. |
| [getVWrap()](#getVWrap--) | Restituisce la modalità di wrap per la coordinata V della texture. |
| [getWWrap()](#getWWrap--) | Restituisce la modalità di wrap per la coordinata W della texture. |
| [getWidth()](#getWidth--) | Restituisce la larghezza di questa texture. |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | Imposta la modalità di filtro per l'ingrandimento. |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | Imposta la modalità di filtro per la riduzione. |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | Imposta la modalità di filtro per la mipmap. |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | Imposta la scala della coordinata UV. |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | Imposta lo scorrimento della coordinata UV. |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | Imposta la modalità di wrap per la coordinata U della texture. |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | Imposta la modalità di wrap per la coordinata V della texture. |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | Imposta la modalità di wrap per la coordinata W della texture. |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


Restituisce l'altezza di questa texture; per le texture non 3D è sempre 1.

**Returns:**
int - l'altezza di questa texture; per le texture non 3D è sempre 1.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Restituisce l'altezza di questa texture.

**Returns:**
int - l'altezza di questa texture.
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


Restituisce la modalità di filtro per l'ingrandimento.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


Restituisce la modalità di filtro per la riduzione.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


Restituisce la modalità di filtro per la mipmap.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


Restituisce la scala della coordinata UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


Restituisce lo scorrimento della coordinata UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


Restituisce il tipo di questa unità di texture.

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


Restituisce la modalità di wrap per la coordinata U della texture.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


Restituisce la modalità di wrap per la coordinata V della texture.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


Restituisce la modalità di wrap per la coordinata W della texture.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Restituisce la larghezza di questa texture.

**Returns:**
int - la larghezza di questa texture.
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


Imposta la modalità di filtro per l'ingrandimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nuovo valore |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


Imposta la modalità di filtro per la riduzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nuovo valore |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


Imposta la modalità di filtro per la mipmap.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nuovo valore |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


Imposta la scala della coordinata UV.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuovo valore |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


Imposta lo scorrimento della coordinata UV.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuovo valore |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


Imposta la modalità di wrap per la coordinata U della texture.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nuovo valore |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


Imposta la modalità di wrap per la coordinata V della texture.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nuovo valore |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


Imposta la modalità di wrap per la coordinata W della texture.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nuovo valore |

