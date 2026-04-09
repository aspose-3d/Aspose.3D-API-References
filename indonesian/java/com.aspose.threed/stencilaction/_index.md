---
title: StencilAction
second_title: Referensi API Aspose.3D untuk Java
description: Aksi pengujian stensil
type: docs
weight: 303
url: /id/java/com.aspose.threed/stencilaction/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum StencilAction extends Enum<StencilAction>
```

Aksi pengujian stensil
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [DECREMENT](#DECREMENT) | Meningkatkan nilai buffer stencil saat ini, dibatasi hingga 0. |
| [DECREMENT_WRAP](#DECREMENT-WRAP) | Mengurangi nilai buffer stencil saat ini dan membungkusnya ke nilai maksimum ketika mencapai nol. |
| [INCREMENT](#INCREMENT) | Meningkatkan nilai buffer stencil saat ini, dibatasi hingga nilai maksimum. |
| [INCREMENT_WRAP](#INCREMENT-WRAP) | Meningkatkan nilai buffer stencil saat ini dan membungkusnya ke nol ketika mencapai nilai maksimum. |
| [INVERT](#INVERT) | Membalik nilai buffer stencil saat ini secara bitwise. |
| [KEEP](#KEEP) | Pertahankan nilai saat ini |
| [REPLACE](#REPLACE) | Mengatur buffer stencil ke ref sebagaimana didefinisikan dalam [RenderState.getStencilReference](../../com.aspose.threed/renderstate\#getStencilReference) |
| [ZERO](#ZERO) | Mengatur nilai buffer stensil menjadi 0 |
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
### DECREMENT {#DECREMENT}
```
public static final StencilAction DECREMENT
```


Meningkatkan nilai buffer stencil saat ini, dibatasi hingga 0.

### DECREMENT_WRAP {#DECREMENT-WRAP}
```
public static final StencilAction DECREMENT_WRAP
```


Mengurangi nilai buffer stencil saat ini dan membungkusnya ke nilai maksimum ketika mencapai nol.

### INCREMENT {#INCREMENT}
```
public static final StencilAction INCREMENT
```


Meningkatkan nilai buffer stencil saat ini, dibatasi hingga nilai maksimum.

### INCREMENT_WRAP {#INCREMENT-WRAP}
```
public static final StencilAction INCREMENT_WRAP
```


Meningkatkan nilai buffer stencil saat ini dan membungkusnya ke nol ketika mencapai nilai maksimum.

### INVERT {#INVERT}
```
public static final StencilAction INVERT
```


Membalik nilai buffer stencil saat ini secara bitwise.

### KEEP {#KEEP}
```
public static final StencilAction KEEP
```


Pertahankan nilai saat ini

### REPLACE {#REPLACE}
```
public static final StencilAction REPLACE
```


Mengatur buffer stencil ke ref sebagaimana didefinisikan dalam [RenderState.getStencilReference](../../com.aspose.threed/renderstate\#getStencilReference)

### ZERO {#ZERO}
```
public static final StencilAction ZERO
```


Mengatur nilai buffer stensil menjadi 0

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
public static StencilAction valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

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

