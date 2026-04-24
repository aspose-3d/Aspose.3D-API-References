---
title: BooleanOperand
second_title: Aspose.3D for Java API 레퍼런스
description: 이 클래스는 변환된 메쉬를 Boolean 연산 피연산자로 캡슐화합니다.
type: docs
weight: 22
url: /ko/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

이 클래스는 변환된 메쉬를 Boolean 연산의 피연산자로 캡슐화합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | 피연산자를 가져옵니다. 이는 [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 또는 [Node](../../com.aspose.threed/node) 인스턴스일 수 있습니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | 베어 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 인스턴스로부터 [BooleanOperand](../../com.aspose.threed/booleanoperand) 인스턴스를 생성합니다. |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 인스턴스와 지정된 변환을 사용하여 [BooleanOperand](../../com.aspose.threed/booleanoperand) 인스턴스를 생성합니다. |
| [of(Node node)](#of-com.aspose.threed.Node-) | 노드에서 [BooleanOperand](../../com.aspose.threed/booleanoperand) 인스턴스를 생성하려면, 유효한 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 구현 엔터티가 필요합니다. |
| [toString()](#toString--) | [BooleanOperand](../../com.aspose.threed/booleanoperand)의 문자열 표현을 가져옵니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
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
### getOperand() {#getOperand--}
```
public A3DObject getOperand()
```


피연산자를 가져옵니다. 이는 [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 또는 [Node](../../com.aspose.threed/node) 인스턴스일 수 있습니다.

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


베어 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 인스턴스로부터 [BooleanOperand](../../com.aspose.threed/booleanoperand) 인스턴스를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Boolean 연산의 피연산자로 사용되는 메시는 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 또는 [HalfSpace](../../com.aspose.threed/halfspace) 인스턴스일 수 있습니다. |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


[IMeshConvertible](../../com.aspose.threed/imeshconvertible) 인스턴스와 지정된 변환을 사용하여 [BooleanOperand](../../com.aspose.threed/booleanoperand) 인스턴스를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Boolean 연산의 피연산자로 사용되는 메시는 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 또는 [HalfSpace](../../com.aspose.threed/halfspace) 인스턴스일 수 있습니다. |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | 메시 객체의 변환 |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


노드에서 [BooleanOperand](../../com.aspose.threed/booleanoperand) 인스턴스를 생성하려면, 유효한 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 구현 엔터티가 필요합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 유효한 [IMeshConvertible](../../com.aspose.threed/imeshconvertible) 구현 엔터티를 가진 [Node](../../com.aspose.threed/node) 인스턴스 |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


[BooleanOperand](../../com.aspose.threed/booleanoperand)의 문자열 표현을 가져옵니다.

**Returns:**
java.lang.String - [BooleanOperand](../../com.aspose.threed/booleanoperand)의 문자열 표현
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

