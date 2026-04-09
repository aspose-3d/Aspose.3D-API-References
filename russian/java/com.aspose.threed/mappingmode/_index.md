---
title: MappingMode
second_title: Справочник API Aspose.3D для Java
description: Определяет, как элемент отображается на поверхность.
type: docs
weight: 285
url: /ru/java/com.aspose.threed/mappingmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MappingMode extends Enum<MappingMode>
```

Определяет, как элемент отображается на поверхность. [MappingMode](../../com.aspose.threed/mappingmode) определяет, как [VertexElement](../../com.aspose.threed/vertexelement) отображается на поверхность геометрии.
## Поля

| Поле | Описание |
| --- | --- |
| [ALL_SAME](#ALL-SAME) | Один элемент данных отображён на всю поверхность. |
| [CONTROL_POINT](#CONTROL-POINT) | Каждый элемент данных отображён на контрольную точку геометрии. |
| [EDGE](#EDGE) | Данные отображаются на ребро. |
| [POLYGON](#POLYGON) | Данные отображаются на полигон. |
| [POLYGON_VERTEX](#POLYGON-VERTEX) | Данные отображаются на вершину полигона. Когда контрольная точка используется несколькими полигонами и данные отображаются как [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX), контрольная точка как вершина разных полигонов будет иметь свои собственные данные. |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ALL_SAME {#ALL-SAME}
```
public static final MappingMode ALL_SAME
```


Один элемент данных отображён на всю поверхность. Как бы ни интерпретировались данные — как контрольная точка, вершина полигона или конечные точки ребра, данные всегда одинаковы, как определено в [ALL\_SAME](../../com.aspose.threed/mappingmode\#ALL-SAME).

### CONTROL_POINT {#CONTROL-POINT}
```
public static final MappingMode CONTROL_POINT
```


Каждый элемент данных отображён на контрольную точку геометрии.

### EDGE {#EDGE}
```
public static final MappingMode EDGE
```


Данные отображаются на ребро. Каждая конечная точка ребра использует одни и те же данные, когда отображение выполнено в режиме [EDGE](../../com.aspose.threed/mappingmode\#EDGE).

### POLYGON {#POLYGON}
```
public static final MappingMode POLYGON
```


Данные отображаются на полигон. Каждая вершина полигона использует одни и те же данные, когда режим отображения — [POLYGON](../../com.aspose.threed/mappingmode\#POLYGON).

### POLYGON_VERTEX {#POLYGON-VERTEX}
```
public static final MappingMode POLYGON_VERTEX
```


Данные отображаются на вершину полигона. Когда контрольная точка используется несколькими полигонами и данные отображаются как [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX), контрольная точка как вершина разных полигонов будет иметь свои собственные данные.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MappingMode valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode)
### values() {#values--}
```
public static MappingMode[] values()
```




**Returns:**
com.aspose.threed.MappingMode[]
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

