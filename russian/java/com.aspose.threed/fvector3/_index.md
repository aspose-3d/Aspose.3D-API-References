---
title: FVector3
second_title: Справочник API Aspose.3D для Java
description: Вектор float с тремя компонентами.
type: docs
weight: 60
url: /ru/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

Вектор float с тремя компонентами.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | Инициализирует новый экземпляр [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | Инициализирует новый экземпляр [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | Инициализирует новый экземпляр [FVector4](../../com.aspose.threed/fvector4). |
| [FVector3()](#FVector3--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [x](#x) | Компонент x. |
| [y](#y) | Компонент y. |
| [z](#z) | Компонент y. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \+ Перегрузка оператора |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | Явный оператор преобразования для приведения FVector3 к Vector3 |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | Векторное произведение двух векторов. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | Вектор единичного масштаба, все компоненты которого равны 1 |
| [getZero()](#getZero--) | Вектор нуля. |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* Перегрузка операторов |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | \- Перегрузка оператора |
| [normalize()](#normalize--) | Нормализует этот экземпляр. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \- Перегрузка оператора |
| [toString()](#toString--) | Возвращает строку, представляющую [FVector3](../../com.aspose.threed/fvector3) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


Инициализирует новый экземпляр [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | X компонент вектора |
| y | float | Y компонент вектора |
| z | float | Z‑компонент вектора |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


Инициализирует новый экземпляр [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vector3 в типе double |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


Инициализирует новый экземпляр [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | Vector4 в типе double |

### FVector3() {#FVector3--}
```
public FVector3()
```


### x {#x}
```
public float x
```


Компонент x.

### y {#y}
```
public float y
```


Компонент y.

### z {#z}
```
public float z
```


Компонент y.

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


\+ Перегрузка оператора

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Первый вектор |
| b | [FVector3](../../com.aspose.threed/fvector3) | Второй вектор |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


Клонировать текущий экземпляр

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


Явный оператор преобразования для приведения FVector3 к Vector3

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | Vector3 в типе float |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


Векторное произведение двух векторов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | Значение правой части. |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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
### getOne() {#getOne--}
```
public static FVector3 getOne()
```


Вектор единичного масштаба, все компоненты которого равны 1

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


Вектор нуля.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The Zero vector.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### mul(FVector3 a, float b) {#mul-com.aspose.threed.FVector3-float-}
```
public static FVector3 mul(FVector3 a, float b)
```


\* Перегрузка операторов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Первый вектор |
| b | float | Второй вектор |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


\- Перегрузка оператора

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Входной вектор |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


Нормализует этот экземпляр.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector3 a, FVector3 b) {#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 sub(FVector3 a, FVector3 b)
```


\- Перегрузка оператора

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Первый вектор |
| b | [FVector3](../../com.aspose.threed/fvector3) | Второй вектор |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую [FVector3](../../com.aspose.threed/fvector3)

**Returns:**
java.lang.String — строковое представление этого вектора.
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

