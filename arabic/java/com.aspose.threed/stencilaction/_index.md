---
title: "StencilAction"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "إجراءات اختبار القالب"
type: docs
weight: 303
url: /ar/java/com.aspose.threed/stencilaction/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum StencilAction extends Enum<StencilAction>
```

إجراءات اختبار القالب
## الحقول

| حقل | الوصف |
| --- | --- |
| [DECREMENT](#DECREMENT) | يزيد قيمة مخزن الستنسل الحالي، يحدها إلى 0. |
| [DECREMENT_WRAP](#DECREMENT-WRAP) | ينقص قيمة مخزن الستنسل الحالي ويعيدها إلى القيمة القصوى عندما تصل إلى الصفر. |
| [INCREMENT](#INCREMENT) | يزيد قيمة مخزن الستنسل الحالي، يحدها إلى القيمة القصوى. |
| [INCREMENT_WRAP](#INCREMENT-WRAP) | يزيد قيمة مخزن الستنسل الحالي ويعيدها إلى الصفر عندما تصل إلى القيمة القصوى. |
| [INVERT](#INVERT) | يقلب قيمة مخزن الستنسل الحالي على مستوى البت. |
| [KEEP](#KEEP) | احتفظ بالقيمة الحالية |
| [REPLACE](#REPLACE) | يضبط مخزن الستنسل إلى المرجع حيث تم تعريفه في [RenderState.getStencilReference](../../com.aspose.threed/renderstate\\#getStencilReference) |
| [ZERO](#ZERO) | يضبط قيمة buffer الـ stencil إلى 0 |
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
### DECREMENT {#DECREMENT}
```
public static final StencilAction DECREMENT
```


يزيد قيمة مخزن الستنسل الحالي، يحدها إلى 0.

### DECREMENT_WRAP {#DECREMENT-WRAP}
```
public static final StencilAction DECREMENT_WRAP
```


ينقص قيمة مخزن الستنسل الحالي ويعيدها إلى القيمة القصوى عندما تصل إلى الصفر.

### INCREMENT {#INCREMENT}
```
public static final StencilAction INCREMENT
```


يزيد قيمة مخزن الستنسل الحالي، يحدها إلى القيمة القصوى.

### INCREMENT_WRAP {#INCREMENT-WRAP}
```
public static final StencilAction INCREMENT_WRAP
```


يزيد قيمة مخزن الستنسل الحالي ويعيدها إلى الصفر عندما تصل إلى القيمة القصوى.

### INVERT {#INVERT}
```
public static final StencilAction INVERT
```


يقلب قيمة مخزن الستنسل الحالي على مستوى البت.

### KEEP {#KEEP}
```
public static final StencilAction KEEP
```


احتفظ بالقيمة الحالية

### REPLACE {#REPLACE}
```
public static final StencilAction REPLACE
```


يضبط مخزن الستنسل إلى المرجع حيث تم تعريفه في [RenderState.getStencilReference](../../com.aspose.threed/renderstate\\#getStencilReference)

### ZERO {#ZERO}
```
public static final StencilAction ZERO
```


يضبط قيمة buffer الـ stencil إلى 0

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
public static StencilAction valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction)
### values() {#values--}
```
public static StencilAction[] values()
```




**Returns:**
com.aspose.threed.StencilAction[]
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

