---
title: BlendFactor
second_title: Aspose.3D for Java API 레퍼런스
description: 블렌드 팩터는 픽셀 연산을 지정합니다.
type: docs
weight: 266
url: /ko/java/com.aspose.threed/blendfactor/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BlendFactor extends Enum<BlendFactor>
```

블렌드 팩터는 픽셀 연산을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [CONSTANT_ALPHA](#CONSTANT-ALPHA) | 블렌드 팩터는 vec4(c.a)이며, c는 [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) 에서 지정됩니다. |
| [CONSTANT_COLOR](#CONSTANT-COLOR) | 블렌드 팩터는 c이며, c는 [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) 에서 지정됩니다. |
| [DST_ALPHA](#DST-ALPHA) | 블렌드 팩터는 vec4(dst.a)입니다. |
| [DST_COLOR](#DST-COLOR) | 블렌드 팩터는 dst.rgba입니다. |
| [ONE](#ONE) | 블렌드 팩터는 vec4(1)입니다. |
| [ONE_MINUS_CONSTANT_ALPHA](#ONE-MINUS-CONSTANT-ALPHA) | 블렌드 팩터는 vec4(1 - c.a)이며, c는 [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) 에서 지정됩니다. |
| [ONE_MINUS_CONSTANT_COLOR](#ONE-MINUS-CONSTANT-COLOR) | 블렌드 팩터는 vec4(1) - c이며, c는 [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) 에서 지정됩니다. |
| [ONE_MINUS_DST_ALPHA](#ONE-MINUS-DST-ALPHA) | 블렌드 팩터는 vec4(1 - dst.a)입니다. |
| [ONE_MINUS_DST_COLOR](#ONE-MINUS-DST-COLOR) | 블렌드 팩터는 vec4(1) - dst.rgba입니다. |
| [ONE_MINUS_SRC_ALPHA](#ONE-MINUS-SRC-ALPHA) | 블렌드 팩터는 vec4(1 - src.a)입니다. |
| [ONE_MINUS_SRC_COLOR](#ONE-MINUS-SRC-COLOR) | 블렌드 팩터는 vec4(1) - src.rgba입니다. |
| [SRC_ALPHA](#SRC-ALPHA) | 블렌드 팩터는 vec4(src.a)입니다. |
| [SRC_ALPHA_SATURATE](#SRC-ALPHA-SATURATE) | 블렌드 팩터는 min(src.a, 1 - dst.a)입니다. |
| [SRC_COLOR](#SRC-COLOR) | 블렌드 팩터는 src.rgba입니다 |
| [ZERO](#ZERO) | 블렌드 팩터는 vec4(0)입니다 |
## 메서드

| 메서드 | 설명 |
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


블렌드 팩터는 vec4(c.a)이며, c는 [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) 에서 지정됩니다.

### CONSTANT_COLOR {#CONSTANT-COLOR}
```
public static final BlendFactor CONSTANT_COLOR
```


블렌드 팩터는 c이며, c는 [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) 에서 지정됩니다.

### DST_ALPHA {#DST-ALPHA}
```
public static final BlendFactor DST_ALPHA
```


블렌드 팩터는 vec4(dst.a)입니다.

### DST_COLOR {#DST-COLOR}
```
public static final BlendFactor DST_COLOR
```


블렌드 팩터는 dst.rgba입니다.

### ONE {#ONE}
```
public static final BlendFactor ONE
```


블렌드 팩터는 vec4(1)입니다.

### ONE_MINUS_CONSTANT_ALPHA {#ONE-MINUS-CONSTANT-ALPHA}
```
public static final BlendFactor ONE_MINUS_CONSTANT_ALPHA
```


블렌드 팩터는 vec4(1 - c.a)이며, c는 [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) 에서 지정됩니다.

### ONE_MINUS_CONSTANT_COLOR {#ONE-MINUS-CONSTANT-COLOR}
```
public static final BlendFactor ONE_MINUS_CONSTANT_COLOR
```


블렌드 팩터는 vec4(1) - c이며, c는 [RenderState.getBlendColor](../../com.aspose.threed/renderstate\#getBlendColor) 에서 지정됩니다.

### ONE_MINUS_DST_ALPHA {#ONE-MINUS-DST-ALPHA}
```
public static final BlendFactor ONE_MINUS_DST_ALPHA
```


블렌드 팩터는 vec4(1 - dst.a)입니다.

### ONE_MINUS_DST_COLOR {#ONE-MINUS-DST-COLOR}
```
public static final BlendFactor ONE_MINUS_DST_COLOR
```


블렌드 팩터는 vec4(1) - dst.rgba입니다.

### ONE_MINUS_SRC_ALPHA {#ONE-MINUS-SRC-ALPHA}
```
public static final BlendFactor ONE_MINUS_SRC_ALPHA
```


블렌드 팩터는 vec4(1 - src.a)입니다.

### ONE_MINUS_SRC_COLOR {#ONE-MINUS-SRC-COLOR}
```
public static final BlendFactor ONE_MINUS_SRC_COLOR
```


블렌드 팩터는 vec4(1) - src.rgba입니다.

### SRC_ALPHA {#SRC-ALPHA}
```
public static final BlendFactor SRC_ALPHA
```


블렌드 팩터는 vec4(src.a)입니다.

### SRC_ALPHA_SATURATE {#SRC-ALPHA-SATURATE}
```
public static final BlendFactor SRC_ALPHA_SATURATE
```


블렌드 팩터는 min(src.a, 1 - dst.a)입니다.

### SRC_COLOR {#SRC-COLOR}
```
public static final BlendFactor SRC_COLOR
```


블렌드 팩터는 src.rgba입니다

### ZERO {#ZERO}
```
public static final BlendFactor ZERO
```


블렌드 팩터는 vec4(0)입니다

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

