---
title: "BooleanOperand"
second_title: "Aspose.3D for Java API Referansı"
description: "Bu sınıf, dönüştürülmüş ağı Boolean işlemlerinin operandı olarak kapsüller."
type: docs
weight: 22
url: /tr/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

Bu sınıf, dönüştürülmüş ağı, Boolean işleminin operandı olarak kapsüller.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | Operandı alır, bir [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) veya [Node](../../com.aspose.threed/node) örneği olabilir. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | Boş bir [IMeshConvertible](../../com.aspose.threed/imeshconvertible) örneğinden bir [BooleanOperand](../../com.aspose.threed/booleanoperand) örneği oluşturun. |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | [IMeshConvertible](../../com.aspose.threed/imeshconvertible) örneğinden ve belirtilen dönüşümden bir [BooleanOperand](../../com.aspose.threed/booleanoperand) örneği oluşturun. |
| [of(Node node)](#of-com.aspose.threed.Node-) | Bir düğümden bir [BooleanOperand](../../com.aspose.threed/booleanoperand) örneği oluşturun, geçerli bir [IMeshConvertible](../../com.aspose.threed/imeshconvertible) uygulanmış varlık gereklidir. |
| [toString()](#toString--) | [BooleanOperand](../../com.aspose.threed/booleanoperand) nesnesinin dize temsilini alır. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Operandı alır, bir [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) veya [Node](../../com.aspose.threed/node) örneği olabilir.

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


Boş bir [IMeshConvertible](../../com.aspose.threed/imeshconvertible) örneğinden bir [BooleanOperand](../../com.aspose.threed/booleanoperand) örneği oluşturun.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Boolean işleminin operandı olarak kullanılan ağ, [IMeshConvertible](../../com.aspose.threed/imeshconvertible) veya [HalfSpace](../../com.aspose.threed/halfspace) örneği olabilir. |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


[IMeshConvertible](../../com.aspose.threed/imeshconvertible) örneğinden ve belirtilen dönüşümden bir [BooleanOperand](../../com.aspose.threed/booleanoperand) örneği oluşturun.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Boolean işleminin operandı olarak kullanılan ağ, [IMeshConvertible](../../com.aspose.threed/imeshconvertible) veya [HalfSpace](../../com.aspose.threed/halfspace) örneği olabilir. |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | Ağ nesnesinin dönüşümü |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


Bir düğümden bir [BooleanOperand](../../com.aspose.threed/booleanoperand) örneği oluşturun, geçerli bir [IMeshConvertible](../../com.aspose.threed/imeshconvertible) uygulanmış varlık gereklidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Geçerli bir [IMeshConvertible](../../com.aspose.threed/imeshconvertible) uygulanmış varlık içeren bir [Node](../../com.aspose.threed/node) örneği. |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


[BooleanOperand](../../com.aspose.threed/booleanoperand) nesnesinin dize temsilini alır.

**Returns:**
java.lang.String - [BooleanOperand](../../com.aspose.threed/booleanoperand) nesnesinin dize temsili
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

