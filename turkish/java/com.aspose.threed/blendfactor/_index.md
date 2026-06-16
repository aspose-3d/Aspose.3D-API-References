---
title: "BlendFactor"
second_title: "Aspose.3D for Java API Referansı"
description: "Karışım faktörü piksel aritmetiğini belirtir."
type: docs
weight: 266
url: /tr/java/com.aspose.threed/blendfactor/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BlendFactor extends Enum<BlendFactor>
```

Karışım faktörü piksel aritmetiğini belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CONSTANT_ALPHA](#CONSTANT-ALPHA) | Karıştırma faktörü vec4(c.a) şeklindedir, c ise [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) içinde belirtilir. |
| [CONSTANT_COLOR](#CONSTANT-COLOR) | Karıştırma faktörü c'dir, c ise [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) içinde belirtilir. |
| [DST_ALPHA](#DST-ALPHA) | Karıştırma faktörü vec4(dst.a) şeklindedir. |
| [DST_COLOR](#DST-COLOR) | Karıştırma faktörü dst.rgba şeklindedir. |
| [ONE](#ONE) | Karıştırma faktörü vec4(1) şeklindedir. |
| [ONE_MINUS_CONSTANT_ALPHA](#ONE-MINUS-CONSTANT-ALPHA) | Karıştırma faktörü vec4(1 - c.a) şeklindedir, c ise [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) içinde belirtilir. |
| [ONE_MINUS_CONSTANT_COLOR](#ONE-MINUS-CONSTANT-COLOR) | Karıştırma faktörü vec4(1) - c şeklindedir, c ise [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) içinde belirtilir. |
| [ONE_MINUS_DST_ALPHA](#ONE-MINUS-DST-ALPHA) | Karıştırma faktörü vec4(1 - dst.a) şeklindedir. |
| [ONE_MINUS_DST_COLOR](#ONE-MINUS-DST-COLOR) | Karıştırma faktörü vec4(1) - dst.rgba şeklindedir. |
| [ONE_MINUS_SRC_ALPHA](#ONE-MINUS-SRC-ALPHA) | Karıştırma faktörü vec4(1 - src.a) şeklindedir. |
| [ONE_MINUS_SRC_COLOR](#ONE-MINUS-SRC-COLOR) | Karıştırma faktörü vec4(1) - src.rgba şeklindedir. |
| [SRC_ALPHA](#SRC-ALPHA) | Karıştırma faktörü vec4(src.a) şeklindedir. |
| [SRC_ALPHA_SATURATE](#SRC-ALPHA-SATURATE) | Karıştırma faktörü min(src.a, 1 - dst.a) şeklindedir. |
| [SRC_COLOR](#SRC-COLOR) | Karışım faktörü src.rgba'dir |
| [ZERO](#ZERO) | Karışım faktörü vec4(0)'dır |
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
### CONSTANT_ALPHA {#CONSTANT-ALPHA}
```
public static final BlendFactor CONSTANT_ALPHA
```


Karıştırma faktörü vec4(c.a) şeklindedir, c ise [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) içinde belirtilir.

### CONSTANT_COLOR {#CONSTANT-COLOR}
```
public static final BlendFactor CONSTANT_COLOR
```


Karıştırma faktörü c'dir, c ise [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) içinde belirtilir.

### DST_ALPHA {#DST-ALPHA}
```
public static final BlendFactor DST_ALPHA
```


Karıştırma faktörü vec4(dst.a) şeklindedir.

### DST_COLOR {#DST-COLOR}
```
public static final BlendFactor DST_COLOR
```


Karıştırma faktörü dst.rgba şeklindedir.

### ONE {#ONE}
```
public static final BlendFactor ONE
```


Karıştırma faktörü vec4(1) şeklindedir.

### ONE_MINUS_CONSTANT_ALPHA {#ONE-MINUS-CONSTANT-ALPHA}
```
public static final BlendFactor ONE_MINUS_CONSTANT_ALPHA
```


Karıştırma faktörü vec4(1 - c.a) şeklindedir, c ise [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) içinde belirtilir.

### ONE_MINUS_CONSTANT_COLOR {#ONE-MINUS-CONSTANT-COLOR}
```
public static final BlendFactor ONE_MINUS_CONSTANT_COLOR
```


Karıştırma faktörü vec4(1) - c şeklindedir, c ise [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) içinde belirtilir.

### ONE_MINUS_DST_ALPHA {#ONE-MINUS-DST-ALPHA}
```
public static final BlendFactor ONE_MINUS_DST_ALPHA
```


Karıştırma faktörü vec4(1 - dst.a) şeklindedir.

### ONE_MINUS_DST_COLOR {#ONE-MINUS-DST-COLOR}
```
public static final BlendFactor ONE_MINUS_DST_COLOR
```


Karıştırma faktörü vec4(1) - dst.rgba şeklindedir.

### ONE_MINUS_SRC_ALPHA {#ONE-MINUS-SRC-ALPHA}
```
public static final BlendFactor ONE_MINUS_SRC_ALPHA
```


Karıştırma faktörü vec4(1 - src.a) şeklindedir.

### ONE_MINUS_SRC_COLOR {#ONE-MINUS-SRC-COLOR}
```
public static final BlendFactor ONE_MINUS_SRC_COLOR
```


Karıştırma faktörü vec4(1) - src.rgba şeklindedir.

### SRC_ALPHA {#SRC-ALPHA}
```
public static final BlendFactor SRC_ALPHA
```


Karıştırma faktörü vec4(src.a) şeklindedir.

### SRC_ALPHA_SATURATE {#SRC-ALPHA-SATURATE}
```
public static final BlendFactor SRC_ALPHA_SATURATE
```


Karıştırma faktörü min(src.a, 1 - dst.a) şeklindedir.

### SRC_COLOR {#SRC-COLOR}
```
public static final BlendFactor SRC_COLOR
```


Karışım faktörü src.rgba'dir

### ZERO {#ZERO}
```
public static final BlendFactor ZERO
```


Karışım faktörü vec4(0)'dır

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
public static BlendFactor valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor)
### values() {#values--}
```
public static BlendFactor[] values()
```




**Returns:**
com.aspose.threed.BlendFactor[]
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

