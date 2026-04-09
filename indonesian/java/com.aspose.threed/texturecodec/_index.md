---
title: TextureCodec
second_title: Referensi API Aspose.3D untuk Java
description: Kelas untuk mengelola encoder dan decoder untuk tekstur.
type: docs
weight: 186
url: /id/java/com.aspose.threed/texturecodec/
---

**Inheritance:**
java.lang.Object
```
public class TextureCodec
```

Kelas untuk mengelola encoder dan decoder untuk tekstur.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextureCodec()](#TextureCodec--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | Dekode data tekstur dari aliran |
| [encode(TextureData texture, Stream stream, String format)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-java.lang.String-) | Enkode data tekstur ke dalam aliran menggunakan format yang ditentukan |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSupportedEncoderFormats()](#getSupportedEncoderFormats--) | Mendapatkan semua format encoder yang didukung |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerCodec(ITextureCodec codec)](#registerCodec-com.aspose.threed.ITextureCodec-) | Mendaftarkan sekumpulan encoder dan decoder tekstur |
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


Dekode data tekstur dari aliran

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |
| reverseY | boolean |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### encode(TextureData texture, Stream stream, String format) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-java.lang.String-}
```
public static void encode(TextureData texture, Stream stream, String format)
```


Enkode data tekstur ke dalam aliran menggunakan format yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | Tekstur yang akan dienkode |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran keluaran |
| format | java.lang.String | Format gambar data yang dienkode, seperti png/jpg |

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
### getSupportedEncoderFormats() {#getSupportedEncoderFormats--}
```
public static String[] getSupportedEncoderFormats()
```


Mendapatkan semua format encoder yang didukung

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


Mendaftarkan sekumpulan encoder dan decoder tekstur

**Parameters:**
| Parameter | Tipe | Deskripsi |
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

