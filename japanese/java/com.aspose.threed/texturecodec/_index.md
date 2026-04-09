---
title: TextureCodec
second_title: Aspose.3D for Java API リファレンス
description: テクスチャのエンコーダーとデコーダーを管理するクラスです。
type: docs
weight: 186
url: /ja/java/com.aspose.threed/texturecodec/
---

**Inheritance:**
java.lang.Object
```
public class TextureCodec
```

テクスチャのエンコーダーとデコーダーを管理するクラスです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [TextureCodec()](#TextureCodec--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | ストリームからテクスチャデータをデコードする |
| [encode(TextureData texture, Stream stream, String format)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-java.lang.String-) | 指定された形式でテクスチャデータをストリームにエンコードする |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSupportedEncoderFormats()](#getSupportedEncoderFormats--) | サポートされているすべてのエンコーダ形式を取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerCodec(ITextureCodec codec)](#registerCodec-com.aspose.threed.ITextureCodec-) | テクスチャエンコーダとデコーダのセットを登録する |
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


ストリームからテクスチャデータをデコードする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |
| reverseY | boolean |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### encode(TextureData texture, Stream stream, String format) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-java.lang.String-}
```
public static void encode(TextureData texture, Stream stream, String format)
```


指定された形式でテクスチャデータをストリームにエンコードする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | エンコードするテクスチャ |
| stream | [Stream](../../com.aspose.threed/stream) | 出力ストリーム |
| format | java.lang.String | エンコードされたデータの画像形式（png/jpg など） |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
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


サポートされているすべてのエンコーダ形式を取得します

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


テクスチャエンコーダとデコーダのセットを登録する

**Parameters:**
| Parameter | Type | 説明 |
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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

