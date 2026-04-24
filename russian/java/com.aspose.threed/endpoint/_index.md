---
title: EndPoint
second_title: Справочник API Aspose.3D для Java
description: Конечная точка для обрезки кривой может быть значением параметра или декартовой точкой.
type: docs
weight: 51
url: /ru/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

Конечная точка для обрезки кривой, может быть значением параметра или декартовой точкой.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | Создать [EndPoint](../../com.aspose.threed/endpoint) из декартовой точки. |
| [EndPoint(double v)](#EndPoint-double-) | Создать [EndPoint](../../com.aspose.threed/endpoint) из реального параметра. |
| [EndPoint()](#EndPoint--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | Создать конечную точку, измеренную в градусах. |
| [fromRadian(double degree)](#fromRadian-double-) | Создать конечную точку, измеренную в радианах. |
| [getAsPoint()](#getAsPoint--) | Получает конечную точку как декартовую точку или бросает исключение. |
| [getAsValue()](#getAsValue--) | Получает конечную точку как реальный параметр или бросает исключение. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | Является ли конечная точка декартовой точкой? |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает строковое представление текущей конечной точки. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


Создать [EndPoint](../../com.aspose.threed/endpoint) из декартовой точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | Точка для построения |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


Создать [EndPoint](../../com.aspose.threed/endpoint) из реального параметра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| v | double | Параметр вещественного числа для построения конечной точки |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


Клонировать текущий экземпляр

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

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
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


Создать конечную точку, измеренную в градусах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| degree | double | Значение в градусах |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


Создать конечную точку, измеренную в радианах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| degree | double | Значение в радианах |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


Получает конечную точку как декартовую точку или бросает исключение.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


Получает конечную точку как реальный параметр или бросает исключение.

**Returns:**
double — конечная точка как реальный параметр или бросает исключение.
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




**Returns:**
int
### isCartesianPoint() {#isCartesianPoint--}
```
public boolean isCartesianPoint()
```


Является ли конечная точка декартовой точкой?

**Returns:**
boolean — является ли конечная точка декартовой точкой?
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Возвращает строковое представление текущей конечной точки.

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

