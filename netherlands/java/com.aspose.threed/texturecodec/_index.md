---
title: "TextureCodec"
second_title: "Aspose.3D voor Java API-referentie"
description: "Klasse om encoders en decoders voor texturen te beheren."
type: docs
weight: 186
url: /nl/java/com.aspose.threed/texturecodec/
---

**Inheritance:**
java.lang.Object
```
public class TextureCodec
```

Klasse om encoders en decoders voor texturen te beheren.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextureCodec()](#TextureCodec--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | Decode texturegegevens uit de stream |
| [encode(TextureData texture, Stream stream, String format)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-java.lang.String-) | Encode texturegegevens in de stream met het opgegeven formaat |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSupportedEncoderFormats()](#getSupportedEncoderFormats--) | Haalt alle ondersteunde encoderformaten op |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerCodec(ITextureCodec codec)](#registerCodec-com.aspose.threed.ITextureCodec-) | Registreer een set van texture-encoders en decoders |
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


Decode texturegegevens uit de stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |
| reverseY | boolean |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### encode(TextureData texture, Stream stream, String format) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-java.lang.String-}
```
public static void encode(TextureData texture, Stream stream, String format)
```


Encode texturegegevens in de stream met het opgegeven formaat

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | De te coderen textuur |
| stream | [Stream](../../com.aspose.threed/stream) | De uitvoerstroom |
| formaat | java.lang.String | Het afbeeldingsformaat van gecodeerde gegevens, zoals png/jpg |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt alle ondersteunde encoderformaten op

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


Registreer een set van texture-encoders en decoders

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

