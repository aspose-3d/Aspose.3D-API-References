---
title: BooleanOperand
second_title: Referensi API Aspose.3D untuk Java
description: Kelas ini membungkus mesh yang ditransformasi sebagai operand operasi Boolean.
type: docs
weight: 22
url: /id/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

Kelas ini mengenkapsulasi mesh yang telah ditransformasi sebagai operand operasi Boolean.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | Mendapatkan operand, yang dapat berupa instance dari [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) atau [Node](../../com.aspose.threed/node). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | Buat sebuah instance [BooleanOperand](../../com.aspose.threed/booleanoperand) dari sebuah instance [IMeshConvertible](../../com.aspose.threed/imeshconvertible) yang kosong. |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | Buat sebuah instance [BooleanOperand](../../com.aspose.threed/booleanoperand) dari sebuah instance [IMeshConvertible](../../com.aspose.threed/imeshconvertible) dan transformasi yang ditentukan. |
| [of(Node node)](#of-com.aspose.threed.Node-) | Buat sebuah instance [BooleanOperand](../../com.aspose.threed/booleanoperand) dari sebuah node, diperlukan entitas yang valid yang mengimplementasikan [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |
| [toString()](#toString--) | Mendapatkan representasi string dari [BooleanOperand](../../com.aspose.threed/booleanoperand) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mendapatkan operand, yang dapat berupa instance dari [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) atau [Node](../../com.aspose.threed/node).

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


Buat sebuah instance [BooleanOperand](../../com.aspose.threed/booleanoperand) dari sebuah instance [IMeshConvertible](../../com.aspose.threed/imeshconvertible) yang kosong.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Mesh yang digunakan sebagai operand operasi Boolean, dapat berupa instance dari [IMeshConvertible](../../com.aspose.threed/imeshconvertible) atau [HalfSpace](../../com.aspose.threed/halfspace). |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


Buat sebuah instance [BooleanOperand](../../com.aspose.threed/booleanoperand) dari sebuah instance [IMeshConvertible](../../com.aspose.threed/imeshconvertible) dan transformasi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Mesh yang digunakan sebagai operand operasi Boolean, dapat berupa instance dari [IMeshConvertible](../../com.aspose.threed/imeshconvertible) atau [HalfSpace](../../com.aspose.threed/halfspace). |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | Transformasi dari objek mesh. |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


Buat sebuah instance [BooleanOperand](../../com.aspose.threed/booleanoperand) dari sebuah node, diperlukan entitas yang valid yang mengimplementasikan [IMeshConvertible](../../com.aspose.threed/imeshconvertible).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Sebuah instance [Node](../../com.aspose.threed/node) dengan entitas yang valid yang mengimplementasikan [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


Mendapatkan representasi string dari [BooleanOperand](../../com.aspose.threed/booleanoperand)

**Returns:**
java.lang.String - Representasi string dari [BooleanOperand](../../com.aspose.threed/booleanoperand)
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

