---
title: Interpolasi
second_title: Referensi API Aspose.3D untuk Java
description: Tipe interpolasi key frame.
type: docs
weight: 283
url: /id/java/com.aspose.threed/interpolation/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Interpolation extends Enum<Interpolation>
```

Tipe interpolasi frame kunci.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [BEZIER](#BEZIER) | Sebuah spline bezier atau Hermite. |
| [B_SPLINE](#B-SPLINE) | Spline basis didefinisikan oleh serangkaian titik kontrol, dimana kurva hanya dijamin melewati titik pertama dan terakhir. |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | Spline kardinal adalah spline Hermite kubik yang tangen‑nya didefinisikan oleh titik akhir dan parameter ketegangan. |
| [CONSTANT](#CONSTANT) | Nilai akan tetap konstan pada nilai titik pertama hingga segmen berikutnya. |
| [LINEAR](#LINEAR) | Interpolasi linear adalah garis lurus antara dua titik. |
| [TCB_SPLINE](#TCB-SPLINE) | Juga disebut spline Kochanek-Bartels, perilaku tangen didefinisikan oleh ketegangan/bias/kontinuitas. |
## Metode

| Metode | Deskripsi |
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


Sebuah spline bezier atau Hermite.

### B_SPLINE {#B-SPLINE}
```
public static final Interpolation B_SPLINE
```


Spline basis didefinisikan oleh serangkaian titik kontrol, dimana kurva hanya dijamin melewati titik pertama dan terakhir.

### CARDINAL_SPLINE {#CARDINAL-SPLINE}
```
public static final Interpolation CARDINAL_SPLINE
```


Spline kardinal adalah spline Hermite kubik yang tangen‑nya didefinisikan oleh titik akhir dan parameter ketegangan.

### CONSTANT {#CONSTANT}
```
public static final Interpolation CONSTANT
```


Nilai akan tetap konstan pada nilai titik pertama hingga segmen berikutnya.

### LINEAR {#LINEAR}
```
public static final Interpolation LINEAR
```


Interpolasi linear adalah garis lurus antara dua titik.

### TCB_SPLINE {#TCB-SPLINE}
```
public static final Interpolation TCB_SPLINE
```


Juga disebut spline Kochanek-Bartels, perilaku tangen didefinisikan oleh ketegangan/bias/kontinuitas.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

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

