---
title: BoundingBox
second_title: Справочник API Aspose.3D для Java
description: Осиально-выравненный ограничивающий прямоугольник Пример  Следующий код показывает, как получить ограничивающий прямоугольник из экземпляра Entity.
type: docs
weight: 24
url: /ru/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

Осиально-выравненный ограничительный параллелепипед **Пример:** Следующий код показывает, как получить ограничительный параллелепипед из экземпляра Entity.

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Инициализировать конечный ограничивающий прямоугольник с заданными минимальными и максимальными углами |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | Инициализировать конечный ограничивающий прямоугольник с заданными минимальными и максимальными углами |
| [BoundingBox()](#BoundingBox--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | Ограничивающий прямоугольник для проверки, находится ли он внутри текущего ограничивающего прямоугольника. |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | Проверьте, находится ли точка p внутри ограничивающего прямоугольника |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равны ли два объекта |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | Создать ограничивающий прямоугольник из заданной геометрии |
| [getCenter()](#getCenter--) | Центр ограничивающего прямоугольника. |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Получает размер ограничивающего прямоугольника. |
| [getInfinite()](#getInfinite--) | Бесконечный ограничивающий прямоугольник |
| [getMaximum()](#getMaximum--) | Максимальный угол ограничивающего прямоугольника |
| [getMinimum()](#getMinimum--) | Минимальный угол ограничивающего прямоугольника |
| [getNull()](#getNull--) | Нулевой ограничивающий прямоугольник |
| [getSize()](#getSize--) | Размер ограничивающего прямоугольника |
| [hashCode()](#hashCode--) | Возвращает хеш‑код этого экземпляра |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | Объединяет новый прямоугольник с текущим ограничивающим прямоугольником. |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | Объединить текущий ограничивающий прямоугольник с заданной точкой |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | Объединить текущий ограничивающий прямоугольник с заданной точкой |
| [merge(double x, double y, double z)](#merge-double-double-double-) | Объединить текущий ограничивающий прямоугольник с заданной точкой |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | Перегрузка оператора умножения, минимальный и максимальный угол нового ограничивающего прямоугольника будут преобразованы матрицей. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | Проверьте, пересекается ли текущий ограничивающий прямоугольник с указанным ограничивающим прямоугольником. |
| [scale()](#scale--) | Вычисляет абсолютное наибольшее значение координаты любой содержащейся точки. |
| [toString()](#toString--) | Получает строковое представление ограничивающего прямоугольника. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


Инициализировать конечный ограничивающий прямоугольник с заданными минимальными и максимальными углами

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | Минимальный угол |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | Максимальный угол **Example:** Следующий код показывает, как построить ограничивающий прямоугольник из минимального и максимального углов. |

```
var minimum = new Vector3(0, 0, 0);
  var maximum = new Vector3(10, 10, 10);
  var boundingBox = new BoundingBox(minimum, maximum);
  System.out.println("Bounding box = " + boundingBox);
``` |

### BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ) {#BoundingBox-double-double-double-double-double-double-}
```
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```


Инициализировать конечный ограничивающий прямоугольник с заданными минимальными и максимальными углами

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| minX | double | X минимального угла |
| minY | double | Минимальный угол Y |
| minZ | double | Минимальный угол Z |
| maxX | double | Максимальный угол X |
| maxY | double | Максимальный угол Y |
|  | maxZ | double | Максимальный угол Z **Пример:** Следующий код показывает, как построить ограничивающий параллелепипед из минимального и максимального углов. |

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  System.out.println("Bounding box = " + boundingBox);
``` |

### BoundingBox() {#BoundingBox--}
```
public BoundingBox()
```


### clone() {#clone--}
```
public BoundingBox clone()
```


Клонировать текущий экземпляр

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox)
### contains(BoundingBox bbox) {#contains-com.aspose.threed.BoundingBox-}
```
public boolean contains(BoundingBox bbox)
```


Ограничивающий прямоугольник для проверки, находится ли он внутри текущего ограничивающего прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


Проверьте, находится ли точка p внутри ограничивающего прямоугольника

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | Точка для проверки |

**Returns:**
boolean - True, если точка находится внутри ограничивающего параллелепипеда **Пример:** Следующий код показывает, как проверить, находится ли точка внутри ограничивающего параллелепипеда.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var pt = new Vector3(4, 4, 4);
  System.out.println("Bounding box overlaps = " + boundingBox.contains(pt));
```
### copyFrom(BoundingBox src) {#copyFrom-com.aspose.threed.BoundingBox-}
```
public void copyFrom(BoundingBox src)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равны ли два объекта

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения |

**Returns:**
boolean - true, если два объекта равны
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


Создать ограничивающий прямоугольник из заданной геометрии

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | Геометрия для вычисления ограничивающего параллелепипеда |

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of given geometry **Example:** The following code shows how to construct a bounding box from a geometry instance.

```
var sphere = (new Sphere()).toMesh();
  var boundingBox = BoundingBox.fromGeometry(sphere);
  System.out.println("Bounding box = " + boundingBox);
```
### getCenter() {#getCenter--}
```
public Vector3 getCenter()
```


Центр ограничивающего прямоугольника.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The center of the bounding box.
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
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


Бесконечный ограничивающий прямоугольник

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


Максимальный угол ограничивающего прямоугольника

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


Минимальный угол ограничивающего прямоугольника

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


Нулевой ограничивающий прямоугольник

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


Размер ограничивающего прямоугольника

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код этого экземпляра

**Returns:**
int - Хеш-код ограничивающего параллелепипеда
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


Объединяет новый прямоугольник с текущим ограничивающим прямоугольником.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | Ограничивающий прямоугольник для объединения |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


Объединить текущий ограничивающий прямоугольник с заданной точкой

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | Точка, которую нужно объединить с ограничивающим параллелепипедом **Пример:** Следующий код показывает, как объединить точку с ограничивающим параллелепипедом. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


Объединить текущий ограничивающий прямоугольник с заданной точкой

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | Точка, которую нужно объединить с ограничивающим параллелепипедом **Пример:** Следующий код показывает, как объединить точку с ограничивающим параллелепипедом. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


Объединить текущий ограничивающий прямоугольник с заданной точкой

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | double | Точка, которую нужно объединить с ограничивающим параллелепипедом |
| y | double | Точка, которую нужно объединить с ограничивающим параллелепипедом |
|  | z | double | Точка, которую нужно объединить с ограничивающим параллелепипедом **Пример:** Следующий код показывает, как объединить точку с ограничивающим параллелепипедом. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


Перегрузка оператора умножения, минимальный и максимальный угол нового ограничивающего прямоугольника будут преобразованы матрицей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | Входной ограничивающий параллелепипед. |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | Матрица, используемая для преобразования углов ограничивающего параллелепипеда |

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The product of bounding box and transform matrix.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### overlapsWith(BoundingBox box) {#overlapsWith-com.aspose.threed.BoundingBox-}
```
public boolean overlapsWith(BoundingBox box)
```


Проверьте, пересекается ли текущий ограничивающий прямоугольник с указанным ограничивающим прямоугольником.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | Другой ограничивающий параллелепипед для проверки |

**Returns:**
boolean - True, если текущий ограничивающий параллелепипед перекрывается с заданным. **Пример:** Следующий код показывает, как проверить, перекрываются ли два ограничивающих параллелепипеда.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


Вычисляет абсолютное наибольшее значение координаты любой содержащейся точки.

**Returns:**
double - вычисленное абсолютное наибольшее значение координаты любой содержащейся точки.
### toString() {#toString--}
```
public String toString()
```


Получает строковое представление ограничивающего прямоугольника.

**Returns:**
java.lang.String - Строковое представление ограничивающего параллелепипеда.
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

