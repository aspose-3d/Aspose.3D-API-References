---
title: "StencilAction"
second_title: "Aspose.3D for Java API 参考"
description: "模板测试操作"
type: docs
weight: 303
url: /zh/java/com.aspose.threed/stencilaction/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum StencilAction extends Enum<StencilAction>
```

模板测试操作
## 字段

| 字段 | 描述 |
| --- | --- |
| [DECREMENT](#DECREMENT) | 将当前模板缓冲区值递增，限制在 0。 |
| [DECREMENT_WRAP](#DECREMENT-WRAP) | 将当前模板缓冲区值递减，当达到零时将其包装到最大值。 |
| [INCREMENT](#INCREMENT) | 将当前模板缓冲区值递增，限制在最大值。 |
| [INCREMENT_WRAP](#INCREMENT-WRAP) | 将当前模板缓冲区值递增，当达到最大值时将其包装为零。 |
| [INVERT](#INVERT) | 对当前模板缓冲区值进行位反转。 |
| [KEEP](#KEEP) | 保持当前值 |
| [REPLACE](#REPLACE) | 将模板缓冲区设置为在 [RenderState.getStencilReference](../../com.aspose.threed/renderstate\#getStencilReference) 中定义的 ref。 |
| [ZERO](#ZERO) | 将模板缓冲区的值设置为 0 |
## 方法

| 方法 | 描述 |
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


将当前模板缓冲区值递增，限制在 0。

### DECREMENT_WRAP {#DECREMENT-WRAP}
```
public static final StencilAction DECREMENT_WRAP
```


将当前模板缓冲区值递减，当达到零时将其包装到最大值。

### INCREMENT {#INCREMENT}
```
public static final StencilAction INCREMENT
```


将当前模板缓冲区值递增，限制在最大值。

### INCREMENT_WRAP {#INCREMENT-WRAP}
```
public static final StencilAction INCREMENT_WRAP
```


将当前模板缓冲区值递增，当达到最大值时将其包装为零。

### INVERT {#INVERT}
```
public static final StencilAction INVERT
```


对当前模板缓冲区值进行位反转。

### KEEP {#KEEP}
```
public static final StencilAction KEEP
```


保持当前值

### REPLACE {#REPLACE}
```
public static final StencilAction REPLACE
```


将模板缓冲区设置为在 [RenderState.getStencilReference](../../com.aspose.threed/renderstate\#getStencilReference) 中定义的 ref。

### ZERO {#ZERO}
```
public static final StencilAction ZERO
```


将模板缓冲区的值设置为 0

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

