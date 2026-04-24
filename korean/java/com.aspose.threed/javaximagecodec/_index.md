---
title: JavaXImageCodec
second_title: Aspose.3D for Java API 레퍼런스
description: 
type: docs
weight: 87
url: /ko/java/com.aspose.threed/javaximagecodec/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.threed.ITextureCodec](../../com.aspose.threed/itexturecodec), [com.aspose.threed.ITextureDecoder](../../com.aspose.threed/itexturedecoder)
```
public class JavaXImageCodec implements ITextureCodec, ITextureDecoder
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [JavaXImageCodec()](#JavaXImageCodec--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDecoders()](#getDecoders--) |  |
| [getEncoders()](#getEncoders--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JavaXImageCodec() {#JavaXImageCodec--}
```
public JavaXImageCodec()
```


### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public TextureData decode(Stream stream, boolean reverseY)
```


스트림에서 텍스처를 디코딩하고, 디코딩에 실패하면 null을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |
| reverseY | boolean |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecoders() {#getDecoders--}
```
public ITextureDecoder[] getDecoders()
```


지원되는 텍스처 디코더를 가져옵니다.

**Returns:**
com.aspose.threed.ITextureDecoder[]
### getEncoders() {#getEncoders--}
```
public ITextureEncoder[] getEncoders()
```


지원되는 텍스처 인코더를 가져옵니다.

**Returns:**
com.aspose.threed.ITextureEncoder[]
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

