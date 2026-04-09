---
title: BooleanOperand
second_title: Aspose.3D for Java API Reference
description: Questa classe incapsula la mesh trasformata come operando delle operazioni Boolean.
type: docs
weight: 22
url: /it/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

Questa classe incapsula la mesh trasformata come operando dell'operazione booleana.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | Ottiene l'operando, può essere un'istanza di [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) o [Node](../../com.aspose.threed/node). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | Crea un'istanza di [BooleanOperand](../../com.aspose.threed/booleanoperand) a partire da una semplice istanza di [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | Crea un'istanza di [BooleanOperand](../../com.aspose.threed/booleanoperand) a partire da un'istanza di [IMeshConvertible](../../com.aspose.threed/imeshconvertible) e da una trasformazione specificata. |
| [of(Node node)](#of-com.aspose.threed.Node-) | Crea un'istanza di [BooleanOperand](../../com.aspose.threed/booleanoperand) a partire da un nodo; è richiesta un'entità valida che implementi [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |
| [toString()](#toString--) | Restituisce la rappresentazione stringa di [BooleanOperand](../../com.aspose.threed/booleanoperand). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene l'operando, può essere un'istanza di [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) o [Node](../../com.aspose.threed/node).

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


Crea un'istanza di [BooleanOperand](../../com.aspose.threed/booleanoperand) a partire da una semplice istanza di [IMeshConvertible](../../com.aspose.threed/imeshconvertible).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | La mesh utilizzata come operando dell'operazione booleana, può essere un'istanza di [IMeshConvertible](../../com.aspose.threed/imeshconvertible) o di [HalfSpace](../../com.aspose.threed/halfspace). |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


Crea un'istanza di [BooleanOperand](../../com.aspose.threed/booleanoperand) a partire da un'istanza di [IMeshConvertible](../../com.aspose.threed/imeshconvertible) e da una trasformazione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | La mesh utilizzata come operando dell'operazione booleana, può essere un'istanza di [IMeshConvertible](../../com.aspose.threed/imeshconvertible) o di [HalfSpace](../../com.aspose.threed/halfspace). |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | La trasformazione dell'oggetto mesh. |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


Crea un'istanza di [BooleanOperand](../../com.aspose.threed/booleanoperand) a partire da un nodo; è richiesta un'entità valida che implementi [IMeshConvertible](../../com.aspose.threed/imeshconvertible).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Un'istanza di [Node](../../com.aspose.threed/node) con un'entità valida che implementa [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


Restituisce la rappresentazione stringa di [BooleanOperand](../../com.aspose.threed/booleanoperand).

**Returns:**
java.lang.String – La rappresentazione stringa di [BooleanOperand](../../com.aspose.threed/booleanoperand).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

