---
title: "Interpolasyon"
second_title: "Aspose.3D for Java API Referansı"
description: "Anahtar kare interpolasyon tipi."
type: docs
weight: 283
url: /tr/java/com.aspose.threed/interpolation/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Interpolation extends Enum<Interpolation>
```

Ana kare interpolasyon tipi.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BEZIER](#BEZIER) | Bir bezier veya Hermite eğrisi. |
| [B_SPLINE](#B-SPLINE) | Temel spline'lar, eğrinin yalnızca ilk ve son noktadan geçeceği garanti edilen bir dizi kontrol noktasıyla tanımlanır. |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | Bir cardinal spline, uç noktalar ve bir gerilim parametresi tarafından tanımlanan teğetlere sahip bir cubic Hermite spline'dir. |
| [CONSTANT](#CONSTANT) | Değer, bir sonraki bölüme kadar ilk noktanın değeriyle sabit kalacaktır. |
| [LINEAR](#LINEAR) | Doğrusal enterpolasyon, iki nokta arasındaki düz bir çizgidir. |
| [TCB_SPLINE](#TCB-SPLINE) | Kochanek-Bartels spline olarak da adlandırılan, teğetin davranışı gerilim/bias/continuity ile tanımlanır. |
## Yöntemler

| Yöntem | Açıklama |
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


Bir bezier veya Hermite eğrisi.

### B_SPLINE {#B-SPLINE}
```
public static final Interpolation B_SPLINE
```


Temel spline'lar, eğrinin yalnızca ilk ve son noktadan geçeceği garanti edilen bir dizi kontrol noktasıyla tanımlanır.

### CARDINAL_SPLINE {#CARDINAL-SPLINE}
```
public static final Interpolation CARDINAL_SPLINE
```


Bir cardinal spline, uç noktalar ve bir gerilim parametresi tarafından tanımlanan teğetlere sahip bir cubic Hermite spline'dir.

### CONSTANT {#CONSTANT}
```
public static final Interpolation CONSTANT
```


Değer, bir sonraki bölüme kadar ilk noktanın değeriyle sabit kalacaktır.

### LINEAR {#LINEAR}
```
public static final Interpolation LINEAR
```


Doğrusal enterpolasyon, iki nokta arasındaki düz bir çizgidir.

### TCB_SPLINE {#TCB-SPLINE}
```
public static final Interpolation TCB_SPLINE
```


Kochanek-Bartels spline olarak da adlandırılan, teğetin davranışı gerilim/bias/continuity ile tanımlanır.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

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

