---
title: Watermark
second_title: Aspose.3D for Java API リファレンス
description: ブラインド透かしをメッシュへ/メッシュからエンコード/デコードするユーティリティ。
type: docs
weight: 230
url: /ja/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

ブラインド透かしをメッシュへ/メッシュからエンコード/デコードするユーティリティ。 **Remarks:** 両方の [Watermark](../../com.aspose.threed/watermark) と [Watermark](../../com.aspose.threed/watermark) はライセンスチェックを実行します。トライアル使用は例外をスローし、例外を抑制するには [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\\#getSuppressTrialException) を使用できますが、ここでの制限は解除されません。有効なライセンスが必要で、制限なくこれらの機能を使用できます。 **Example:** 以下のコードは、ブラインド透かしをメッシュにエンコードし、デコードする方法を示しています。

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## Methods

| Method | 説明 |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | メッシュから透かしをデコードする |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | メッシュから透かしをデコードする |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | テキストをメッシュのブラインド透かしにエンコードします。 |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | テキストをメッシュのブラインド透かしにエンコードします。 |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | テキストをメッシュのブラインド透かしにエンコードします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### decodeWatermark(Mesh input) {#decodeWatermark-com.aspose.threed.Mesh-}
```
public static String decodeWatermark(Mesh input)
```


メッシュから透かしをデコードする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | 透かしを抽出するメッシュ |

**Returns:**
java.lang.String - 透かしがデコードされていない場合はブラインド透かし、または null。
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


メッシュから透かしをデコードする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | 透かしを抽出するメッシュ |
| パスワード | java.lang.String | 透かしを復号化するためのパスワード |

**Returns:**
java.lang.String - 透かしがデコードされていない場合はブラインド透かし、または null。
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


テキストをメッシュのブラインド透かしにエンコードします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | ブラインド透かしをエンコードするメッシュ |
| テキスト | java.lang.String | メッシュにエンコードするテキスト |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello");
     new Scene(encodedMesh).save("test.ply");
```
### encodeWatermark(Mesh input, String text, String password) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text, String password)
```


テキストをメッシュのブラインド透かしにエンコードします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | ブラインド透かしをエンコードするメッシュ |
| テキスト | java.lang.String | メッシュにエンコードするテキスト |
| パスワード | java.lang.String | 透かしを保護するパスワード（オプション） |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     var encodedMesh = Watermark.encodeWatermark(mesh, "Hello", "password");
     new Scene(encodedMesh).save("test.ply");
```
### encodeWatermark(Mesh input, String text, String password, boolean permanent) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-}
```
public static Mesh encodeWatermark(Mesh input, String text, String password, boolean permanent)
```


テキストをメッシュのブラインド透かしにエンコードします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | ブラインド透かしをエンコードするメッシュ |
| テキスト | java.lang.String | メッシュにエンコードするテキスト |
| パスワード | java.lang.String | 透かしを保護するパスワード（オプション） |
| 永続的 | boolean | 永続的な透かしは上書きも削除もされません。 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     var encodedMesh = Watermark.encodeWatermark(mesh, "Hello", "password");
     new Scene(encodedMesh).save("test.ply");
```
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

