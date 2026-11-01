---
title: "الاستيفاء"
second_title: "مرجع Aspose.3D لـ Java API"
description: "نوع استيفاء الإطارات المفتاحية."
type: docs
weight: 283
url: /ar/java/com.aspose.threed/interpolation/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Interpolation extends Enum<Interpolation>
```

نوع الاستيفاء للإطار الرئيسي.
## الحقول

| حقل | الوصف |
| --- | --- |
| [BEZIER](#BEZIER) | منحنى بيزيه أو هيرميت. |
| [B_SPLINE](#B-SPLINE) | يتم تعريف المنحنيات الأساسية بسلسلة من نقاط التحكم، حيث يضمن أن يمر المنحنى فقط عبر النقطة الأولى والنقطة الأخيرة. |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | المنحنى الكاردينالي هو منحنى هيرميت مكعب تكون المماساته معرفة بنقاط النهاية ومعامل الشد. |
| [CONSTANT](#CONSTANT) | القيمة ستظل ثابتة على قيمة النقطة الأولى حتى القطعة التالية. |
| [LINEAR](#LINEAR) | الاستيفاء الخطي هو خط مستقيم بين نقطتين. |
| [TCB_SPLINE](#TCB-SPLINE) | يُطلق عليه أيضًا منحنى كوشانيك-بارتلس، سلوك المماس يُحدد بواسطة الشد/التحيز/الاستمرارية. |
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
### BEZIER {#BEZIER}
```
public static final Interpolation BEZIER
```


منحنى بيزيه أو هيرميت.

### B_SPLINE {#B-SPLINE}
```
public static final Interpolation B_SPLINE
```


يتم تعريف المنحنيات الأساسية بسلسلة من نقاط التحكم، حيث يضمن أن يمر المنحنى فقط عبر النقطة الأولى والنقطة الأخيرة.

### CARDINAL_SPLINE {#CARDINAL-SPLINE}
```
public static final Interpolation CARDINAL_SPLINE
```


المنحنى الكاردينالي هو منحنى هيرميت مكعب تكون المماساته معرفة بنقاط النهاية ومعامل الشد.

### CONSTANT {#CONSTANT}
```
public static final Interpolation CONSTANT
```


القيمة ستظل ثابتة على قيمة النقطة الأولى حتى القطعة التالية.

### LINEAR {#LINEAR}
```
public static final Interpolation LINEAR
```


الاستيفاء الخطي هو خط مستقيم بين نقطتين.

### TCB_SPLINE {#TCB-SPLINE}
```
public static final Interpolation TCB_SPLINE
```


يُطلق عليه أيضًا منحنى كوشانيك-بارتلس، سلوك المماس يُحدد بواسطة الشد/التحيز/الاستمرارية.

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
public static Interpolation valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation)
### values() {#values--}
```
public static Interpolation[] values()
```




**Returns:**
com.aspose.threed.Interpolation[]
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

