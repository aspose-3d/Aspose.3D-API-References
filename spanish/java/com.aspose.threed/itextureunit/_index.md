---
title: ITextureUnit
second_title: Referencia de API de Aspose.3D para Java
description: representa una textura en la memoria que se comparte entre GPU y CPU y puede ser muestreada por el shader donde el  solo representa una referencia a un archivo externo.
type: docs
weight: 258
url: /es/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## Métodos

| Método | Descripción |
| --- | --- |
| [getDepth()](#getDepth--) | Obtiene la altura de esta textura, para texturas que no son 3D siempre es 1. |
| [getHeight()](#getHeight--) | Obtiene la altura de esta textura. |
| [getMagnification()](#getMagnification--) | Obtiene el modo de filtrado para magnificación. |
| [getMinification()](#getMinification--) | Obtiene el modo de filtrado para minificación. |
| [getMipmap()](#getMipmap--) | Obtiene el modo de filtrado para mipmap. |
| [getScale()](#getScale--) | Obtiene la escala de la coordenada UV. |
| [getScroll()](#getScroll--) | Obtiene el desplazamiento de la coordenada UV. |
| [getType()](#getType--) | Obtiene el tipo de esta unidad de textura. |
| [getUWrap()](#getUWrap--) | Obtiene el modo de envoltura para la coordenada U de la textura. |
| [getVWrap()](#getVWrap--) | Obtiene el modo de envoltura para la coordenada V de la textura. |
| [getWWrap()](#getWWrap--) | Obtiene el modo de envoltura para la coordenada W de la textura. |
| [getWidth()](#getWidth--) | Obtiene el ancho de esta textura. |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | Establece el modo de filtrado para magnificación. |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | Establece el modo de filtrado para minificación. |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | Establece el modo de filtrado para mipmap. |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | Establece la escala de la coordenada UV. |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | Establece el desplazamiento de la coordenada UV. |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | Establece el modo de envoltura para la coordenada U de la textura. |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | Establece el modo de envoltura para la coordenada V de la textura. |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | Establece el modo de envoltura para la coordenada W de la textura. |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


Obtiene la altura de esta textura, para texturas que no son 3D siempre es 1.

**Returns:**
int - la altura de esta textura, para texturas que no son 3D siempre es 1.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Obtiene la altura de esta textura.

**Returns:**
int - la altura de esta textura.
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


Obtiene el modo de filtrado para magnificación.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


Obtiene el modo de filtrado para minificación.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


Obtiene el modo de filtrado para mipmap.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


Obtiene la escala de la coordenada UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


Obtiene el desplazamiento de la coordenada UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


Obtiene el tipo de esta unidad de textura.

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


Obtiene el modo de envoltura para la coordenada U de la textura.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


Obtiene el modo de envoltura para la coordenada V de la textura.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


Obtiene el modo de envoltura para la coordenada W de la textura.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Obtiene el ancho de esta textura.

**Returns:**
int - el ancho de esta textura.
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


Establece el modo de filtrado para magnificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nuevo valor |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


Establece el modo de filtrado para minificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nuevo valor |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


Establece el modo de filtrado para mipmap.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nuevo valor |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


Establece la escala de la coordenada UV.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuevo valor |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


Establece el desplazamiento de la coordenada UV.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuevo valor |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


Establece el modo de envoltura para la coordenada U de la textura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nuevo valor |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


Establece el modo de envoltura para la coordenada V de la textura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nuevo valor |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


Establece el modo de envoltura para la coordenada W de la textura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nuevo valor |

