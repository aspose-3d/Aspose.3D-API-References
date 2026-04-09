---
title: BooleanOperand
second_title: Aspose.3D for Java API-referens
description: Denna klass kapslar in det transformerade meshet som operand för Booleska operationer.
type: docs
weight: 22
url: /sv/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

Denna klass kapslar in det transformerade meshet som operand för en Boolesk operation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | Hämtar operand, den kan vara en instans av [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) eller [Node](../../com.aspose.threed/node). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | Skapa en [BooleanOperand](../../com.aspose.threed/booleanoperand) instans från en rå [IMeshConvertible](../../com.aspose.threed/imeshconvertible) instans. |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | Skapa en [BooleanOperand](../../com.aspose.threed/booleanoperand) instans från en [IMeshConvertible](../../com.aspose.threed/imeshconvertible) instans och en specificerad transform. |
| [of(Node node)](#of-com.aspose.threed.Node-) | Skapa en [BooleanOperand](../../com.aspose.threed/booleanoperand) instans från en nod, ett giltigt objekt som implementerar [IMeshConvertible](../../com.aspose.threed/imeshconvertible) krävs. |
| [toString()](#toString--) | Hämtar strängrepresentationen av [BooleanOperand](../../com.aspose.threed/booleanoperand) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar operand, den kan vara en instans av [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) eller [Node](../../com.aspose.threed/node).

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


Skapa en [BooleanOperand](../../com.aspose.threed/booleanoperand) instans från en rå [IMeshConvertible](../../com.aspose.threed/imeshconvertible) instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Det mesh som används som operand för en boolesk operation, det kan vara en instans av [IMeshConvertible](../../com.aspose.threed/imeshconvertible) eller [HalfSpace](../../com.aspose.threed/halfspace) |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


Skapa en [BooleanOperand](../../com.aspose.threed/booleanoperand) instans från en [IMeshConvertible](../../com.aspose.threed/imeshconvertible) instans och en specificerad transform.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Det mesh som används som operand för en boolesk operation, det kan vara en instans av [IMeshConvertible](../../com.aspose.threed/imeshconvertible) eller [HalfSpace](../../com.aspose.threed/halfspace) |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | Transformen för mesh-objektet |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


Skapa en [BooleanOperand](../../com.aspose.threed/booleanoperand) instans från en nod, ett giltigt objekt som implementerar [IMeshConvertible](../../com.aspose.threed/imeshconvertible) krävs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | En [Node](../../com.aspose.threed/node) instans med ett giltigt objekt som implementerar [IMeshConvertible](../../com.aspose.threed/imeshconvertible) |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


Hämtar strängrepresentationen av [BooleanOperand](../../com.aspose.threed/booleanoperand)

**Returns:**
java.lang.String - Strängrepresentationen av [BooleanOperand](../../com.aspose.threed/booleanoperand)
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

