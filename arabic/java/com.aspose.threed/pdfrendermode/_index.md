---
title: "PdfRenderMode"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يحدد وضعية العرض النمط الذي يُعرض به العمل الفني ثلاثي الأبعاد."
type: docs
weight: 289
url: /ar/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

يحدد وضعية العرض النمط الذي يُعرض به العمل الفني ثلاثي الأبعاد.
## الحقول

| حقل | الوصف |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | يعرض حواف صندوق الحدود لكل عقدة، محاذية مع محاور مساحة الإحداثيات المحلية لتلك العقدة. |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | يعرض الحواف بلون واحد، مع إزالة الحواف المتجهة للخلف والمخفية. |
| [ILLUSTRATION](#ILLUSTRATION) | يعرض حواف الظل مع الأسطح، ويزيل الخطوط المخفية. |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | يعرض حواف الظل مع أسطح مضاءة ومقشرة ومصطلح إشعاعي إضافي لإزالة المناطق ذات الإضاءة الضعيفة في العمل الفني. |
| [SHADED_VERTICES](#SHADED-VERTICES) | يعرض القمم فقط، مع استخدام لون القمة وتطبيق الإضاءة. |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | يعرض الحواف فقط، مع استيفاء لونها بين القمتين وتطبيق الإضاءة. |
| [SOLID](#SOLID) | يعرض أشكالًا هندسية مقشرة ومضاءة. |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | يعرض حواف الظل مع أسطح مضاءة ومقشرة، ويزيل الخطوط المخفية. |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | يعرض أشكالًا هندسية مقشرة ومضاءة (مثلثات) مع حواف بلون واحد فوقها. |
| [TRANSPARENT](#TRANSPARENT) | يعرض أشكالًا هندسية مقشرة ومضاءة (مثلثات) مع مستوى إضافي من الشفافية. |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | يعرض وجوه صناديق الحدود لكل عقدة، محاذية مع محاور مساحة الإحداثيات المحلية لتلك العقدة، مع مستوى إضافي من الشفافية. |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | يعرض حواف ووجوه صناديق الحدود لكل عقدة، محاذية مع محاور مساحة الإحداثيات المحلية لتلك العقدة، مع مستوى إضافي من الشفافية. |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | يعرض أشكالًا هندسية مقشرة ومضاءة (مثلثات) مع مستوى إضافي من الشفافية، مع حواف صلبة بلون واحد فوقها. |
| [VERTICES](#VERTICES) | يعرض القمم فقط بلون واحد. |
| [WIREFRAME](#WIREFRAME) | يعرض الحواف فقط بلون واحد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


يعرض حواف صندوق الحدود لكل عقدة، محاذية مع محاور مساحة الإحداثيات المحلية لتلك العقدة.

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


يعرض الحواف بلون واحد، مع إزالة الحواف المتجهة للخلف والمخفية.

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


يعرض حواف الظل مع الأسطح، ويزيل الخطوط المخفية.

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


يعرض حواف الظل مع أسطح مضاءة ومقشرة ومصطلح إشعاعي إضافي لإزالة المناطق ذات الإضاءة الضعيفة في العمل الفني.

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


يعرض القمم فقط، مع استخدام لون القمة وتطبيق الإضاءة.

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


يعرض الحواف فقط، مع استيفاء لونها بين القمتين وتطبيق الإضاءة.

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


يعرض أشكالًا هندسية مقشرة ومضاءة.

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


يعرض حواف الظل مع أسطح مضاءة ومقشرة، ويزيل الخطوط المخفية.

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


يعرض أشكالًا هندسية مقشرة ومضاءة (مثلثات) مع حواف بلون واحد فوقها.

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


يعرض أشكالًا هندسية مقشرة ومضاءة (مثلثات) مع مستوى إضافي من الشفافية.

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


يعرض وجوه صناديق الحدود لكل عقدة، محاذية مع محاور مساحة الإحداثيات المحلية لتلك العقدة، مع مستوى إضافي من الشفافية.

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


يعرض حواف ووجوه صناديق الحدود لكل عقدة، محاذية مع محاور مساحة الإحداثيات المحلية لتلك العقدة، مع مستوى إضافي من الشفافية.

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


يعرض أشكالًا هندسية مقشرة ومضاءة (مثلثات) مع مستوى إضافي من الشفافية، مع حواف صلبة بلون واحد فوقها.

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


يعرض القمم فقط بلون واحد.

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


يعرض الحواف فقط بلون واحد.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode)
### values() {#values--}
```
public static PdfRenderMode[] values()
```




**Returns:**
com.aspose.threed.PdfRenderMode[]
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

