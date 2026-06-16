---
title: "Watermark"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "أداة لتشفير/فك تشفير العلامة المائية العمياء إلى/من شبكة."
type: docs
weight: 230
url: /ar/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

أداة لتشفير/فك تشفير العلامة المائية العمياء إلى/من شبكة. **ملاحظات:** كلا [Watermark](../../com.aspose.threed/watermark) و [Watermark](../../com.aspose.threed/watermark) سيجريان فحص الترخيص. استخدام النسخة التجريبية سيؤدي إلى استثناء، يمكنك استخدام [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) لكتم الاستثناء، لكنه لن يرفع القيد هنا. يلزم وجود ترخيص صالح لاستخدام هذه الميزات دون أي قيود. **مثال:** الكود التالي يوضح كيفية تشفير علامة مائية عمياء في شبكة وفك تشفيرها.

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## الطرق

| طريقة | الوصف |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | فك تشفير العلامة المائية من شبكة |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | فك تشفير العلامة المائية من شبكة |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | تشفير نص في العلامة المائية العمياء للشبكة. |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | تشفير نص في العلامة المائية العمياء للشبكة. |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | تشفير نص في العلامة المائية العمياء للشبكة. |
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


فك تشفير العلامة المائية من شبكة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | الشبكة لاستخراج العلامة المائية |

**Returns:**
java.lang.String - العلامة المائية العمياء أو null إذا لم يتم فك تشفير أي علامة مائية.
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


فك تشفير العلامة المائية من شبكة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | الشبكة لاستخراج العلامة المائية |
| كلمة المرور | java.lang.String | كلمة المرور لفك تشفير العلامة المائية |

**Returns:**
java.lang.String - العلامة المائية العمياء أو null إذا لم يتم فك تشفير أي علامة مائية.
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


تشفير نص في العلامة المائية العمياء للشبكة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | شبكة لتشفير علامة مائية عمياء |
| نص | java.lang.String | النص لتشفيره إلى الشبكة |

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


تشفير نص في العلامة المائية العمياء للشبكة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | شبكة لتشفير علامة مائية عمياء |
| نص | java.lang.String | النص لتشفيره إلى الشبكة |
| كلمة المرور | java.lang.String | كلمة المرور لحماية العلامة المائية، وهي اختيارية |

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


تشفير نص في العلامة المائية العمياء للشبكة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | شبكة لتشفير علامة مائية عمياء |
| نص | java.lang.String | النص لتشفيره إلى الشبكة |
| كلمة المرور | java.lang.String | كلمة المرور لحماية العلامة المائية، وهي اختيارية |
| دائم | boolean | العلامة المائية الدائمة لن يتم استبدالها أو إزالتها. |

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
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

