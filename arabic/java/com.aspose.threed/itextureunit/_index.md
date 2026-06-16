---
title: "ITextureUnit"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يمثل نسيجًا في الذاكرة يتم مشاركته بين الـ GPU والـ CPU ويمكن للـ shader أن ي sampled حيث أن الـ only يمثل إشارة إلى ملف خارجي."
type: docs
weight: 258
url: /ar/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDepth()](#getDepth--) | يحصل على ارتفاع هذا النسيج، بالنسبة للأنسجة غير ثلاثية الأبعاد يكون دائمًا 1. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع هذا النسيج. |
| [getMagnification()](#getMagnification--) | يحصل على وضع الفلتر للتكبير. |
| [getMinification()](#getMinification--) | يحصل على وضع الفلتر للتصغير. |
| [getMipmap()](#getMipmap--) | يحصل على وضع الفلتر للـ mipmap. |
| [getScale()](#getScale--) | يحصل على مقياس إحداثيات UV. |
| [getScroll()](#getScroll--) | يحصل على تمرير إحداثيات UV. |
| [getType()](#getType--) | يحصل على نوع وحدة النسيج هذه. |
| [getUWrap()](#getUWrap--) | يحصل على وضع الالتفاف لإحداثية U للنسيج. |
| [getVWrap()](#getVWrap--) | يحصل على وضع الالتفاف لإحداثية V للنسيج. |
| [getWWrap()](#getWWrap--) | يحصل على وضع الالتفاف لإحداثية W للنسيج. |
| [getWidth()](#getWidth--) | يحصل على عرض هذا النسيج. |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | يضبط وضع الفلتر للتكبير. |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | يضبط وضع الفلتر للتصغير. |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | يضبط وضع الفلتر للـ mipmap. |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | يضبط مقياس إحداثيات UV. |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | يضبط تمرير إحداثيات UV. |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | يضبط وضع الالتفاف لإحداثية U للنسيج. |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | يضبط وضع الالتفاف لإحداثية V للنسيج. |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | يضبط وضع الالتفاف لإحداثية W للنسيج. |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


يحصل على ارتفاع هذا النسيج، بالنسبة للأنسجة غير ثلاثية الأبعاد يكون دائمًا 1.

**Returns:**
int - ارتفاع هذا النسيج، بالنسبة للأنسجة غير ثلاثية الأبعاد يكون دائمًا 1.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


يحصل على ارتفاع هذا النسيج.

**Returns:**
int - ارتفاع هذا النسيج.
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


يحصل على وضع الفلتر للتكبير.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


يحصل على وضع الفلتر للتصغير.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


يحصل على وضع الفلتر للـ mipmap.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


يحصل على مقياس إحداثيات UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


يحصل على تمرير إحداثيات UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


يحصل على نوع وحدة النسيج هذه.

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


يحصل على وضع الالتفاف لإحداثية U للنسيج.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


يحصل على وضع الالتفاف لإحداثية V للنسيج.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


يحصل على وضع الالتفاف لإحداثية W للنسيج.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


يحصل على عرض هذا النسيج.

**Returns:**
int - عرض هذا النسيج.
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


يضبط وضع الفلتر للتكبير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | القيمة الجديدة |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


يضبط وضع الفلتر للتصغير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | القيمة الجديدة |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


يضبط وضع الفلتر للـ mipmap.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | القيمة الجديدة |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


يضبط مقياس إحداثيات UV.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | القيمة الجديدة |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


يضبط تمرير إحداثيات UV.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | القيمة الجديدة |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


يضبط وضع الالتفاف لإحداثية U للنسيج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | القيمة الجديدة |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


يضبط وضع الالتفاف لإحداثية V للنسيج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | القيمة الجديدة |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


يضبط وضع الالتفاف لإحداثية W للنسيج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | القيمة الجديدة |

