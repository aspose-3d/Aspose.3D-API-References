---
title: ITextureUnit
second_title: Aspose.3D for Java API 레퍼런스
description: GPU와 CPU 사이에서 공유되는 메모리 내 텍스처를 나타내며 셰이더에서 샘플링될 수 있습니다. 여기서  은 외부 파일에 대한 참조만을 나타냅니다.
type: docs
weight: 258
url: /ko/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDepth()](#getDepth--) | 이 텍스처의 높이를 가져옵니다. 3D가 아닌 텍스처의 경우 항상 1입니다. |
| [getHeight()](#getHeight--) | 이 텍스처의 높이를 가져옵니다. |
| [getMagnification()](#getMagnification--) | 확대에 대한 필터 모드를 가져옵니다. |
| [getMinification()](#getMinification--) | 축소에 대한 필터 모드를 가져옵니다. |
| [getMipmap()](#getMipmap--) | Mipmap에 대한 필터 모드를 가져옵니다. |
| [getScale()](#getScale--) | UV 좌표의 스케일을 가져옵니다. |
| [getScroll()](#getScroll--) | UV 좌표의 스크롤을 가져옵니다. |
| [getType()](#getType--) | 이 텍스처 유닛의 유형을 가져옵니다. |
| [getUWrap()](#getUWrap--) | 텍스처의 U 좌표에 대한 랩 모드를 가져옵니다. |
| [getVWrap()](#getVWrap--) | 텍스처의 V 좌표에 대한 랩 모드를 가져옵니다. |
| [getWWrap()](#getWWrap--) | 텍스처의 W 좌표에 대한 랩 모드를 가져옵니다. |
| [getWidth()](#getWidth--) | 이 텍스처의 너비를 가져옵니다. |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | 확대에 대한 필터 모드를 설정합니다. |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | 축소에 대한 필터 모드를 설정합니다. |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | Mipmap에 대한 필터 모드를 설정합니다. |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | UV 좌표의 스케일을 설정합니다. |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | UV 좌표의 스크롤을 설정합니다. |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | 텍스처의 U 좌표에 대한 랩 모드를 설정합니다. |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | 텍스처의 V 좌표에 대한 랩 모드를 설정합니다. |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | 텍스처의 W 좌표에 대한 랩 모드를 설정합니다. |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


이 텍스처의 높이를 가져옵니다. 3D가 아닌 텍스처의 경우 항상 1입니다.

**Returns:**
int - 이 텍스처의 높이, 3D가 아닌 텍스처의 경우 항상 1입니다.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


이 텍스처의 높이를 가져옵니다.

**Returns:**
int - 이 텍스처의 높이.
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


확대에 대한 필터 모드를 가져옵니다.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


축소에 대한 필터 모드를 가져옵니다.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


Mipmap에 대한 필터 모드를 가져옵니다.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


UV 좌표의 스케일을 가져옵니다.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


UV 좌표의 스크롤을 가져옵니다.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


이 텍스처 유닛의 유형을 가져옵니다.

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


텍스처의 U 좌표에 대한 랩 모드를 가져옵니다.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


텍스처의 V 좌표에 대한 랩 모드를 가져옵니다.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


텍스처의 W 좌표에 대한 랩 모드를 가져옵니다.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


이 텍스처의 너비를 가져옵니다.

**Returns:**
int - 이 텍스처의 너비.
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


확대에 대한 필터 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 새 값 |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


축소에 대한 필터 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 새 값 |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


Mipmap에 대한 필터 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 새 값 |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


UV 좌표의 스케일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 새 값 |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


UV 좌표의 스크롤을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 새 값 |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


텍스처의 U 좌표에 대한 랩 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 새 값 |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


텍스처의 V 좌표에 대한 랩 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 새 값 |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


텍스처의 W 좌표에 대한 랩 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 새 값 |

