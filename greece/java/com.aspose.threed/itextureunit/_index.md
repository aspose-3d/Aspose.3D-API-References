---
title: ITextureUnit
second_title: Aspose.3D for Java API Reference
description: αντιπροσωπεύει μια υφή στη μνήμη που μοιράζεται μεταξύ GPU και CPU και μπορεί να δειγματοληφθεί από το shader  όπου το  μόνο αντιπροσωπεύει μια αναφορά σε εξωτερικό αρχείο.
type: docs
weight: 258
url: /el/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDepth()](#getDepth--) | Λαμβάνει το ύψος αυτής της υφής· για μη‑3Δ υφή είναι πάντα 1. |
| [getHeight()](#getHeight--) | Λαμβάνει το ύψος αυτής της υφής. |
| [getMagnification()](#getMagnification--) | Λαμβάνει τη λειτουργία φίλτρου για μεγέθυνση. |
| [getMinification()](#getMinification--) | Λαμβάνει τη λειτουργία φίλτρου για σμίκρυνση. |
| [getMipmap()](#getMipmap--) | Λαμβάνει τη λειτουργία φίλτρου για mipmap. |
| [getScale()](#getScale--) | Λαμβάνει την κλίμακα της συντεταγμένης UV. |
| [getScroll()](#getScroll--) | Λαμβάνει την κύλιση της συντεταγμένης UV. |
| [getType()](#getType--) | Λαμβάνει τον τύπο αυτής της μονάδας υφής. |
| [getUWrap()](#getUWrap--) | Λαμβάνει τη λειτουργία περιτύλιξης για τη συντεταγμένη U της υφής. |
| [getVWrap()](#getVWrap--) | Λαμβάνει τη λειτουργία περιτύλιξης για τη συντεταγμένη V της υφής. |
| [getWWrap()](#getWWrap--) | Λαμβάνει τη λειτουργία περιτύλιξης για τη συντεταγμένη W της υφής. |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος αυτής της υφής. |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | Ορίζει τη λειτουργία φίλτρου για μεγέθυνση. |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | Ορίζει τη λειτουργία φίλτρου για σμίκρυνση. |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | Ορίζει τη λειτουργία φίλτρου για mipmap. |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | Ορίζει την κλίμακα της συντεταγμένης UV. |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | Ορίζει την κύλιση της συντεταγμένης UV. |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | Ορίζει τη λειτουργία περιτύλιξης για τη συντεταγμένη U της υφής. |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | Ορίζει τη λειτουργία περιτύλιξης για τη συντεταγμένη V της υφής. |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | Ορίζει τη λειτουργία περιτύλιξης για τη συντεταγμένη W της υφής. |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


Λαμβάνει το ύψος αυτής της υφής· για μη‑3Δ υφή είναι πάντα 1.

**Returns:**
int - το ύψος αυτής της υφής, για μη‑3Δ υφή είναι πάντα 1.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Λαμβάνει το ύψος αυτής της υφής.

**Returns:**
int - το ύψος αυτής της υφής.
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


Λαμβάνει τη λειτουργία φίλτρου για μεγέθυνση.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


Λαμβάνει τη λειτουργία φίλτρου για σμίκρυνση.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


Λαμβάνει τη λειτουργία φίλτρου για mipmap.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


Λαμβάνει την κλίμακα της συντεταγμένης UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


Λαμβάνει την κύλιση της συντεταγμένης UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


Λαμβάνει τον τύπο αυτής της μονάδας υφής.

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


Λαμβάνει τη λειτουργία περιτύλιξης για τη συντεταγμένη U της υφής.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


Λαμβάνει τη λειτουργία περιτύλιξης για τη συντεταγμένη V της υφής.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


Λαμβάνει τη λειτουργία περιτύλιξης για τη συντεταγμένη W της υφής.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Λαμβάνει το πλάτος αυτής της υφής.

**Returns:**
int - το πλάτος αυτής της υφής.
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


Ορίζει τη λειτουργία φίλτρου για μεγέθυνση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Νέα τιμή |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


Ορίζει τη λειτουργία φίλτρου για σμίκρυνση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Νέα τιμή |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


Ορίζει τη λειτουργία φίλτρου για mipmap.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Νέα τιμή |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


Ορίζει την κλίμακα της συντεταγμένης UV.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Νέα τιμή |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


Ορίζει την κύλιση της συντεταγμένης UV.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Νέα τιμή |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


Ορίζει τη λειτουργία περιτύλιξης για τη συντεταγμένη U της υφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Νέα τιμή |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


Ορίζει τη λειτουργία περιτύλιξης για τη συντεταγμένη V της υφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Νέα τιμή |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


Ορίζει τη λειτουργία περιτύλιξης για τη συντεταγμένη W της υφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Νέα τιμή |

