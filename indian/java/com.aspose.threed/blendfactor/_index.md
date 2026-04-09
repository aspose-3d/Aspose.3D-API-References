---
title: ब्लेंडफ़ैक्टर
second_title: Aspose.3D for Java API Reference
description: ब्लेंड फैक्टर पिक्सेल अंकगणित को निर्दिष्ट करता है।
type: docs
weight: 266
url: /hi/java/com.aspose.threed/blendfactor/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BlendFactor extends Enum<BlendFactor>
```

ब्लेंड फैक्टर पिक्सेल अंकगणित को निर्दिष्ट करता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CONSTANT_ALPHA](#CONSTANT-ALPHA) | ब्लेंड फ़ैक्टर है vec4(c.a) जहाँ c निर्दिष्ट किया गया है [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) |
| [CONSTANT_COLOR](#CONSTANT-COLOR) | ब्लेंड फ़ैक्टर है c जहाँ c निर्दिष्ट किया गया है [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) |
| [DST_ALPHA](#DST-ALPHA) | ब्लेंड फ़ैक्टर है vec4(dst.a) |
| [DST_COLOR](#DST-COLOR) | ब्लेंड फ़ैक्टर है dst.rgba |
| [ONE](#ONE) | ब्लेंड फ़ैक्टर है vec4(1) |
| [ONE_MINUS_CONSTANT_ALPHA](#ONE-MINUS-CONSTANT-ALPHA) | ब्लेंड फ़ैक्टर है vec4(1 - c.a) जहाँ c निर्दिष्ट किया गया है [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) |
| [ONE_MINUS_CONSTANT_COLOR](#ONE-MINUS-CONSTANT-COLOR) | ब्लेंड फ़ैक्टर है vec4(1) - c जहाँ c निर्दिष्ट किया गया है [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) |
| [ONE_MINUS_DST_ALPHA](#ONE-MINUS-DST-ALPHA) | ब्लेंड फ़ैक्टर है vec4(1 - dst.a) |
| [ONE_MINUS_DST_COLOR](#ONE-MINUS-DST-COLOR) | ब्लेंड फ़ैक्टर है vec4(1) - dst.rgba |
| [ONE_MINUS_SRC_ALPHA](#ONE-MINUS-SRC-ALPHA) | ब्लेंड फ़ैक्टर है vec4(1 - src.a) |
| [ONE_MINUS_SRC_COLOR](#ONE-MINUS-SRC-COLOR) | ब्लेंड फ़ैक्टर है vec4(1) - src.rgba |
| [SRC_ALPHA](#SRC-ALPHA) | ब्लेंड फ़ैक्टर है vec4(src.a) |
| [SRC_ALPHA_SATURATE](#SRC-ALPHA-SATURATE) | ब्लेंड फ़ैक्टर है min(src.a, 1 - dst.a) |
| [SRC_COLOR](#SRC-COLOR) | The blend factor is src.rgba |
| [ZERO](#ZERO) | The blend factor is vec4(0) |
## Methods

| Method | विवरण |
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


ब्लेंड फ़ैक्टर है vec4(c.a) जहाँ c निर्दिष्ट किया गया है [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor)

### CONSTANT_COLOR {#CONSTANT-COLOR}
```
public static final BlendFactor CONSTANT_COLOR
```


ब्लेंड फ़ैक्टर है c जहाँ c निर्दिष्ट किया गया है [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor)

### DST_ALPHA {#DST-ALPHA}
```
public static final BlendFactor DST_ALPHA
```


ब्लेंड फ़ैक्टर है vec4(dst.a)

### DST_COLOR {#DST-COLOR}
```
public static final BlendFactor DST_COLOR
```


ब्लेंड फ़ैक्टर है dst.rgba

### ONE {#ONE}
```
public static final BlendFactor ONE
```


ब्लेंड फ़ैक्टर है vec4(1)

### ONE_MINUS_CONSTANT_ALPHA {#ONE-MINUS-CONSTANT-ALPHA}
```
public static final BlendFactor ONE_MINUS_CONSTANT_ALPHA
```


ब्लेंड फ़ैक्टर है vec4(1 - c.a) जहाँ c निर्दिष्ट किया गया है [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor)

### ONE_MINUS_CONSTANT_COLOR {#ONE-MINUS-CONSTANT-COLOR}
```
public static final BlendFactor ONE_MINUS_CONSTANT_COLOR
```


ब्लेंड फ़ैक्टर है vec4(1) - c जहाँ c निर्दिष्ट किया गया है [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor)

### ONE_MINUS_DST_ALPHA {#ONE-MINUS-DST-ALPHA}
```
public static final BlendFactor ONE_MINUS_DST_ALPHA
```


ब्लेंड फ़ैक्टर है vec4(1 - dst.a)

### ONE_MINUS_DST_COLOR {#ONE-MINUS-DST-COLOR}
```
public static final BlendFactor ONE_MINUS_DST_COLOR
```


ब्लेंड फ़ैक्टर है vec4(1) - dst.rgba

### ONE_MINUS_SRC_ALPHA {#ONE-MINUS-SRC-ALPHA}
```
public static final BlendFactor ONE_MINUS_SRC_ALPHA
```


ब्लेंड फ़ैक्टर है vec4(1 - src.a)

### ONE_MINUS_SRC_COLOR {#ONE-MINUS-SRC-COLOR}
```
public static final BlendFactor ONE_MINUS_SRC_COLOR
```


ब्लेंड फ़ैक्टर है vec4(1) - src.rgba

### SRC_ALPHA {#SRC-ALPHA}
```
public static final BlendFactor SRC_ALPHA
```


ब्लेंड फ़ैक्टर है vec4(src.a)

### SRC_ALPHA_SATURATE {#SRC-ALPHA-SATURATE}
```
public static final BlendFactor SRC_ALPHA_SATURATE
```


ब्लेंड फ़ैक्टर है min(src.a, 1 - dst.a)

### SRC_COLOR {#SRC-COLOR}
```
public static final BlendFactor SRC_COLOR
```


The blend factor is src.rgba

### ZERO {#ZERO}
```
public static final BlendFactor ZERO
```


The blend factor is vec4(0)

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

