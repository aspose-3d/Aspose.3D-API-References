---
title: "BooleanOperand"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Cette classe encapsule le maillage transformé en tant qu'opérande d'opérations booléennes."
type: docs
weight: 22
url: /fr/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

Cette classe encapsule le maillage transformé comme opérande d'une opération booléenne.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | Obtient l'opérande, qui peut être une instance de [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) ou [Node](../../com.aspose.threed/node). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | Construisez une instance de [BooleanOperand](../../com.aspose.threed/booleanoperand) à partir d'une instance brute de [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | Construisez une instance de [BooleanOperand](../../com.aspose.threed/booleanoperand) à partir d'une instance de [IMeshConvertible](../../com.aspose.threed/imeshconvertible) et d'une transformation spécifiée. |
| [of(Node node)](#of-com.aspose.threed.Node-) | Construisez une instance de [BooleanOperand](../../com.aspose.threed/booleanoperand) à partir d'un nœud, une entité valide implémentant [IMeshConvertible](../../com.aspose.threed/imeshconvertible) est requise |
| [toString()](#toString--) | Obtient la représentation sous forme de chaîne de [BooleanOperand](../../com.aspose.threed/booleanoperand) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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


Obtient l'opérande, qui peut être une instance de [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) ou [Node](../../com.aspose.threed/node).

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


Construisez une instance de [BooleanOperand](../../com.aspose.threed/booleanoperand) à partir d'une instance brute de [IMeshConvertible](../../com.aspose.threed/imeshconvertible).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Le maillage utilisé comme opérande de l'opération booléenne, il peut être une instance de [IMeshConvertible](../../com.aspose.threed/imeshconvertible) ou de [HalfSpace](../../com.aspose.threed/halfspace) |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


Construisez une instance de [BooleanOperand](../../com.aspose.threed/booleanoperand) à partir d'une instance de [IMeshConvertible](../../com.aspose.threed/imeshconvertible) et d'une transformation spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Le maillage utilisé comme opérande de l'opération booléenne, il peut être une instance de [IMeshConvertible](../../com.aspose.threed/imeshconvertible) ou de [HalfSpace](../../com.aspose.threed/halfspace) |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | La transformation de l'objet mesh |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


Construisez une instance de [BooleanOperand](../../com.aspose.threed/booleanoperand) à partir d'un nœud, une entité valide implémentant [IMeshConvertible](../../com.aspose.threed/imeshconvertible) est requise

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Une instance de [Node](../../com.aspose.threed/node) avec une entité valide implémentant [IMeshConvertible](../../com.aspose.threed/imeshconvertible) |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


Obtient la représentation sous forme de chaîne de [BooleanOperand](../../com.aspose.threed/booleanoperand)

**Returns:**
java.lang.String - La représentation sous forme de chaîne de [BooleanOperand](../../com.aspose.threed/booleanoperand)
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

