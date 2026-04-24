---
title: NurbsDirection
second_title: Справочник API Aspose.3D для Java
description: У 3D  есть два направления,  и ,  определяют данные для каждого направления.
type: docs
weight: 113
url: /ru/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

У 3D [NurbsSurface](../../com.aspose.threed/nurbssurface) есть два направления, [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) и [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV), [NurbsDirection](../../com.aspose.threed/nurbsdirection) определяет данные для каждого направления. Направление фактически является NURBS‑кривой, что означает, что оно также определяется своим [getOrder](../../com.aspose.threed/nurbsdirection\#getOrder), [getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors) и набором взвешенных контрольных точек (определённых в [NurbsSurface](../../com.aspose.threed/nurbssurface)).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | Создайте новый экземпляр [NurbsDirection](../../com.aspose.threed/nurbsdirection) |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Возвращает количество контрольных точек в текущем направлении. |
| [getDegree()](#getDegree--) | Получает степень NURBS-кривой, степень определяется как Order - 1 |
| [getDivisions()](#getDivisions--) | Получает количество делений между соседними контрольными точками в текущем направлении. |
| [getKnotVectors()](#getKnotVectors--) | Получает вектор узлов; это последовательность параметрических значений, определяющих, где и как контрольные точки влияют на NURBS-кривую. |
| [getMultiplicity()](#getMultiplicity--) | Получает мультипликативность. |
| [getOrder()](#getOrder--) | Получает порядок NURBS-кривой, он определяет количество соседних контрольных точек, влияющих на любую точку кривой. |
| [getType()](#getType--) | Получает тип текущего направления. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | Устанавливает количество контрольных точек в текущем направлении. |
| [setDegree(int value)](#setDegree-int-) | Устанавливает степень NURBS-кривой, степень определяется как Order - 1 |
| [setDivisions(int value)](#setDivisions-int-) | Устанавливает количество делений между соседними контрольными точками в текущем направлении. |
| [setOrder(int value)](#setOrder-int-) | Устанавливает порядок NURBS-кривой, он определяет количество соседних контрольных точек, влияющих на любую точку кривой. |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | Устанавливает тип текущего направления. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


Создайте новый экземпляр [NurbsDirection](../../com.aspose.threed/nurbsdirection)

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Возвращает количество контрольных точек в текущем направлении.

**Returns:**
int — количество контрольных точек в текущем направлении.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Получает степень NURBS-кривой, степень определяется как Order - 1

**Returns:**
int — степень NURBS-кривой, степень определяется как Order - 1
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


Получает количество делений между соседними контрольными точками в текущем направлении.

**Returns:**
int — количество делений между соседними контрольными точками в текущем направлении.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Получает вектор узлов; это последовательность параметрических значений, определяющих, где и как контрольные точки влияют на NURBS-кривую.

**Returns:**
java.util.List<java.lang.Double> — вектор узлов; это последовательность параметрических значений, определяющих, где и как контрольные точки влияют на NURBS-кривую.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Получает мультипликативность.

**Returns:**
java.util.List<java.lang.Integer> - кратность.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Получает порядок NURBS-кривой, он определяет количество соседних контрольных точек, влияющих на любую точку кривой.

**Returns:**
int - порядок NURBS‑кривой, он определяет количество соседних контрольных точек, влияющих на любую точку кривой.
### getType() {#getType--}
```
public NurbsType getType()
```


Получает тип текущего направления.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the current direction.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Устанавливает количество контрольных точек в текущем направлении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Устанавливает степень NURBS-кривой, степень определяется как Order - 1

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


Устанавливает количество делений между соседними контрольными точками в текущем направлении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Устанавливает порядок NURBS-кривой, он определяет количество соседних контрольных точек, влияющих на любую точку кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


Устанавливает тип текущего направления.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Новое значение |

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

