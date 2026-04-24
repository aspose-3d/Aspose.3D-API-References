---
title: Vector4
second_title: Справочник API Aspose.3D для Java
description: Вектор с четырьмя компонентами.
type: docs
weight: 203
url: /ru/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

Вектор с четырьмя компонентами.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | Инициализирует новый экземпляр структуры [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | Инициализирует новый экземпляр структуры [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | Инициализирует новый экземпляр структуры [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | Инициализирует новый экземпляр структуры [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | Инициализирует новый экземпляр структуры [Vector4](../../com.aspose.threed/vector4). |
| [Vector4()](#Vector4--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [w](#w) | Компонент w. |
| [x](#x) | Компонент x. |
| [y](#y) | Компонент y. |
| [z](#z) | Компонент z. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Перегрузка оператора для + |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | Сравнить текущий вектор с другим экземпляром. |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | Явный оператор преобразования для приведения Vector4 к FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверить, равны ли два вектора |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Получает хеш-код этого вектора. |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Перегрузка оператора для \* |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | Перегрузка оператора для \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Устанавливает компоненты xyz вектора одновременно, w будет установлен в 1. |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | Устанавливает все компоненты вектора одновременно. |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Перегрузка оператора для - (минус) |
| [toString()](#toString--) | Возвращает java.lang.String, представляющий текущий [Vector4](../../com.aspose.threed/vector4). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


Инициализирует новый экземпляр структуры [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Вектор. |
| w | double | Ширина. |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


Инициализирует новый экземпляр структуры [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Вектор. |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


Инициализирует новый экземпляр структуры [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | Вектор. |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


Инициализирует новый экземпляр структуры [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | double | Координата x. |
| y | double | Координата y. |
| z | double | Координата z. |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


Инициализирует новый экземпляр структуры [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | double | Координата x. |
| y | double | Координата y. |
| z | double | Координата z. |
| w | double | Ширина. |

### Vector4() {#Vector4--}
```
public Vector4()
```


### w {#w}
```
public double w
```


Компонент w.

### x {#x}
```
public double x
```


Компонент x.

### y {#y}
```
public double y
```


Компонент y.

### z {#z}
```
public double z
```


Компонент z.

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


Перегрузка оператора для +

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | Левый вектор |
| rhs | [Vector4](../../com.aspose.threed/vector4) | Правый вектор |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


Клонировать текущий экземпляр

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


Сравнить текущий вектор с другим экземпляром.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


Явный оператор преобразования для приведения Vector4 к FVector4

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверить, равны ли два вектора

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш-код этого вектора.

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


Перегрузка оператора для \*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | Левый вектор |
| rhs | [Vector4](../../com.aspose.threed/vector4) | Правый вектор |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


Перегрузка оператора для \*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | Левый вектор |
| rhs | double | Правое двойное значение |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Устанавливает компоненты xyz вектора одновременно, w будет установлен в 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newX | double | Новый компонент X. |
| newY | double | Новый компонент Y. |
| newZ | double | Новый компонент Z. |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


Устанавливает все компоненты вектора одновременно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newX | double | Новый компонент X. |
| newY | double | Новый компонент Y. |
| newZ | double | Новый компонент Z. |
| newW | double | Новый компонент W. |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


Перегрузка оператора для - (минус)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | Левый вектор |
| rhs | [Vector4](../../com.aspose.threed/vector4) | Правый вектор |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Возвращает java.lang.String, представляющий текущий [Vector4](../../com.aspose.threed/vector4).

**Returns:**
java.lang.String - java.lang.String, представляющий текущий [Vector4](../../com.aspose.threed/vector4).
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

