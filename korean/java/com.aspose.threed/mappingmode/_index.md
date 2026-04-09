---
title: MappingMode
second_title: Aspose.3D for Java API 레퍼런스
description: 요소가 표면에 매핑되는 방식을 결정합니다.
type: docs
weight: 285
url: /ko/java/com.aspose.threed/mappingmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MappingMode extends Enum<MappingMode>
```

Determines how the element is mapped to a surface. The [MappingMode](../../com.aspose.threed/mappingmode) defined how [VertexElement](../../com.aspose.threed/vertexelement) is mapped to the surface of geometry.
## 필드

| 필드 | 설명 |
| --- | --- |
| [ALL_SAME](#ALL-SAME) | 하나의 데이터가 전체 표면에 매핑됩니다. |
| [CONTROL_POINT](#CONTROL-POINT) | 각 데이터가 기하학의 제어점에 매핑됩니다. |
| [EDGE](#EDGE) | 데이터가 에지에 매핑됩니다. |
| [POLYGON](#POLYGON) | 데이터가 폴리곤에 매핑됩니다. |
| [POLYGON_VERTEX](#POLYGON-VERTEX) | 데이터가 폴리곤의 정점에 매핑됩니다. 제어점이 여러 폴리곤에 공유되고 데이터가 [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX)으로 매핑될 경우, 서로 다른 폴리곤 정점으로서의 제어점은 각각 고유한 데이터를 갖게 됩니다. |
## 메서드

| 메서드 | 설명 |
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


하나의 데이터가 전체 표면에 매핑됩니다. 데이터가 제어점/폴리곤 정점/에지 끝점으로 해석되더라도, 데이터는 항상 [ALL\_SAME](../../com.aspose.threed/mappingmode\#ALL-SAME)으로 정의된 대로 동일합니다.

### CONTROL_POINT {#CONTROL-POINT}
```
public static final MappingMode CONTROL_POINT
```


각 데이터가 기하학의 제어점에 매핑됩니다.

### EDGE {#EDGE}
```
public static final MappingMode EDGE
```


데이터가 에지에 매핑됩니다. 매핑이 [EDGE](../../com.aspose.threed/mappingmode\#EDGE)일 때 각 에지 끝점은 동일한 데이터를 공유합니다.

### POLYGON {#POLYGON}
```
public static final MappingMode POLYGON
```


데이터가 폴리곤에 매핑됩니다. 매핑 모드가 [POLYGON](../../com.aspose.threed/mappingmode\#POLYGON)일 때 각 폴리곤 정점은 동일한 데이터를 공유합니다.

### POLYGON_VERTEX {#POLYGON-VERTEX}
```
public static final MappingMode POLYGON_VERTEX
```


데이터가 폴리곤의 정점에 매핑됩니다. 제어점이 여러 폴리곤에 공유되고 데이터가 [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX)으로 매핑될 경우, 서로 다른 폴리곤 정점으로서의 제어점은 각각 고유한 데이터를 갖게 됩니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

