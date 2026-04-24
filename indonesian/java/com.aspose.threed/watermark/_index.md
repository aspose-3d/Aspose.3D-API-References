---
title: Watermark
second_title: Referensi API Aspose.3D untuk Java
description: Utilitas untuk mengkodekan/mendekode watermark buta ke/dari mesh.
type: docs
weight: 230
url: /id/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

Utilitas untuk mengkodekan/mendekode watermark buta ke/dari mesh. **Remarks:** Baik [Watermark](../../com.aspose.threed/watermark) maupun [Watermark](../../com.aspose.threed/watermark) akan melakukan pemeriksaan lisensi. Penggunaan trial akan melempar pengecualian, Anda dapat menggunakan [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) untuk menekan pengecualian, tetapi tidak akan mengangkat pembatasan di sini. Lisensi yang valid diperlukan untuk menggunakan fitur ini tanpa batasan apa pun. **Example:** Kode berikut menunjukkan cara mengkodekan watermark buta ke dalam mesh dan mendekodenya.

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | Dekode watermark dari mesh |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Dekode watermark dari mesh |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Enkode teks ke dalam watermark buta mesh. |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | Enkode teks ke dalam watermark buta mesh. |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | Enkode teks ke dalam watermark buta mesh. |
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


Dekode watermark dari mesh

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh untuk mengekstrak watermark |

**Returns:**
java.lang.String - Watermark buta atau null jika tidak ada watermark yang didekode.
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


Dekode watermark dari mesh

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh untuk mengekstrak watermark |
| kata sandi | java.lang.String | Password untuk mendekripsi watermark |

**Returns:**
java.lang.String - Watermark buta atau null jika tidak ada watermark yang didekode.
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


Enkode teks ke dalam watermark buta mesh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh untuk mengkodekan watermark buta |
| teks | java.lang.String | Teks untuk dikodekan ke mesh |

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


Enkode teks ke dalam watermark buta mesh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh untuk mengkodekan watermark buta |
| teks | java.lang.String | Teks untuk dikodekan ke mesh |
| kata sandi | java.lang.String | Password untuk melindungi watermark, bersifat opsional |

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


Enkode teks ke dalam watermark buta mesh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh untuk mengkodekan watermark buta |
| teks | java.lang.String | Teks untuk dikodekan ke mesh |
| kata sandi | java.lang.String | Password untuk melindungi watermark, bersifat opsional |
| permanen | boolean | Watermark permanen tidak akan ditimpa atau dihapus. |

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

