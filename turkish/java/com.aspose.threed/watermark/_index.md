---
title: "Watermark"
second_title: "Aspose.3D for Java API Referansı"
description: "Kör filigranı bir ağda kodlamak/çözmek için araç."
type: docs
weight: 230
url: /tr/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

Kör filigranı bir ağda kodlamak/çözmek için araç. **Remarks:** Hem [Watermark](../../com.aspose.threed/watermark) hem de [Watermark](../../com.aspose.threed/watermark) lisans kontrolü yapacaktır. Deneme kullanımı bir istisna fırlatır, istisnayı bastırmak için [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) kullanabilirsiniz, ancak bu burada kısıtlamayı kaldırmaz. Bu özellikleri kısıtlamasız kullanmak için geçerli bir lisans gereklidir. **Example:** Aşağıdaki kod, bir ağda kör filigranı nasıl kodlayıp çözeceğinizi gösterir.

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | Filigranı bir ağdan çöz |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Filigranı bir ağdan çöz |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Metni ağın kör filigranına kodlayın. |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | Metni ağın kör filigranına kodlayın. |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | Metni ağın kör filigranına kodlayın. |
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


Filigranı bir ağdan çöz

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Filigranı çıkarmak için ağ |

**Returns:**
java.lang.String - Kör filigran veya hiçbir filigran çözülemediğinde null.
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


Filigranı bir ağdan çöz

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Filigranı çıkarmak için ağ |
| parola | java.lang.String | Filigranı çözmek için şifre |

**Returns:**
java.lang.String - Kör filigran veya hiçbir filigran çözülemediğinde null.
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


Metni ağın kör filigranına kodlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Kör filigranı kodlamak için ağ |
| metin | java.lang.String | Ağa kodlamak için metin |

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


Metni ağın kör filigranına kodlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Kör filigranı kodlamak için ağ |
| metin | java.lang.String | Ağa kodlamak için metin |
| parola | java.lang.String | Filigranı korumak için şifre, isteğe bağlıdır |

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


Metni ağın kör filigranına kodlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Kör filigranı kodlamak için ağ |
| metin | java.lang.String | Ağa kodlamak için metin |
| parola | java.lang.String | Filigranı korumak için şifre, isteğe bağlıdır |
| kalıcı | boolean | Kalıcı filigran üzerine yazılmaz veya kaldırılmaz. |

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

