---
title: BooleanOperand
second_title: Справочник API Aspose.3D для Java
description: Этот класс инкапсулирует преобразованную сетку как операнд булевых операций.
type: docs
weight: 22
url: /ru/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

Этот класс инкапсулирует преобразованную сетку как операнд булевой операции.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | Получает операнд, он может быть экземпляром [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) или [Node](../../com.aspose.threed/node). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | Создайте экземпляр [BooleanOperand](../../com.aspose.threed/booleanoperand) из голого экземпляра [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | Создайте экземпляр [BooleanOperand](../../com.aspose.threed/booleanoperand) из экземпляра [IMeshConvertible](../../com.aspose.threed/imeshconvertible) и указанного преобразования. |
| [of(Node node)](#of-com.aspose.threed.Node-) | Создайте экземпляр [BooleanOperand](../../com.aspose.threed/booleanoperand) из узла, требуется корректный объект, реализующий [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |
| [toString()](#toString--) | Получает строковое представление [BooleanOperand](../../com.aspose.threed/booleanoperand). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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


Получает операнд, он может быть экземпляром [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) или [Node](../../com.aspose.threed/node).

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


Создайте экземпляр [BooleanOperand](../../com.aspose.threed/booleanoperand) из голого экземпляра [IMeshConvertible](../../com.aspose.threed/imeshconvertible).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Сетка, используемая в качестве операнда булевой операции; она может быть экземпляром [IMeshConvertible](../../com.aspose.threed/imeshconvertible) или [HalfSpace](../../com.aspose.threed/halfspace). |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


Создайте экземпляр [BooleanOperand](../../com.aspose.threed/booleanoperand) из экземпляра [IMeshConvertible](../../com.aspose.threed/imeshconvertible) и указанного преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Сетка, используемая в качестве операнда булевой операции; она может быть экземпляром [IMeshConvertible](../../com.aspose.threed/imeshconvertible) или [HalfSpace](../../com.aspose.threed/halfspace). |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | Преобразование объекта сетки. |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


Создайте экземпляр [BooleanOperand](../../com.aspose.threed/booleanoperand) из узла, требуется корректный объект, реализующий [IMeshConvertible](../../com.aspose.threed/imeshconvertible).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Экземпляр [Node](../../com.aspose.threed/node) с корректным объектом, реализующим [IMeshConvertible](../../com.aspose.threed/imeshconvertible). |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


Получает строковое представление [BooleanOperand](../../com.aspose.threed/booleanoperand).

**Returns:**
java.lang.String — строковое представление [BooleanOperand](../../com.aspose.threed/booleanoperand).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

