---
title: BooleanOperand
second_title: Aspose.3D for Java API リファレンス
description: このクラスは変換されたメッシュをブール演算のオペランドとしてカプセル化します。
type: docs
weight: 22
url: /ja/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

このクラスは変換されたメッシュをブール演算のオペランドとしてカプセル化します。
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | オペランドを取得します。オペランドは [HalfSpace](../../com.aspose.threed/halfspace)、[IMeshConvertible](../../com.aspose.threed/imeshconvertible) または [Node](../../com.aspose.threed/node) のインスタンスである可能性があります。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | ベアな [IMeshConvertible](../../com.aspose.threed/imeshconvertible) インスタンスから [BooleanOperand](../../com.aspose.threed/booleanoperand) インスタンスを作成します。 |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | [IMeshConvertible](../../com.aspose.threed/imeshconvertible) インスタンスと指定された変換から [BooleanOperand](../../com.aspose.threed/booleanoperand) インスタンスを作成します。 |
| [of(Node node)](#of-com.aspose.threed.Node-) | ノードから [BooleanOperand](../../com.aspose.threed/booleanoperand) インスタンスを作成します。 有効なエンティティとして実装された [IMeshConvertible](../../com.aspose.threed/imeshconvertible) が必要です。 |
| [toString()](#toString--) | [BooleanOperand](../../com.aspose.threed/booleanoperand) の文字列表現を取得します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
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


オペランドを取得します。オペランドは [HalfSpace](../../com.aspose.threed/halfspace)、[IMeshConvertible](../../com.aspose.threed/imeshconvertible) または [Node](../../com.aspose.threed/node) のインスタンスである可能性があります。

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


ベアな [IMeshConvertible](../../com.aspose.threed/imeshconvertible) インスタンスから [BooleanOperand](../../com.aspose.threed/booleanoperand) インスタンスを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Boolean 演算のオペランドとして使用されるメッシュで、[IMeshConvertible](../../com.aspose.threed/imeshconvertible) または [HalfSpace](../../com.aspose.threed/halfspace) のインスタンスにすることができます。 |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


[IMeshConvertible](../../com.aspose.threed/imeshconvertible) インスタンスと指定された変換から [BooleanOperand](../../com.aspose.threed/booleanoperand) インスタンスを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Boolean 演算のオペランドとして使用されるメッシュで、[IMeshConvertible](../../com.aspose.threed/imeshconvertible) または [HalfSpace](../../com.aspose.threed/halfspace) のインスタンスにすることができます。 |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | メッシュオブジェクトの変換 |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


ノードから [BooleanOperand](../../com.aspose.threed/booleanoperand) インスタンスを作成します。 有効なエンティティとして実装された [IMeshConvertible](../../com.aspose.threed/imeshconvertible) が必要です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 有効なエンティティとして実装された [IMeshConvertible](../../com.aspose.threed/imeshconvertible) を持つ [Node](../../com.aspose.threed/node) インスタンス |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


[BooleanOperand](../../com.aspose.threed/booleanoperand) の文字列表現を取得します。

**Returns:**
java.lang.String - [BooleanOperand](../../com.aspose.threed/booleanoperand) の文字列表現
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

