---
title: TextureCodec
second_title: Aspose.3D for Java API Reference
description: टेक्सचर के लिए एन्कोडर और डिकोडर प्रबंधित करने वाली क्लास।
type: docs
weight: 186
url: /hi/java/com.aspose.threed/texturecodec/
---

**Inheritance:**
java.lang.Object
```
public class TextureCodec
```

टेक्सचर के लिए एन्कोडर और डिकोडर प्रबंधित करने वाली क्लास।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [TextureCodec()](#TextureCodec--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | स्ट्रीम से टेक्सचर डेटा डिकोड करें |
| [encode(TextureData texture, Stream stream, String format)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-java.lang.String-) | निर्दिष्ट फ़ॉर्मेट का उपयोग करके टेक्सचर डेटा को स्ट्रीम में एन्कोड करें |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSupportedEncoderFormats()](#getSupportedEncoderFormats--) | सभी समर्थित एन्कोडर फ़ॉर्मेट प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerCodec(ITextureCodec codec)](#registerCodec-com.aspose.threed.ITextureCodec-) | टेक्सचर एन्कोडर और डिकोडर का एक सेट रजिस्टर करें |
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


स्ट्रीम से टेक्सचर डेटा डिकोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |
| reverseY | boolean |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### encode(TextureData texture, Stream stream, String format) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-java.lang.String-}
```
public static void encode(TextureData texture, Stream stream, String format)
```


निर्दिष्ट फ़ॉर्मेट का उपयोग करके टेक्सचर डेटा को स्ट्रीम में एन्कोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | एन्कोड करने के लिए टेक्सचर |
| stream | [Stream](../../com.aspose.threed/stream) | आउटपुट स्ट्रीम |
| format | java.lang.String | एन्कोडेड डेटा का इमेज फ़ॉर्मेट, जैसे png/jpg |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
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


सभी समर्थित एन्कोडर फ़ॉर्मेट प्राप्त करता है

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


टेक्सचर एन्कोडर और डिकोडर का एक सेट रजिस्टर करें

**Parameters:**
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

