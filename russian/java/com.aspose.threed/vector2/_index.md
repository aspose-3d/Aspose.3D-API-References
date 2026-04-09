---
title: Vector2
second_title: Справочник API Aspose.3D для Java
description: Вектор с двумя компонентами.
type: docs
weight: 201
url: /ru/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

Вектор с двумя компонентами.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | Инициализирует новый экземпляр структуры [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | Инициализирует новый экземпляр структуры [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | Инициализирует новый экземпляр структуры [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(double x, double y)](#Vector2-double-double-) | Инициализирует новый экземпляр структуры [Vector2](../../com.aspose.threed/vector2). |
| [Vector2()](#Vector2--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [x](#x) | Компонент x. |
| [y](#y) | Компонент y. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Оператор сложения для Vector2 |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | Сравнить текущий вектор с другим экземпляром. |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | Оператор явного преобразования для приведения Vector2 к FVector2 |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | Векторное произведение двух векторов. |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Оператор деления для Vector2 |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | Получает скалярное произведение двух векторов. |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | Проверить, равны ли два vector2 |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверить, равны ли два vector2 |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Получает длину. |
| [getU()](#getU--) | Получает компонент U, если [Vector2](../../com.aspose.threed/vector2) используется как координата отображения. |
| [getV()](#getV--) | Получает компонент V, если [Vector2](../../com.aspose.threed/vector2) используется как координата отображения. |
| [hashCode()](#hashCode--) | Получает хеш‑код Vector2 |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Оператор умножения для Vector2 |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Оператор умножения для Vector2 |
| [normalize()](#normalize--) | Нормализует этот экземпляр. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Оператор равенства для Vector2 |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Оператор неравенства для Vector2 |
| [setU(double value)](#setU-double-) | Устанавливает компонент U, если [Vector2](../../com.aspose.threed/vector2) используется в качестве координаты отображения. |
| [setV(double value)](#setV-double-) | Устанавливает компонент V, если [Vector2](../../com.aspose.threed/vector2) используется в качестве координаты отображения. |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Оператор вычитания для Vector2 |
| [toString()](#toString--) | Возвращает java.lang.String, представляющий текущий [Vector2](../../com.aspose.threed/vector2). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


Инициализирует новый экземпляр структуры [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


Инициализирует новый экземпляр структуры [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


Инициализирует новый экземпляр структуры [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | Вектор в типе float. |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


Инициализирует новый экземпляр структуры [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | double | Координата x. |
| y | double | Координата y. |

### Vector2() {#Vector2--}
```
public Vector2()
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

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Оператор сложения для Vector2

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Значение левой части. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Значение правой части. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


Клонировать текущий экземпляр

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


Сравнить текущий вектор с другим экземпляром.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


Оператор явного преобразования для приведения Vector2 к FVector2

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


Векторное произведение двух векторов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Оператор деления для Vector2

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Значение левой части. |
| rhs | double | Значение правой части. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


Получает скалярное произведение двух векторов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Значение правой части. |

**Returns:**
double - Скалярное произведение двух векторов.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


Проверить, равны ли два vector2

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Значение правой части. |

**Returns:**
boolean - true, если все компоненты идентично равны.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверить, равны ли два vector2

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения. |

**Returns:**
boolean - true, если все компоненты идентично равны.
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


Получает длину.

**Returns:**
double - длина.
### getU() {#getU--}
```
public double getU()
```


Получает компонент U, если [Vector2](../../com.aspose.threed/vector2) используется в качестве координаты отображения. Это псевдоним компонента x.

**Returns:**
double - компонент U, если [Vector2](../../com.aspose.threed/vector2) используется в качестве координаты отображения. Это псевдоним компонента x.
### getV() {#getV--}
```
public double getV()
```


Получает компонент V, если [Vector2](../../com.aspose.threed/vector2) используется в качестве координаты отображения. Это псевдоним компонента y.

**Returns:**
double - компонент V, если [Vector2](../../com.aspose.threed/vector2) используется в качестве координаты отображения. Это псевдоним компонента y.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш‑код Vector2

**Returns:**
int - Хеш-код [Vector2](../../com.aspose.threed/vector2)
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Оператор умножения для Vector2

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Значение левой части. |
| rhs | double | Значение правой части. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Оператор умножения для Vector2

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | double | Значение левой части. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Значение правой части. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


Нормализует этот экземпляр.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector2 lhs, Vector2 rhs) {#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_eq(Vector2 lhs, Vector2 rhs)
```


Оператор равенства для Vector2

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Значение левой части. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Значение правой части. |

**Returns:**
boolean - true, если все компоненты идентично равны.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Оператор неравенства для Vector2

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Значение левой части. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Значение правой части. |

**Returns:**
boolean - true, если два вектора не равны.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


Устанавливает компонент U, если [Vector2](../../com.aspose.threed/vector2) используется в качестве координаты отображения. Это псевдоним компонента x.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


Устанавливает компонент V, если [Vector2](../../com.aspose.threed/vector2) используется в качестве координаты отображения. Это псевдоним компонента y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Оператор вычитания для Vector2

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Значение левой части. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Значение правой части. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


Возвращает java.lang.String, представляющий текущий [Vector2](../../com.aspose.threed/vector2).

**Returns:**
java.lang.String - java.lang.String, представляющий текущий [Vector2](../../com.aspose.threed/vector2).
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

