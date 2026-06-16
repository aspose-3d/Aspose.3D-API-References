---
title: "StencilAction"
second_title: "Aspose.3D for Java API Referansı"
description: "Stencil test eylemleri"
type: docs
weight: 303
url: /tr/java/com.aspose.threed/stencilaction/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum StencilAction extends Enum<StencilAction>
```

Stencil test eylemleri
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DECREMENT](#DECREMENT) | Mevcut stencil tampon değerini artırır, 0'a sınırlanır. |
| [DECREMENT_WRAP](#DECREMENT-WRAP) | Mevcut stencil tampon değerini azaltır ve sıfıra ulaştığında maksimum değere sarar. |
| [INCREMENT](#INCREMENT) | Mevcut stencil tampon değerini artırır, maksimum değere sınırlanır. |
| [INCREMENT_WRAP](#INCREMENT-WRAP) | Mevcut stencil tampon değerini artırır ve maksimum değere ulaştığında sıfıra sarar. |
| [INVERT](#INVERT) | Bit düzeyinde mevcut stencil tampon değerini tersine çevirir. |
| [KEEP](#KEEP) | Mevcut değeri koru |
| [REPLACE](#REPLACE) | Stencil tamponu, [RenderState.getStencilReference](../../com.aspose.threed/renderstate\#getStencilReference) içinde tanımlandığı gibi ref'e ayarlar. |
| [ZERO](#ZERO) | Stencil tampon değerini 0 olarak ayarlar |
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
### DECREMENT {#DECREMENT}
```
public static final StencilAction DECREMENT
```


Mevcut stencil tampon değerini artırır, 0'a sınırlanır.

### DECREMENT_WRAP {#DECREMENT-WRAP}
```
public static final StencilAction DECREMENT_WRAP
```


Mevcut stencil tampon değerini azaltır ve sıfıra ulaştığında maksimum değere sarar.

### INCREMENT {#INCREMENT}
```
public static final StencilAction INCREMENT
```


Mevcut stencil tampon değerini artırır, maksimum değere sınırlanır.

### INCREMENT_WRAP {#INCREMENT-WRAP}
```
public static final StencilAction INCREMENT_WRAP
```


Mevcut stencil tampon değerini artırır ve maksimum değere ulaştığında sıfıra sarar.

### INVERT {#INVERT}
```
public static final StencilAction INVERT
```


Bit düzeyinde mevcut stencil tampon değerini tersine çevirir.

### KEEP {#KEEP}
```
public static final StencilAction KEEP
```


Mevcut değeri koru

### REPLACE {#REPLACE}
```
public static final StencilAction REPLACE
```


Stencil tamponu, [RenderState.getStencilReference](../../com.aspose.threed/renderstate\#getStencilReference) içinde tanımlandığı gibi ref'e ayarlar.

### ZERO {#ZERO}
```
public static final StencilAction ZERO
```


Stencil tampon değerini 0 olarak ayarlar

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
public static StencilAction valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

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

