---
title: "MappingMode"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يحدد كيفية ربط العنصر بسطح."
type: docs
weight: 285
url: /ar/java/com.aspose.threed/mappingmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MappingMode extends Enum<MappingMode>
```

يحدد كيفية ربط العنصر بسطح. الـ [MappingMode](../../com.aspose.threed/mappingmode) يحدد كيفية ربط الـ [VertexElement](../../com.aspose.threed/vertexelement) بالسطح الهندسي.
## الحقول

| حقل | الوصف |
| --- | --- |
| [ALL_SAME](#ALL-SAME) | بيان واحد يتم تعيينه إلى السطح بالكامل. |
| [CONTROL_POINT](#CONTROL-POINT) | كل بيان يتم تعيينه إلى نقطة التحكم في الهندسة. |
| [EDGE](#EDGE) | يتم تعيين البيانات إلى الحافة. |
| [POLYGON](#POLYGON) | يتم تعيين البيانات إلى المضلع. |
| [POLYGON_VERTEX](#POLYGON-VERTEX) | يتم تعيين البيانات إلى رأس المضلع. عندما تكون نقطة التحكم مشتركة بين عدة مضلعات، ويتم تعيين البيانات كـ [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX)، فإن نقطة التحكم كقمة مضلع مختلفة ستحصل على بياناتها الخاصة. |
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
### ALL_SAME {#ALL-SAME}
```
public static final MappingMode ALL_SAME
```


بيان واحد يتم تعيينه إلى السطح بالكامل. أيًا كانت البيانات التي تُفسَّر كنقطة تحكم/قمة مضلع/نقاط نهائية للحافة، فإن البيانات تكون دائمًا نفسها كما هو معرف بواسطة [ALL\_SAME](../../com.aspose.threed/mappingmode\#ALL-SAME).

### CONTROL_POINT {#CONTROL-POINT}
```
public static final MappingMode CONTROL_POINT
```


كل بيان يتم تعيينه إلى نقطة التحكم في الهندسة.

### EDGE {#EDGE}
```
public static final MappingMode EDGE
```


يتم تعيين البيانات إلى الحافة. كل نقطة نهائية للحافة تشترك في نفس البيانات عندما يكون التعيين هو [EDGE](../../com.aspose.threed/mappingmode\#EDGE).

### POLYGON {#POLYGON}
```
public static final MappingMode POLYGON
```


يتم تعيين البيانات إلى المضلع. كل قمة من قمم المضلع تشترك في نفس البيانات عندما يكون وضع التعيين هو [POLYGON](../../com.aspose.threed/mappingmode\#POLYGON).

### POLYGON_VERTEX {#POLYGON-VERTEX}
```
public static final MappingMode POLYGON_VERTEX
```


يتم تعيين البيانات إلى رأس المضلع. عندما تكون نقطة التحكم مشتركة بين عدة مضلعات، ويتم تعيين البيانات كـ [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX)، فإن نقطة التحكم كقمة مضلع مختلفة ستحصل على بياناتها الخاصة.

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
public static MappingMode valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode)
### values() {#values--}
```
public static MappingMode[] values()
```




**Returns:**
com.aspose.threed.MappingMode[]
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

