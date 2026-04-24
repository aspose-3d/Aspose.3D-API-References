---
title: BoundingBox2D
second_title: Справочник API Aspose.3D для Java
description: Ограничивающий прямоугольник, выровненный по осям для
type: docs
weight: 25
url: /ru/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

Осиально-выравненный ограничивающий прямоугольник для [Vector2](../../com.aspose.threed/vector2)
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Инициализировать конечный ограничивающий прямоугольник с заданными минимальными и максимальными углами |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [INFINITE](#INFINITE) | Бесконечный ограничивающий прямоугольник |
| [NULL](#NULL) | Нулевой ограничивающий прямоугольник |
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Получает размер ограничивающего прямоугольника. |
| [getMaximum()](#getMaximum--) | Максимальный угол ограничивающего прямоугольника |
| [getMinimum()](#getMinimum--) | Минимальный угол ограничивающего прямоугольника |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | Объединяет новый прямоугольник с текущим ограничивающим прямоугольником. |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | Объединяет новый прямоугольник с текущим ограничивающим прямоугольником. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Получает строковое представление ограничивающего прямоугольника. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


Инициализировать конечный ограничивающий прямоугольник с заданными минимальными и максимальными углами

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | Минимальный угол |
| maximum | [Vector2](../../com.aspose.threed/vector2) | Максимальный угол |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


Бесконечный ограничивающий прямоугольник

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


Нулевой ограничивающий прямоугольник

### clone() {#clone--}
```
public BoundingBox2D clone()
```


Клонировать текущий экземпляр

**Returns:**
[BoundingBox2D](../../com.aspose.threed/boundingbox2d)
### copyFrom(BoundingBox2D src) {#copyFrom-com.aspose.threed.BoundingBox2D-}
```
public void copyFrom(BoundingBox2D src)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

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
### getExtent() {#getExtent--}
```
public BoundingBoxExtent getExtent()
```


Получает размер ограничивающего прямоугольника.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


Максимальный угол ограничивающего прямоугольника

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


Минимальный угол ограничивающего прямоугольника

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The minimum corner of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### merge(BoundingBox2D bb) {#merge-com.aspose.threed.BoundingBox2D-}
```
public void merge(BoundingBox2D bb)
```


Объединяет новый прямоугольник с текущим ограничивающим прямоугольником.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | Ограничивающий прямоугольник для объединения |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


Объединяет новый прямоугольник с текущим ограничивающим прямоугольником.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | Точка для объединения |

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


Получает строковое представление ограничивающего прямоугольника.

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

