---
title: "JavaXImageCodec"
second_title: "Aspose.3D for Java API 参考"
description: 
type: docs
weight: 87
url: /zh/java/com.aspose.threed/javaximagecodec/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.threed.ITextureCodec](../../com.aspose.threed/itexturecodec), [com.aspose.threed.ITextureDecoder](../../com.aspose.threed/itexturedecoder)
```
public class JavaXImageCodec implements ITextureCodec, ITextureDecoder
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [JavaXImageCodec()](#JavaXImageCodec--) |  |
## 方法

| 方法 | 描述 |
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


从流中解码纹理，如果解码失败则返回 null。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |
| reverseY | 布尔 |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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


获取受支持的纹理解码器。

**Returns:**
com.aspose.threed.ITextureDecoder[]
### getEncoders() {#getEncoders--}
```
public ITextureEncoder[] getEncoders()
```


获取受支持的纹理编码器。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

