---
title: "BoneLinkMode"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "تشير وضعية ربط العظام إلى الطريقة التي يتم بها ربط العظم بعظمه الأب داخل هيكل هرمي."
type: docs
weight: 267
url: /ar/java/com.aspose.threed/bonelinkmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BoneLinkMode extends Enum<BoneLinkMode>
```

وضع ربط العظام يشير إلى الطريقة التي يتم بها ربط العظمة بعظمتها الأصلية ضمن هيكل هرمي.
## الحقول

| حقل | الوصف |
| --- | --- |
| [ADDITIVE](#ADDITIVE) | الوضع الجمعي يحسب تحولات العظام الفرعية عن طريق إضافة تحولاتهم المحلية إلى تحولات عظامهم الأب. |
| [NORMALIZE](#NORMALIZE) | في هذا الوضع، يتم تطبيع تحولات العظام الفرعية بالنسبة لتحولات عظمها الأب. |
| [TOTAL_ONE](#TOTAL-ONE) | يضمن وضع Total One أن التحولات المدمجة للعظم الأب والفرعي تنتج تحولًا مركبًا يمتد إلى طول إجمالي قدره وحدة واحدة. |
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
### ADDITIVE {#ADDITIVE}
```
public static final BoneLinkMode ADDITIVE
```


الوضع الجمعي يحسب تحولات العظام الفرعية عن طريق إضافة تحولاتهم المحلية إلى تحولات عظامهم الأب.

### NORMALIZE {#NORMALIZE}
```
public static final BoneLinkMode NORMALIZE
```


في هذا الوضع، يتم تطبيع تحولات العظام الفرعية بالنسبة لتحولات عظمها الأب.

### TOTAL_ONE {#TOTAL-ONE}
```
public static final BoneLinkMode TOTAL_ONE
```


يضمن وضع Total One أن التحولات المدمجة للعظم الأب والفرعي تنتج تحولًا مركبًا يمتد إلى طول إجمالي قدره وحدة واحدة.

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
public static BoneLinkMode valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode)
### values() {#values--}
```
public static BoneLinkMode[] values()
```




**Returns:**
com.aspose.threed.BoneLinkMode[]
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

