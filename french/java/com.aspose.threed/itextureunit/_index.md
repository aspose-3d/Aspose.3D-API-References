---
title: "ITextureUnit"
second_title: "Référence d'API Aspose.3D pour Java"
description: "représente une texture dans la mémoire partagée entre le GPU et le CPU et pouvant être échantillonnée par le shader où le  ne représente qu'une référence à un fichier externe."
type: docs
weight: 258
url: /fr/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDepth()](#getDepth--) | Obtient la hauteur de cette texture, pour une texture non 3D elle est toujours de 1. |
| [getHeight()](#getHeight--) | Obtient la hauteur de cette texture. |
| [getMagnification()](#getMagnification--) | Obtient le mode de filtrage pour l'agrandissement. |
| [getMinification()](#getMinification--) | Obtient le mode de filtrage pour la minification. |
| [getMipmap()](#getMipmap--) | Obtient le mode de filtrage pour le mipmap. |
| [getScale()](#getScale--) | Obtient l'échelle de la coordonnée UV. |
| [getScroll()](#getScroll--) | Obtient le défilement de la coordonnée UV. |
| [getType()](#getType--) | Obtient le type de cette unité de texture. |
| [getUWrap()](#getUWrap--) | Obtient le mode d'enroulement pour la coordonnée U de la texture. |
| [getVWrap()](#getVWrap--) | Obtient le mode d'enroulement pour la coordonnée V de la texture. |
| [getWWrap()](#getWWrap--) | Obtient le mode d'enroulement pour la coordonnée W de la texture. |
| [getWidth()](#getWidth--) | Obtient la largeur de cette texture. |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | Définit le mode de filtrage pour l'agrandissement. |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | Définit le mode de filtrage pour la minification. |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | Définit le mode de filtrage pour le mipmap. |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | Définit l'échelle de la coordonnée UV. |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | Définit le défilement de la coordonnée UV. |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | Définit le mode d'enroulement pour la coordonnée U de la texture. |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | Définit le mode d'enroulement pour la coordonnée V de la texture. |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | Définit le mode d'enroulement pour la coordonnée W de la texture. |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


Obtient la hauteur de cette texture, pour une texture non 3D elle est toujours de 1.

**Returns:**
int - la hauteur de cette texture, pour une texture non 3D elle est toujours de 1.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Obtient la hauteur de cette texture.

**Returns:**
int - la hauteur de cette texture.
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


Obtient le mode de filtrage pour l'agrandissement.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


Obtient le mode de filtrage pour la minification.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


Obtient le mode de filtrage pour le mipmap.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


Obtient l'échelle de la coordonnée UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


Obtient le défilement de la coordonnée UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


Obtient le type de cette unité de texture.

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


Obtient le mode d'enroulement pour la coordonnée U de la texture.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


Obtient le mode d'enroulement pour la coordonnée V de la texture.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


Obtient le mode d'enroulement pour la coordonnée W de la texture.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Obtient la largeur de cette texture.

**Returns:**
int - la largeur de cette texture.
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


Définit le mode de filtrage pour l'agrandissement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nouvelle valeur |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


Définit le mode de filtrage pour la minification.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nouvelle valeur |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


Définit le mode de filtrage pour le mipmap.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nouvelle valeur |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


Définit l'échelle de la coordonnée UV.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nouvelle valeur |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


Définit le défilement de la coordonnée UV.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nouvelle valeur |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


Définit le mode d'enroulement pour la coordonnée U de la texture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nouvelle valeur |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


Définit le mode d'enroulement pour la coordonnée V de la texture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nouvelle valeur |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


Définit le mode d'enroulement pour la coordonnée W de la texture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nouvelle valeur |

