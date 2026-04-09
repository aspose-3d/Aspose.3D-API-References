---
title: TextureData
second_title: Aspose.3D for Java API 레퍼런스
description: 이 클래스는 텍스처의 원시 데이터와 포맷 정의를 포함합니다.
type: docs
weight: 187
url: /ko/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

이 클래스는 텍스처의 원시 데이터와 포맷 정의를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | [TextureData](../../com.aspose.threed/texturedata)의 생성자 |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | 새로운 [TextureData](../../com.aspose.threed/texturedata)를 생성하고 픽셀 데이터를 할당합니다. |
| [TextureData()](#TextureData--) | [TextureData](../../com.aspose.threed/texturedata)의 생성자 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | 파일에서 텍스처를 로드합니다 |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | 스트림에서 텍스처를 로드합니다 |
| [getBytesPerPixel()](#getBytesPerPixel--) | 픽셀당 바이트 수 |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | 픽셀 데이터의 원시 바이트 |
| [getHeight()](#getHeight--) | 수직 픽셀 수 |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getPixelFormat()](#getPixelFormat--) | 픽셀 형식 |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getStride()](#getStride--) | 스캔라인의 바이트 수. |
| [getWidth()](#getWidth--) | 수평 픽셀 수 |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | 읽기/쓰기를 위해 모든 픽셀 매핑 |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | 주어진 픽셀 형식으로 읽기/쓰기를 위해 모든 픽셀 매핑 |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | 주어진 픽셀 형식으로 사각형으로 지정된 픽셀을 읽기/쓰기를 위해 매핑 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | 텍스처 데이터를 지정된 이미지 형식으로 저장 |
| [save(String fileName)](#save-java.lang.String-) | 텍스처 데이터를 이미지 파일에 저장 |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | 텍스처 데이터를 이미지 파일에 저장 |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | 픽셀 레이아웃을 새로운 픽셀 형식으로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


[TextureData](../../com.aspose.threed/texturedata)의 생성자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 너비 | int |  |
| 높이 | int |  |
| 스트라이드 | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| 데이터 | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


새로운 [TextureData](../../com.aspose.threed/texturedata)를 생성하고 픽셀 데이터를 할당합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 너비 | int |  |
| 높이 | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


[TextureData](../../com.aspose.threed/texturedata)의 생성자

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
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


파일에서 텍스처를 로드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


스트림에서 텍스처를 로드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


픽셀당 바이트 수

**Returns:**
int - 픽셀당 바이트 수
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


픽셀 데이터의 원시 바이트

**Returns:**
byte[] - 픽셀 데이터의 원시 바이트
### getHeight() {#getHeight--}
```
public int getHeight()
```


수직 픽셀 수

**Returns:**
int - 수직 픽셀 수
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


픽셀 형식

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
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
### getStride() {#getStride--}
```
public int getStride()
```


스캔라인의 바이트 수.

**Returns:**
int - 스캔라인의 바이트 수.
### getWidth() {#getWidth--}
```
public int getWidth()
```


수평 픽셀 수

**Returns:**
int - 수평 픽셀 수
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mapPixels(PixelMapMode mapMode) {#mapPixels-com.aspose.threed.PixelMapMode-}
```
public PixelMapping mapPixels(PixelMapMode mapMode)
```


읽기/쓰기를 위해 모든 픽셀 매핑

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | 맵 모드 |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


주어진 픽셀 형식으로 읽기/쓰기를 위해 모든 픽셀 매핑

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | 맵 모드 |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | 픽셀 형식 |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


주어진 픽셀 형식으로 사각형으로 지정된 픽셀을 읽기/쓰기를 위해 매핑

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | 액세스할 픽셀 영역 |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | 맵 모드 |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | 픽셀 형식 |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping) - Returns a mapping object, it should be disposed when no longer needed.
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
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


텍스처 데이터를 지정된 이미지 형식으로 저장

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 저장된 이미지를 보유하는 스트림 |
| 형식 | java.lang.String | 이미지 형식, 일반적으로 파일 확장자 |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


텍스처 데이터를 이미지 파일에 저장

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 이미지가 저장될 파일 이름. |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


텍스처 데이터를 이미지 파일에 저장

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 이미지가 저장될 파일 이름. |
| 형식 | java.lang.String | 출력 파일의 이미지 형식. |

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

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transformPixelFormat(PixelFormat pixelFormat) {#transformPixelFormat-com.aspose.threed.PixelFormat-}
```
public void transformPixelFormat(PixelFormat pixelFormat)
```


픽셀 레이아웃을 새로운 픽셀 형식으로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | 대상 픽셀 형식 |

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

