---
title: "TextureCodec"
second_title: "Aspose.3D for Java API 参考"
description: "用于管理纹理的编码器和解码器的类。"
type: docs
weight: 186
url: /zh/java/com.aspose.threed/texturecodec/
---

**Inheritance:**
java.lang.Object
```
public class TextureCodec
```

用于管理纹理的编码器和解码器的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextureCodec()](#TextureCodec--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | 从流中解码纹理数据 |
| [encode(TextureData texture, Stream stream, String format)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-java.lang.String-) | 使用指定格式将纹理数据编码到流中 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSupportedEncoderFormats()](#getSupportedEncoderFormats--) | 获取所有支持的编码器格式 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerCodec(ITextureCodec codec)](#registerCodec-com.aspose.threed.ITextureCodec-) | 注册一组纹理编码器和解码器 |
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


从流中解码纹理数据

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |
| reverseY | 布尔 |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### encode(TextureData texture, Stream stream, String format) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-java.lang.String-}
```
public static void encode(TextureData texture, Stream stream, String format)
```


使用指定格式将纹理数据编码到流中

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | 要编码的纹理 |
| stream | [Stream](../../com.aspose.threed/stream) | 输出流 |
| 格式 | java.lang.String | 已编码数据的图像格式，例如 png/jpg |

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
### getSupportedEncoderFormats() {#getSupportedEncoderFormats--}
```
public static String[] getSupportedEncoderFormats()
```


获取所有支持的编码器格式

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


注册一组纹理编码器和解码器

**Parameters:**
| 参数 | 类型 | 描述 |
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

