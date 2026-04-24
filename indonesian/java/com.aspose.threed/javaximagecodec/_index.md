---
title: JavaXImageCodec
second_title: Referensi API Aspose.3D untuk Java
description: 
type: docs
weight: 87
url: /id/java/com.aspose.threed/javaximagecodec/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.threed.ITextureCodec](../../com.aspose.threed/itexturecodec), [com.aspose.threed.ITextureDecoder](../../com.aspose.threed/itexturedecoder)
```
public class JavaXImageCodec implements ITextureCodec, ITextureDecoder
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [JavaXImageCodec()](#JavaXImageCodec--) |  |
## Metode

| Metode | Deskripsi |
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


Dekode tekstur dari aliran, kembalikan null jika gagal mendekode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
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


Mendapatkan decoder tekstur yang didukung.

**Returns:**
com.aspose.threed.ITextureDecoder[]
### getEncoders() {#getEncoders--}
```
public ITextureEncoder[] getEncoders()
```


Mendapatkan encoder tekstur yang didukung.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

