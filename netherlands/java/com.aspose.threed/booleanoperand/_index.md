---
title: BooleanOperand
second_title: Aspose.3D for Java API-referentie
description: Deze klasse omvat het getransformeerde mesh als operand voor Booleaanse bewerkingen.
type: docs
weight: 22
url: /nl/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

Deze klasse encapsuleert het getransformeerde mesh als operand van een Boolean‑operatie.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | Haalt de operand op; dit kan een instantie zijn van [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) of [Node](../../com.aspose.threed/node). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | Maak een [BooleanOperand](../../com.aspose.threed/booleanoperand) instantie aan vanuit een kale [IMeshConvertible](../../com.aspose.threed/imeshconvertible) instantie. |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | Maak een [BooleanOperand](../../com.aspose.threed/booleanoperand) instantie aan vanuit een [IMeshConvertible](../../com.aspose.threed/imeshconvertible) instantie en een gespecificeerde transformatie. |
| [of(Node node)](#of-com.aspose.threed.Node-) | Maak een [BooleanOperand](../../com.aspose.threed/booleanoperand) instantie aan vanuit een node, een geldige entiteit die [IMeshConvertible](../../com.aspose.threed/imeshconvertible) implementeert is vereist |
| [toString()](#toString--) | Haalt de tekenreeksrepresentatie van [BooleanOperand](../../com.aspose.threed/booleanoperand) op. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de operand op; dit kan een instantie zijn van [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) of [Node](../../com.aspose.threed/node).

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


Maak een [BooleanOperand](../../com.aspose.threed/booleanoperand) instantie aan vanuit een kale [IMeshConvertible](../../com.aspose.threed/imeshconvertible) instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | De mesh die wordt gebruikt als operand van de Booleaanse bewerking, kan een instantie zijn van [IMeshConvertible](../../com.aspose.threed/imeshconvertible) of [HalfSpace](../../com.aspose.threed/halfspace) |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


Maak een [BooleanOperand](../../com.aspose.threed/booleanoperand) instantie aan vanuit een [IMeshConvertible](../../com.aspose.threed/imeshconvertible) instantie en een gespecificeerde transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | De mesh die wordt gebruikt als operand van de Booleaanse bewerking, kan een instantie zijn van [IMeshConvertible](../../com.aspose.threed/imeshconvertible) of [HalfSpace](../../com.aspose.threed/halfspace) |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | De transformatie van het mesh‑object |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


Maak een [BooleanOperand](../../com.aspose.threed/booleanoperand) instantie aan vanuit een node, een geldige entiteit die [IMeshConvertible](../../com.aspose.threed/imeshconvertible) implementeert is vereist

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Een [Node](../../com.aspose.threed/node) instantie met een geldige entiteit die [IMeshConvertible](../../com.aspose.threed/imeshconvertible) implementeert |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


Haalt de tekenreeksrepresentatie van [BooleanOperand](../../com.aspose.threed/booleanoperand) op.

**Returns:**
java.lang.String - De tekenreeksrepresentatie van [BooleanOperand](../../com.aspose.threed/booleanoperand)
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

