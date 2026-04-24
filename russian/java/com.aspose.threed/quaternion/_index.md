---
title: Quaternion
second_title: Справочник API Aspose.3D для Java
description: Кватернион обычно используется для выполнения вращения в компьютерной графике.
type: docs
weight: 143
url: /ru/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

Кватернион обычно используется для выполнения вращения в компьютерной графике.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | Инициализирует новый экземпляр класса [Quaternion](../../com.aspose.threed/quaternion). |
| [Quaternion()](#Quaternion--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [IDENTITY](#IDENTITY) | Единичный кватернион. |
| [w](#w) | Компонент w. |
| [x](#x) | Компонент x. |
| [y](#y) | Компонент y. |
| [z](#z) | Компонент z. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Перегрузка оператора для + |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | Конкатенировать два кватерниона. |
| [conjugate()](#conjugate--) | Возвращает сопряжённый кватернион текущего кватерниона. |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | Перегрузка оператора для /. |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | Скалярное произведение. |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверить, равны ли два кватерниона. |
| [eulerAngles()](#eulerAngles--) | Преобразует кватернион в вращение, представленное углами Эйлера. Все компоненты указаны в радианах. |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | Создаёт кватернион вокруг заданной оси и вращает по часовой стрелке. |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | Создаёт кватернион из заданного угла Эйлера. |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | Создаёт кватернион из заданного угла Эйлера. |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Создаёт кватернион, вращающий из исходного направления в целевое. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Получает длину кватерниона. |
| [hashCode()](#hashCode--) | Получает хеш‑код кватерниона. |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Заполняет этот кватернион интерполированным значением между заданными аргументами кватернионов для параметра t в диапазоне от начального к конечному. |
| [inverse()](#inverse--) | Возвращает обратный кватернион текущего кватерниона. |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Перегрузка оператора для \* |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | Перегрузка оператора для \* |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | Перегрузка оператора для \* |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | Перегрузка оператора для \* |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | Перегрузка оператора для \* |
| [normalize()](#normalize--) | Нормализовать кватернион. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Оператор равенства для кватерниона. |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Оператор неравенства для кватерниона. |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Выполнить сферическую линейную интерполяцию между двумя значениями. |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | Разложить кватернион на угол и ось. |
| [toMatrix()](#toMatrix--) | Преобразовать вращение, представленное кватернионом, в матрицу преобразования. |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | Преобразовать вращение, представленное кватернионом, в матрицу преобразования. |
| [toString()](#toString--) | Получает строковое представление кватерниона. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


Инициализирует новый экземпляр класса [Quaternion](../../com.aspose.threed/quaternion).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| w | double | w component of the quaternion |
| x | double | x component of the quaternion |
| y | double | y component of the quaternion |
| z | double | z component of the quaternion |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


Единичный кватернион.

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

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


Перегрузка оператора для +

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left quaternion |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


Клонировать текущий экземпляр

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


Конкатенировать два кватерниона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


Возвращает сопряжённый кватернион текущего кватерниона.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


Перегрузка оператора для /.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left quaternion |
| rhs | double | Right quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


Скалярное произведение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | The quaternion |

**Returns:**
double - Dot value
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверить, равны ли два кватерниона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для проверки равенства. |

**Returns:**
boolean - true, если все компоненты идентично равны.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


Преобразует кватернион в вращение, представленное углами Эйлера. Все компоненты указаны в радианах.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


Создаёт кватернион вокруг заданной оси и вращает по часовой стрелке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | double | Clockwise rotation in radian |
| axis | [Vector3](../../com.aspose.threed/vector3) | Axis |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


Создаёт кватернион из заданного угла Эйлера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | Euler angle in radian |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


Создаёт кватернион из заданного угла Эйлера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pitch | double | Pitch in radian |
| yaw | double | Yaw in radian |
| roll | double | Roll in radian |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


Создаёт кватернион, вращающий из исходного направления в целевое.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | Original direction |
| dest | [Vector3](../../com.aspose.threed/vector3) | Destination direction |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
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


Получает длину кватерниона.

**Returns:**
double - the length of the quaternion
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш‑код кватерниона.

**Returns:**
int - The hash code of the [Quaternion](../../com.aspose.threed/quaternion)
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


Заполняет этот кватернион интерполированным значением между заданными аргументами кватернионов для параметра t в диапазоне от начального к конечному.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| t | float | The coefficient to interpolate. |
| from | [Quaternion](../../com.aspose.threed/quaternion) | Source quaternion. |
| to | [Quaternion](../../com.aspose.threed/quaternion) | Target quaternion. |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


Возвращает обратный кватернион текущего кватерниона.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


Перегрузка оператора для \*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left quaternion |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


Перегрузка оператора для \*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | The rotation quaternion |
| v | [Vector3](../../com.aspose.threed/vector3) | Вектор для вращения |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


Перегрузка оператора для \*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | The rotation quaternion |
| v | [Vector4](../../com.aspose.threed/vector4) | Вектор для вращения |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


Перегрузка оператора для \*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left quaternion |
| rhs | double | Right quaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


Перегрузка оператора для \*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | The rotation quaternion |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Вектор для вращения |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


Нормализовать кватернион.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Normalized quaternion.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Quaternion lhs, Quaternion rhs) {#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_eq(Quaternion lhs, Quaternion rhs)
```


Оператор равенства для кватерниона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Значение левой части. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Значение правой части. |

**Returns:**
boolean - true, если все компоненты идентично равны.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


Оператор неравенства для кватерниона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Значение левой части. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Значение правой части. |

**Returns:**
boolean - True, если два кватерниона не равны.
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


Выполнить сферическую линейную интерполяцию между двумя значениями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| t | double | t находится в диапазоне от 0 до 1 |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | Первое значение |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | Второе значение |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


Разложить кватернион на угол и ось.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | double[] | Угол вращения, в радианах. |
| axis | [Vector3](../../com.aspose.threed/vector3) | Ось, вокруг которой происходит вращение. |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


Преобразовать вращение, представленное кватернионом, в матрицу преобразования.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


Преобразовать вращение, представленное кватернионом, в матрицу преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | Часть матрицы, отвечающая за трансляцию. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


Получает строковое представление кватерниона.

**Returns:**
java.lang.String - Строка объекта
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

