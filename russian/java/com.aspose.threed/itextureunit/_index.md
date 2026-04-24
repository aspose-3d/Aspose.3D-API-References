---
title: ITextureUnit
second_title: Справочник API Aspose.3D для Java
description: представляет текстуру в памяти, которая общая между GPU и CPU и может быть использована в шейдере  где  только представляет ссылку на внешний файл.
type: docs
weight: 258
url: /ru/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## Методы

| Метод | Описание |
| --- | --- |
| [getDepth()](#getDepth--) | Получает высоту этой текстуры; для не‑3D текстур она всегда равна 1. |
| [getHeight()](#getHeight--) | Получает высоту этой текстуры. |
| [getMagnification()](#getMagnification--) | Получает режим фильтрации при увеличении. |
| [getMinification()](#getMinification--) | Получает режим фильтрации при уменьшении. |
| [getMipmap()](#getMipmap--) | Получает режим фильтрации мипмапа. |
| [getScale()](#getScale--) | Получает масштаб UV‑координаты. |
| [getScroll()](#getScroll--) | Получает смещение UV‑координаты. |
| [getType()](#getType--) | Получает тип этого текстурного юнита. |
| [getUWrap()](#getUWrap--) | Получает режим обёртки для координаты U текстуры. |
| [getVWrap()](#getVWrap--) | Получает режим обёртки для координаты V текстуры. |
| [getWWrap()](#getWWrap--) | Получает режим обёртки для координаты W текстуры. |
| [getWidth()](#getWidth--) | Получает ширину этой текстуры. |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | Устанавливает режим фильтрации при увеличении. |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | Устанавливает режим фильтрации при уменьшении. |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | Устанавливает режим фильтрации мипмапа. |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | Устанавливает масштаб UV‑координаты. |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | Устанавливает смещение UV‑координаты. |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | Устанавливает режим обёртки для координаты U текстуры. |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | Устанавливает режим обёртки для координаты V текстуры. |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | Устанавливает режим обёртки для координаты W текстуры. |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


Получает высоту этой текстуры; для не‑3D текстур она всегда равна 1.

**Returns:**
int - высота этой текстуры, для не‑3D текстур она всегда равна 1.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Получает высоту этой текстуры.

**Returns:**
int - высота этой текстуры.
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


Получает режим фильтрации при увеличении.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


Получает режим фильтрации при уменьшении.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


Получает режим фильтрации мипмапа.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


Получает масштаб UV‑координаты.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


Получает смещение UV‑координаты.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


Получает тип этого текстурного юнита.

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


Получает режим обёртки для координаты U текстуры.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


Получает режим обёртки для координаты V текстуры.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


Получает режим обёртки для координаты W текстуры.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Получает ширину этой текстуры.

**Returns:**
int - ширина этой текстуры.
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


Устанавливает режим фильтрации при увеличении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Новое значение |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


Устанавливает режим фильтрации при уменьшении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Новое значение |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


Устанавливает режим фильтрации мипмапа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Новое значение |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


Устанавливает масштаб UV‑координаты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Новое значение |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


Устанавливает смещение UV‑координаты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Новое значение |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


Устанавливает режим обёртки для координаты U текстуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Новое значение |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


Устанавливает режим обёртки для координаты V текстуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Новое значение |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


Устанавливает режим обёртки для координаты W текстуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Новое значение |

