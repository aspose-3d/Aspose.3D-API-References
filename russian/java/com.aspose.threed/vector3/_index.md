---
title: Vector3
second_title: Справочник API Aspose.3D для Java
description: Вектор с тремя компонентами.
type: docs
weight: 202
url: /ru/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

Вектор с тремя компонентами.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | Инициализирует новый экземпляр структуры [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | Инициализирует новый экземпляр структуры [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(double v)](#Vector3-double-) | Инициализирует новый экземпляр структуры [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | Инициализирует новый экземпляр структуры [Vector3](../../com.aspose.threed/vector3). |
| [Vector3()](#Vector3--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [x](#x) | Компонент x. |
| [y](#y) | Компонент y. |
| [z](#z) | Компонент z. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Перегрузка оператора для + |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | Вычислить внутренний угол между двумя направлениями. Два направления могут быть ненормализованными векторами. |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Вычислить внутренний угол между двумя направлениями. Два направления могут быть ненормализованными векторами. |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | Сравнить текущий вектор с другим экземпляром. |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | Вычисляет косинус для каждой компоненты. |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | Явный оператор преобразования для приведения Vector3 к FVector3. |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | Векторное произведение двух векторов. |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Перегрузка оператора для /. |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | Перегрузка оператора для /. |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | Получает скалярное произведение двух векторов. |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверить, равны ли два vector3. |
| [get(int idx)](#get-int-) | Получает компонент вектора по индексу. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Получает длину этого вектора. |
| [getLength2()](#getLength2--) | Получает квадрат длины. |
| [getOne()](#getOne--) | Получает единичный вектор (1, 1, 1). |
| [getUnitX()](#getUnitX--) | Получает единичный вектор (1, 0, 0). |
| [getUnitY()](#getUnitY--) | Получает единичный вектор (0, 1, 0). |
| [getUnitZ()](#getUnitZ--) | Получает единичный вектор (0, 0, 1). |
| [getZero()](#getZero--) | Получает единичный вектор (0, 0, 0). |
| [hashCode()](#hashCode--) | Получает хеш-код Vector3. |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Перегрузка оператора для \* |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | Перегрузка оператора для \* |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | Перегрузка оператора для \* |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | Перегрузка оператора для - |
| [normalize()](#normalize--) | Нормализует этот экземпляр. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Оператор равенства для Vector3 |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Оператор неравенства для Vector3 |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Устанавливает компоненты x/y/z за один вызов. |
| [set(int idx, double value)](#set-int-double-) | Устанавливает компонент вектора по индексу. |
| [sin()](#sin--) | Вычисляет синус для каждого компонента |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Перегрузка оператора для - (минус) |
| [toString()](#toString--) | Возвращает java.lang.String, представляющий текущий [Vector3](../../com.aspose.threed/vector3). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


Инициализирует новый экземпляр структуры [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | double | Координата x. |
| y | double | Координата y. |
| z | double | Координата z. |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


Инициализирует новый экземпляр структуры [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | Координата x. |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


Инициализирует новый экземпляр структуры [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


Инициализирует новый экземпляр структуры [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vec4 | [Vector4](../../com.aspose.threed/vector4) | Vec4. |

### Vector3() {#Vector3--}
```
public Vector3()
```


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

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


Перегрузка оператора для +

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Левый вектор |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Правый вектор |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


Вычислить внутренний угол между двумя направлениями. Два направления могут быть ненормализованными векторами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | Вектор направления для сравнения |

**Returns:**
double — внутренний угол в радианах
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


Вычислить внутренний угол между двумя направлениями. Два направления могут быть ненормализованными векторами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | Вектор направления для сравнения |
| up | [Vector3](../../com.aspose.threed/vector3) | Вектор вверх общей плоскости двух направлений |

**Returns:**
double — внутренний угол в радианах
### clone() {#clone--}
```
public Vector3 clone()
```


Клонировать текущий экземпляр

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


Сравнить текущий вектор с другим экземпляром.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


Вычисляет косинус для каждой компоненты.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


Явный оператор преобразования для приведения Vector3 к FVector3.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


Векторное произведение двух векторов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Значение правой части. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


Перегрузка оператора для /.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Левый вектор |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Правый вектор |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


Перегрузка оператора для /.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Левый вектор |
| rhs | double | Правое двойное значение |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


Получает скалярное произведение двух векторов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Значение правой части. |

**Returns:**
double - Скалярное произведение двух векторов.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверить, равны ли два vector3.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для проверки равенства. |

**Returns:**
boolean - true, если все компоненты идентично равны.
### get(int idx) {#get-int-}
```
public double get(int idx)
```


Получает компонент вектора по индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - компонент вектора по индексу.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public double getLength()
```


Получает длину этого вектора.

**Returns:**
double - длина этого вектора.
### getLength2() {#getLength2--}
```
public double getLength2()
```


Получает квадрат длины.

**Returns:**
double - квадрат длины.
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


Получает единичный вектор (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


Получает единичный вектор (1, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


Получает единичный вектор (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


Получает единичный вектор (0, 0, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


Получает единичный вектор (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш-код Vector3.

**Returns:**
int - Хеш-код [Vector3](../../com.aspose.threed/vector3)
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


Перегрузка оператора для \*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Левый вектор |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Правый вектор |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


Перегрузка оператора для \*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Левый вектор |
| rhs | double | Правое двойное значение |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


Перегрузка оператора для \*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | double | Левый скаляр |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Правый вектор |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


Перегрузка оператора для -

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Вектор начала координат |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


Нормализует этот экземпляр.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector3 lhs, Vector3 rhs) {#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_eq(Vector3 lhs, Vector3 rhs)
```


Оператор равенства для Vector3

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Значение левой части. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Значение правой части. |

**Returns:**
boolean - true, если все компоненты идентично равны.
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Оператор неравенства для Vector3

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Значение левой части. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Значение правой части. |

**Returns:**
boolean - true, если два вектора не равны.
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Устанавливает компоненты x/y/z за один вызов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newX | double | Компонент x. |
| newY | double | Компонент y. |
| newZ | double | Компонент z. |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


Устанавливает компонент вектора по индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| idx | int |  |
| значение | double | Новое значение |

### sin() {#sin--}
```
public Vector3 sin()
```


Вычисляет синус для каждого компонента

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


Перегрузка оператора для - (минус)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Левый вектор |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Правый вектор |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


Возвращает java.lang.String, представляющий текущий [Vector3](../../com.aspose.threed/vector3).

**Returns:**
java.lang.String - java.lang.String, представляющий текущий [Vector3](../../com.aspose.threed/vector3).
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

