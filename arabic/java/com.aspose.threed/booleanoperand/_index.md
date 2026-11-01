---
title: "BooleanOperand"
second_title: "مرجع Aspose.3D لـ Java API"
description: "تُغلف هذه الفئة الشبكة المُحوَّلة كمعامل عمليات بوليانية."
type: docs
weight: 22
url: /ar/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

تُغلف هذه الفئة الشبكة المُحوَّلة كمعامل لعملية بوليانية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | يحصل على المعامل، ويمكن أن يكون مثيلاً من [HalfSpace](../../com.aspose.threed/halfspace)، أو [IMeshConvertible](../../com.aspose.threed/imeshconvertible)، أو [Node](../../com.aspose.threed/node). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | إنشاء كائن [BooleanOperand](../../com.aspose.threed/booleanoperand) من كائن [IMeshConvertible](../../com.aspose.threed/imeshconvertible) عاري. |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | إنشاء كائن [BooleanOperand](../../com.aspose.threed/booleanoperand) من كائن [IMeshConvertible](../../com.aspose.threed/imeshconvertible) وتطبيق التحويل المحدد. |
| [of(Node node)](#of-com.aspose.threed.Node-) | إنشاء كائن [BooleanOperand](../../com.aspose.threed/booleanoperand) من عقدة، يلزم وجود كيان صالح يطبق [IMeshConvertible](../../com.aspose.threed/imeshconvertible) |
| [toString()](#toString--) | يحصل على تمثيل النص لـ [BooleanOperand](../../com.aspose.threed/booleanoperand) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
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
### getOperand() {#getOperand--}
```
public A3DObject getOperand()
```


يحصل على المعامل، ويمكن أن يكون مثيلاً من [HalfSpace](../../com.aspose.threed/halfspace)، أو [IMeshConvertible](../../com.aspose.threed/imeshconvertible)، أو [Node](../../com.aspose.threed/node).

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


إنشاء كائن [BooleanOperand](../../com.aspose.threed/booleanoperand) من كائن [IMeshConvertible](../../com.aspose.threed/imeshconvertible) عاري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | المجسم المستخدم كمعامل عملية Boolean، يمكن أن يكون كائنًا من [IMeshConvertible](../../com.aspose.threed/imeshconvertible) أو [HalfSpace](../../com.aspose.threed/halfspace) |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


إنشاء كائن [BooleanOperand](../../com.aspose.threed/booleanoperand) من كائن [IMeshConvertible](../../com.aspose.threed/imeshconvertible) وتطبيق التحويل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | المجسم المستخدم كمعامل عملية Boolean، يمكن أن يكون كائنًا من [IMeshConvertible](../../com.aspose.threed/imeshconvertible) أو [HalfSpace](../../com.aspose.threed/halfspace) |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | تحويل كائن المجسم |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


إنشاء كائن [BooleanOperand](../../com.aspose.threed/booleanoperand) من عقدة، يلزم وجود كيان صالح يطبق [IMeshConvertible](../../com.aspose.threed/imeshconvertible)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | كائن [Node](../../com.aspose.threed/node) مع كيان صالح يطبق [IMeshConvertible](../../com.aspose.threed/imeshconvertible) |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


يحصل على تمثيل النص لـ [BooleanOperand](../../com.aspose.threed/booleanoperand)

**Returns:**
java.lang.String - تمثيل النص لـ [BooleanOperand](../../com.aspose.threed/booleanoperand)
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

