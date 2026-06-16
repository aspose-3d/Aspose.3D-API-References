---
title: "TextureCodec"
second_title: "Aspose.3D for Java API Referansı"
description: "Dokular için kodlayıcı ve kod çözücülerini yöneten sınıf."
type: docs
weight: 186
url: /tr/java/com.aspose.threed/texturecodec/
---

**Inheritance:**
java.lang.Object
```
public class TextureCodec
```

Dokular için kodlayıcı ve kod çözücülerini yöneten sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextureCodec()](#TextureCodec--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | Akıştan doku verisini çöz |
| [encode(TextureData texture, Stream stream, String format)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-java.lang.String-) | Belirtilen formatı kullanarak doku verisini akışa kodla |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSupportedEncoderFormats()](#getSupportedEncoderFormats--) | Tüm desteklenen kodlayıcı formatlarını alır |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerCodec(ITextureCodec codec)](#registerCodec-com.aspose.threed.ITextureCodec-) | Bir dizi doku kodlayıcı ve çözücü kaydet |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureCodec() {#TextureCodec--}
```
public TextureCodec()
```


### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public static TextureData decode(Stream stream, boolean reverseY)
```


Akıştan doku verisini çöz

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |
| reverseY | boolean |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### encode(TextureData texture, Stream stream, String format) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-java.lang.String-}
```
public static void encode(TextureData texture, Stream stream, String format)
```


Belirtilen formatı kullanarak doku verisini akışa kodla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | Kodlanacak doku |
| stream | [Stream](../../com.aspose.threed/stream) | Çıktı akışı |
| biçim | java.lang.String | Kodlanmış verinin görüntü formatı, örneğin png/jpg |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
### getSupportedEncoderFormats() {#getSupportedEncoderFormats--}
```
public static String[] getSupportedEncoderFormats()
```


Tüm desteklenen kodlayıcı formatlarını alır

**Returns:**
java.lang.String[]
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




### registerCodec(ITextureCodec codec) {#registerCodec-com.aspose.threed.ITextureCodec-}
```
public static void registerCodec(ITextureCodec codec)
```


Bir dizi doku kodlayıcı ve çözücü kaydet

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codec | [ITextureCodec](../../com.aspose.threed/itexturecodec) |  |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

