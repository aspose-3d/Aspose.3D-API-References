---
title: 텍스처
second_title: Aspose.3D for Java API 레퍼런스
description: 이 클래스는 외부 파일에서 텍스처를 정의합니다.
type: docs
weight: 184
url: /ko/java/com.aspose.threed/texture/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.TextureBase](../../com.aspose.threed/texturebase)
```
public class Texture extends TextureBase
```

이 클래스는 외부 파일에서 텍스처를 정의합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Texture()](#Texture--) | [Texture](../../com.aspose.threed/texture) 클래스의 새 인스턴스를 초기화합니다. |
| [Texture(String name)](#Texture-java.lang.String-) | [Texture](../../com.aspose.threed/texture) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getAlpha()](#getAlpha--) | 텍스처의 기본 알파 값을 가져옵니다. 이는 [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource)가 [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA)인 경우에 유효합니다. 기본값은 1.0이며, 유효 범위는 0과 1 사이입니다. |
| [getAlphaSource()](#getAlphaSource--) | 텍스처가 알파 채널을 정의하는지 여부를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | 텍스처의 바이너리 콘텐츠를 가져옵니다. |
| [getEnableMipMap()](#getEnableMipMap--) | 이 텍스처에 대해 mipmap이 활성화되어 있는지 가져옵니다. |
| [getFileName()](#getFileName--) | 연관된 텍스처 파일을 가져옵니다. |
| [getMagFilter()](#getMagFilter--) | 확대용 필터를 가져옵니다. |
| [getMinFilter()](#getMinFilter--) | 축소용 필터를 가져옵니다. |
| [getMipFilter()](#getMipFilter--) | mip 레벨 샘플링용 필터를 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getUVRotation()](#getUVRotation--) | 텍스처의 회전을 가져옵니다. |
| [getUVScale()](#getUVScale--) | UV 스케일을 가져옵니다. |
| [getUVTranslation()](#getUVTranslation--) | UV 변환을 가져옵니다. |
| [getWrapModeU()](#getWrapModeU--) | U 방향의 텍스처 랩 모드를 가져옵니다. |
| [getWrapModeV()](#getWrapModeV--) | V 방향의 텍스처 랩 모드를 가져옵니다. |
| [getWrapModeW()](#getWrapModeW--) | W 방향의 텍스처 랩 모드를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setAlpha(double value)](#setAlpha-double-) | 텍스처의 기본 알파 값을 설정합니다. 이는 [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource)가 [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA)인 경우에 유효합니다. 기본값은 1.0이며, 유효 범위는 0과 1 사이입니다. |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | 텍스처가 알파 채널을 정의하는지 여부를 설정합니다. |
| [setContent(byte[] value)](#setContent-byte---) | 텍스처의 바이너리 콘텐츠를 설정합니다. |
| [setEnableMipMap(boolean value)](#setEnableMipMap-boolean-) | 이 텍스처에 대해 mipmap이 활성화되어 있는지 설정합니다. |
| [setFileName(String value)](#setFileName-java.lang.String-) | 연관된 텍스처 파일을 설정합니다. |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | 확대에 대한 필터를 설정합니다. |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | 축소에 대한 필터를 설정합니다. |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | mip 레벨 샘플링에 대한 필터를 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setRotation(double u, double v)](#setRotation-double-double-) | UV 회전을 설정합니다. |
| [setScale(double u, double v)](#setScale-double-double-) | UV 스케일을 설정합니다. |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | UV 변환을 설정합니다. |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | 텍스처의 회전을 설정합니다. |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | UV 스케일을 설정합니다. |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | UV 변환을 설정합니다. |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | U 방향의 텍스처 랩 모드를 설정합니다. |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | V 방향의 텍스처 랩 모드를 설정합니다. |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | W 방향의 텍스처 랩 모드를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Texture() {#Texture--}
```
public Texture()
```


[Texture](../../com.aspose.threed/texture) 클래스의 새 인스턴스를 초기화합니다.

### Texture(String name) {#Texture-java.lang.String-}
```
public Texture(String name)
```


[Texture](../../com.aspose.threed/texture) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


속성을 찾습니다. 동적 속성 (Created by CreateDynamicProperty/SetProperty) 또는 네이티브 속성 (Identified by its name)일 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyName | java.lang.String | 속성 이름. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


텍스처의 기본 알파 값을 가져옵니다. 이는 [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource)가 [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA)인 경우에 유효합니다. 기본값은 1.0이며, 유효 범위는 0과 1 사이입니다.

**Returns:**
double - 텍스처의 기본 알파 값입니다. 이는 [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) 이 [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA)인 경우에 유효합니다. 기본값은 1.0이며, 유효 범위는 0에서 1 사이입니다.
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


텍스처가 알파 채널을 정의하는지 여부를 가져옵니다. 기본값은 [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Returns:**
[AlphaSource](../../com.aspose.threed/alphasource) - whether the texture defines the alpha channel. Default value is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContent() {#getContent--}
```
public byte[] getContent()
```


텍스처의 바이너리 콘텐츠를 가져옵니다. 포함된 텍스처 콘텐츠는 선택 사항이며, 없을 경우 사용자는 외부 파일에서 텍스처를 로드해야 합니다.

**Returns:**
byte[] - 텍스처의 바이너리 콘텐츠입니다. 포함된 텍스처 콘텐츠는 선택 사항이며, 없을 경우 사용자는 외부 파일에서 텍스처를 로드해야 합니다.
### getEnableMipMap() {#getEnableMipMap--}
```
public boolean getEnableMipMap()
```


이 텍스처에 대해 mipmap이 활성화되어 있는지 가져옵니다.

**Returns:**
boolean - 이 텍스처에 대해 mipmap이 활성화되어 있는지 여부
### getFileName() {#getFileName--}
```
public String getFileName()
```


연관된 텍스처 파일을 가져옵니다.

**Returns:**
java.lang.String - 연관된 텍스처 파일입니다.
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


확대용 필터를 가져옵니다.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


축소용 필터를 가져옵니다.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


mip 레벨 샘플링용 필터를 가져옵니다.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


모든 속성의 컬렉션을 가져옵니다.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


지정된 속성의 값을 가져옵니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |

**Returns:**
java.lang.Object - 찾은 속성의 값
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


텍스처의 회전을 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


UV 스케일을 가져옵니다.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


UV 변환을 가져옵니다.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


U 방향의 텍스처 랩 모드를 가져옵니다.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


V 방향의 텍스처 랩 모드를 가져옵니다.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


W 방향의 텍스처 랩 모드를 가져옵니다.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in W.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


동적 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


이름으로 식별되는 지정된 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


텍스처의 기본 알파 값을 설정합니다. 이는 [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource)가 [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA)인 경우에 유효합니다. 기본값은 1.0이며, 유효 범위는 0과 1 사이입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


텍스처가 알파 채널을 정의하는지 설정합니다. 기본값은 [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | 새 값 |

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


텍스처의 바이너리 콘텐츠를 설정합니다. 포함된 텍스처 콘텐츠는 선택 사항이며, 없을 경우 사용자는 외부 파일에서 텍스처를 로드해야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] | 새 값 |

### setEnableMipMap(boolean value) {#setEnableMipMap-boolean-}
```
public void setEnableMipMap(boolean value)
```


이 텍스처에 대해 mipmap이 활성화되어 있는지 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


연관된 텍스처 파일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


확대에 대한 필터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 새 값 |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


축소에 대한 필터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 새 값 |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


mip 레벨 샘플링에 대한 필터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 새 값 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


지정된 속성의 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |
| 값 | java.lang.Object | 속성의 값 |

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


UV 회전을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


UV 스케일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


UV 변환을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


텍스처의 회전을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


UV 스케일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 새 값 |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


UV 변환을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 새 값 |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


U 방향의 텍스처 랩 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 새 값 |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


V 방향의 텍스처 랩 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 새 값 |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


W 방향의 텍스처 랩 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 새 값 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

