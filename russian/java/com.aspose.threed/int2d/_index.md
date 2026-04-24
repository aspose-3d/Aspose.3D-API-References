---
title: Int2D
second_title: Справочник API Aspose.3D для Java
description: Создано пользователем lexchou 17.05.2017.
type: docs
weight: 86
url: /ru/java/com.aspose.threed/int2d/
---

**Inheritance:**
java.lang.Object
```
public final class Int2D
```

Создано пользователем lexchou 5/17/2017. Обёртка двумерного массива int
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Int2D(int rows, int columns)](#Int2D-int-int-) | Создать двумерный массив int с выделением данных по умолчанию. |
| [Int2D(int rows, int columns, int[] data)](#Int2D-int-int-int---) | Создать двумерный массив int с заданными данными |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int r, int c)](#get-int-int-) | Получает элемент в указанной позиции |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) |  |
| [getLength(int rank)](#getLength-int-) |  |
| [getRows()](#getRows--) |  |
| [hashCode()](#hashCode--) |  |
| [length()](#length--) | Получает общую длину этого двумерного массива |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(int r, int c, int v)](#set-int-int-int-) | Устанавливает элемент в указанной позиции |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Int2D(int rows, int columns) {#Int2D-int-int-}
```
public Int2D(int rows, int columns)
```


Создать двумерный массив int с выделением данных по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| строки | int | Количество строк двумерного массива |
| столбцы | int | Количество столбцов двумерного массива |

### Int2D(int rows, int columns, int[] data) {#Int2D-int-int-int---}
```
public Int2D(int rows, int columns, int[] data)
```


Создать двумерный массив int с заданными данными

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| строки | int | Количество строк двумерного массива |
| столбцы | int | Количество столбцов двумерного массива |
| данные | int[] | Массив для обёртки, Float2D будет использовать этот массив внутренне. |

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
### get(int r, int c) {#get-int-int-}
```
public int get(int r, int c)
```


Получает элемент в указанной позиции

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| r | int | Строка |
| c | int | Столбец |

**Returns:**
int — значение в указанной позиции
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public int getColumns()
```




**Returns:**
int
### getLength(int rank) {#getLength-int-}
```
public int getLength(int rank)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ранг | int |  |

**Returns:**
int
### getRows() {#getRows--}
```
public int getRows()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### length() {#length--}
```
public int length()
```


Получает общую длину этого двумерного массива

**Returns:**
int — общее количество чисел с плавающей точкой в этом двумерном массиве.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(int r, int c, int v) {#set-int-int-int-}
```
public void set(int r, int c, int v)
```


Устанавливает элемент в указанной позиции

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| r | int | Строка |
| c | int | Столбец |
| v | int | Значение |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

