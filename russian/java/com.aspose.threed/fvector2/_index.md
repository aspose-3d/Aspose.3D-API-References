---
title: FVector2
second_title: Справочник API Aspose.3D для Java
description: Вектор float с двумя компонентами.
type: docs
weight: 59
url: /ru/java/com.aspose.threed/fvector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector2 implements Struct<FVector2>, Serializable
```

Вектор float с двумя компонентами.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FVector2(float x, float y)](#FVector2-float-float-) | Инициализирует новый экземпляр [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2(Vector2 vec)](#FVector2-com.aspose.threed.Vector2-) | Инициализирует новый экземпляр [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2()](#FVector2--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [x](#x) | Компонент x. |
| [y](#y) | Компонент y. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(FVector2 a, FVector2 b)](#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \+ Перегрузка оператора |
| [clone()](#clone--) |  |
| [copyFrom(FVector2 src)](#copyFrom-com.aspose.threed.FVector2-) |  |
| [create(FVector2 v)](#create-com.aspose.threed.FVector2-) | Явный оператор преобразования для приведения FVector2 к Vector2 |
| [equals(FVector2 rhs)](#equals-com.aspose.threed.FVector2-) | Проверить, равны ли два вектора |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверить, равны ли два вектора |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Получает хеш-код этого экземпляра |
| [mul(FVector2 a, float b)](#mul-com.aspose.threed.FVector2-float-) | \* Перегрузка оператора |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(FVector2 a, FVector2 b)](#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | == Перегрузка оператора |
| [op_ne(FVector2 a, FVector2 b)](#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | != Перегрузка оператора |
| [sub(FVector2 a, FVector2 b)](#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \- Перегрузка оператора |
| [toString()](#toString--) | Возвращает строку, представляющую [FVector2](../../com.aspose.threed/fvector2) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector2(float x, float y) {#FVector2-float-float-}
```
public FVector2(float x, float y)
```


Инициализирует новый экземпляр [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | X компонент вектора |
| y | float | Y компонент вектора |

### FVector2(Vector2 vec) {#FVector2-com.aspose.threed.Vector2-}
```
public FVector2(Vector2 vec)
```


Инициализирует новый экземпляр [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vec | [Vector2](../../com.aspose.threed/vector2) | Vector2 в типе double |

### FVector2() {#FVector2--}
```
public FVector2()
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

### add(FVector2 a, FVector2 b) {#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 add(FVector2 a, FVector2 b)
```


\+ Перегрузка оператора

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Первый вектор |
| b | [FVector2](../../com.aspose.threed/fvector2) | Второй вектор |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The sum of two vectors.
### clone() {#clone--}
```
public FVector2 clone()
```


Клонировать текущий экземпляр

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### copyFrom(FVector2 src) {#copyFrom-com.aspose.threed.FVector2-}
```
public void copyFrom(FVector2 src)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [FVector2](../../com.aspose.threed/fvector2) |  |

### create(FVector2 v) {#create-com.aspose.threed.FVector2-}
```
public static Vector2 create(FVector2 v)
```


Явный оператор преобразования для приведения FVector2 к Vector2

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| v | [FVector2](../../com.aspose.threed/fvector2) | Vector 2 в типе float. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### equals(FVector2 rhs) {#equals-com.aspose.threed.FVector2-}
```
public boolean equals(FVector2 rhs)
```


Проверить, равны ли два вектора

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rhs | [FVector2](../../com.aspose.threed/fvector2) |  |

**Returns:**
boolean - True, если все компоненты равны.
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
boolean - True, если входные данные являются вектором и все компоненты равны.
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


Получает хеш-код этого экземпляра

**Returns:**
int - Хеш-код вектора.
### mul(FVector2 a, float b) {#mul-com.aspose.threed.FVector2-float-}
```
public static FVector2 mul(FVector2 a, float b)
```


\* Перегрузка оператора

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Первый вектор |
| b | float | Второй вектор |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The product of two vectors.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(FVector2 a, FVector2 b) {#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_eq(FVector2 a, FVector2 b)
```


== Перегрузка оператора

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Первый вектор |
| b | [FVector2](../../com.aspose.threed/fvector2) | Второй вектор |

**Returns:**
boolean - True, если все компоненты равны.
### op_ne(FVector2 a, FVector2 b) {#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_ne(FVector2 a, FVector2 b)
```


!= Operator overloading

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Первый вектор |
| b | [FVector2](../../com.aspose.threed/fvector2) | Второй вектор |

**Returns:**
boolean - True, если какой‑либо компонент отличается.
### sub(FVector2 a, FVector2 b) {#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 sub(FVector2 a, FVector2 b)
```


\- Перегрузка оператора

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Первый вектор |
| b | [FVector2](../../com.aspose.threed/fvector2) | Второй вектор |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The difference of two vectors.
### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую [FVector2](../../com.aspose.threed/fvector2)

**Returns:**
java.lang.String - Строковое представление текущего вектора.
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

