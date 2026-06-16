---
title: "Watermark"
second_title: "Aspose.3D for Java API 参考"
description: "用于对网格进行盲水印编码/解码的实用工具。"
type: docs
weight: 230
url: /zh/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

用于对网格进行盲水印编码/解码的实用工具。 **备注:** [Watermark](../../com.aspose.threed/watermark) 和 [Watermark](../../com.aspose.threed/watermark) 都会执行许可证检查，试用时会抛出异常，您可以使用 [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) 来抑制异常，但这不会解除此处的限制。需要有效许可证才能在没有任何限制的情况下使用这些功能。 **示例:** 以下代码演示了如何将盲水印编码到网格中以及如何解码它。

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | 从网格中解码水印 |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | 从网格中解码水印 |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | 将文本编码为网格的盲水印。 |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | 将文本编码为网格的盲水印。 |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | 将文本编码为网格的盲水印。 |
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


从网格中解码水印

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | 用于提取水印的网格 |

**Returns:**
java.lang.String - 盲水印，如果未解码水印则为 null。
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


从网格中解码水印

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | 用于提取水印的网格 |
| 密码 | java.lang.String | 用于解密水印的密码 |

**Returns:**
java.lang.String - 盲水印，如果未解码水印则为 null。
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


将文本编码为网格的盲水印。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | 用于编码盲水印的网格 |
| 文本 | java.lang.String | 要编码到网格的文本 |

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


将文本编码为网格的盲水印。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | 用于编码盲水印的网格 |
| 文本 | java.lang.String | 要编码到网格的文本 |
| 密码 | java.lang.String | 用于保护水印的密码，可选 |

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


将文本编码为网格的盲水印。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | 用于编码盲水印的网格 |
| 文本 | java.lang.String | 要编码到网格的文本 |
| 密码 | java.lang.String | 用于保护水印的密码，可选 |
| 永久 | 布尔 | 永久水印不会被覆盖或删除。 |

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

