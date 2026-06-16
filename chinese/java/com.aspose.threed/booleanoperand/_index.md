---
title: "BooleanOperand"
second_title: "Aspose.3D for Java API 参考"
description: "此类将变换后的网格封装为布尔运算的操作数。"
type: docs
weight: 22
url: /zh/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

此类将变换后的网格封装为布尔运算的操作数。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | 获取操作数，它可以是 [HalfSpace](../../com.aspose.threed/halfspace)、[IMeshConvertible](../../com.aspose.threed/imeshconvertible) 或 [Node](../../com.aspose.threed/node) 的实例。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | 从裸的 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 实例构造一个 [BooleanOperand](../../com.aspose.threed/booleanoperand) 实例。 |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | 从 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 实例和指定的变换构造一个 [BooleanOperand](../../com.aspose.threed/booleanoperand) 实例。 |
| [of(Node node)](#of-com.aspose.threed.Node-) | 从节点构造一个 [BooleanOperand](../../com.aspose.threed/booleanoperand) 实例，需要实现了 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 的有效实体。 |
| [toString()](#toString--) | 获取 [BooleanOperand](../../com.aspose.threed/booleanoperand) 的字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
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
### getOperand() {#getOperand--}
```
public A3DObject getOperand()
```


获取操作数，它可以是 [HalfSpace](../../com.aspose.threed/halfspace)、[IMeshConvertible](../../com.aspose.threed/imeshconvertible) 或 [Node](../../com.aspose.threed/node) 的实例。

**Returns:**
[A3DObject](../../com.aspose.threed/a3dobject) - the operand, it can be an instance of [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) or [Node](../../com.aspose.threed/node).
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### of(Entity mesh) {#of-com.aspose.threed.Entity-}
```
public static BooleanOperand of(Entity mesh)
```


从裸的 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 实例构造一个 [BooleanOperand](../../com.aspose.threed/booleanoperand) 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | 用作布尔运算操作数的网格，它可以是 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 或 [HalfSpace](../../com.aspose.threed/halfspace) 的实例。 |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


从 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 实例和指定的变换构造一个 [BooleanOperand](../../com.aspose.threed/booleanoperand) 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | 用作布尔运算操作数的网格，它可以是 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 或 [HalfSpace](../../com.aspose.threed/halfspace) 的实例。 |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | 网格对象的变换。 |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


从节点构造一个 [BooleanOperand](../../com.aspose.threed/booleanoperand) 实例，需要实现了 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 的有效实体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 一个实现了 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 的有效实体的 [Node](../../com.aspose.threed/node) 实例。 |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


获取 [BooleanOperand](../../com.aspose.threed/booleanoperand) 的字符串表示。

**Returns:**
java.lang.String - [BooleanOperand](../../com.aspose.threed/booleanoperand) 的字符串表示。
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

