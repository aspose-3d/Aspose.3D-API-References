---
title: BooleanOperand
second_title: Referencia de API de Aspose.3D para Java
description: Esta clase encapsula la malla transformada como operando de operaciones Booleanas.
type: docs
weight: 22
url: /es/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

Esta clase encapsula la malla transformada como operando de la operación Booleana.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | Obtiene el operando, que puede ser una instancia de [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) o [Node](../../com.aspose.threed/node). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | Construya una instancia de [BooleanOperand](../../com.aspose.threed/booleanoperand) a partir de una instancia sin procesar de [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | Construya una instancia de [BooleanOperand](../../com.aspose.threed/booleanoperand) a partir de una instancia de [IMeshConvertible](../../com.aspose.threed/imeshconvertible) y la transformación especificada. |
| [of(Node node)](#of-com.aspose.threed.Node-) | Construya una instancia de [BooleanOperand](../../com.aspose.threed/booleanoperand) a partir de un nodo; se requiere una entidad válida que implemente [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |
| [toString()](#toString--) | Obtiene la representación en cadena de [BooleanOperand](../../com.aspose.threed/booleanoperand). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene el operando, que puede ser una instancia de [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) o [Node](../../com.aspose.threed/node).

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


Construya una instancia de [BooleanOperand](../../com.aspose.threed/booleanoperand) a partir de una instancia sin procesar de [IMeshConvertible](../../com.aspose.threed/imeshconvertible).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | La malla utilizada como operando de la operación Booleana, puede ser una instancia de [IMeshConvertible](../../com.aspose.threed/imeshconvertible) o [HalfSpace](../../com.aspose.threed/halfspace). |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


Construya una instancia de [BooleanOperand](../../com.aspose.threed/booleanoperand) a partir de una instancia de [IMeshConvertible](../../com.aspose.threed/imeshconvertible) y la transformación especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | La malla utilizada como operando de la operación Booleana, puede ser una instancia de [IMeshConvertible](../../com.aspose.threed/imeshconvertible) o [HalfSpace](../../com.aspose.threed/halfspace). |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | La transformación del objeto malla. |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


Construya una instancia de [BooleanOperand](../../com.aspose.threed/booleanoperand) a partir de un nodo; se requiere una entidad válida que implemente [IMeshConvertible](../../com.aspose.threed/imeshconvertible).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Una instancia de [Node](../../com.aspose.threed/node) con una entidad válida que implemente [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


Obtiene la representación en cadena de [BooleanOperand](../../com.aspose.threed/booleanoperand).

**Returns:**
java.lang.String - La representación en cadena de [BooleanOperand](../../com.aspose.threed/booleanoperand).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

