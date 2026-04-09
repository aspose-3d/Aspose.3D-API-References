---
title: JavaXImageCodec
second_title: Aspose.3D for Java API-referens
description: 
type: docs
weight: 87
url: /sv/java/com.aspose.threed/javaximagecodec/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.threed.ITextureCodec](../../com.aspose.threed/itexturecodec), [com.aspose.threed.ITextureDecoder](../../com.aspose.threed/itexturedecoder)
```
public class JavaXImageCodec implements ITextureCodec, ITextureDecoder
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [JavaXImageCodec()](#JavaXImageCodec--) |  |
## Metoder

| Metod | Beskrivning |
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


Dekoda textur från ström, returnera null om dekodning misslyckas.

**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
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


Hämtar stödjade texturavkodare.

**Returns:**
com.aspose.threed.ITextureDecoder[]
### getEncoders() {#getEncoders--}
```
public ITextureEncoder[] getEncoders()
```


Hämtar stödjade texturkodare.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

