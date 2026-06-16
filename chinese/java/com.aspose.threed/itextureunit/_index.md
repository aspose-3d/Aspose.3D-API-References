---
title: "ITextureUnit"
second_title: "Aspose.3D for Java API 参考"
description: "表示在内存中共享于 GPU 和 CPU 的纹理，可被着色器采样，其中仅表示对外部文件的引用。"
type: docs
weight: 258
url: /zh/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDepth()](#getDepth--) | 获取此纹理的高度，对于非 3D 纹理始终为 1。 |
| [getHeight()](#getHeight--) | 获取此纹理的高度。 |
| [getMagnification()](#getMagnification--) | 获取放大过滤模式。 |
| [getMinification()](#getMinification--) | 获取缩小过滤模式。 |
| [getMipmap()](#getMipmap--) | 获取 mipmap 过滤模式。 |
| [getScale()](#getScale--) | 获取 UV 坐标的缩放。 |
| [getScroll()](#getScroll--) | 获取 UV 坐标的滚动。 |
| [getType()](#getType--) | 获取此纹理单元的类型。 |
| [getUWrap()](#getUWrap--) | 获取纹理 U 坐标的环绕模式。 |
| [getVWrap()](#getVWrap--) | 获取纹理 V 坐标的环绕模式。 |
| [getWWrap()](#getWWrap--) | 获取纹理 W 坐标的环绕模式。 |
| [getWidth()](#getWidth--) | 获取此纹理的宽度。 |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | 设置放大过滤模式。 |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | 设置缩小过滤模式。 |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | 设置 mipmap 过滤模式。 |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | 设置 UV 坐标的缩放。 |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | 设置 UV 坐标的滚动。 |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | 设置纹理 U 坐标的环绕模式。 |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | 设置纹理 V 坐标的环绕模式。 |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | 设置纹理 W 坐标的环绕模式。 |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


获取此纹理的高度，对于非 3D 纹理始终为 1。

**Returns:**
int - 此纹理的高度，对于非 3D 纹理始终为 1。
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


获取此纹理的高度。

**Returns:**
int - 此纹理的高度。
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


获取放大过滤模式。

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


获取缩小过滤模式。

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


获取 mipmap 过滤模式。

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


获取 UV 坐标的缩放。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


获取 UV 坐标的滚动。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


获取此纹理单元的类型。

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


获取纹理 U 坐标的环绕模式。

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


获取纹理 V 坐标的环绕模式。

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


获取纹理 W 坐标的环绕模式。

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


获取此纹理的宽度。

**Returns:**
int - 此纹理的宽度。
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


设置放大过滤模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 新值 |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


设置缩小过滤模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 新值 |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


设置 mipmap 过滤模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 新值 |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


设置 UV 坐标的缩放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新值 |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


设置 UV 坐标的滚动。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新值 |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


设置纹理 U 坐标的环绕模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 新值 |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


设置纹理 V 坐标的环绕模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 新值 |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


设置纹理 W 坐标的环绕模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 新值 |

