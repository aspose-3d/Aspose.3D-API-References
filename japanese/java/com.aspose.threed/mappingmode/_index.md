---
title: MappingMode
second_title: Aspose.3D for Java API リファレンス
description: 要素が表面にどのようにマッピングされるかを決定します。
type: docs
weight: 285
url: /ja/java/com.aspose.threed/mappingmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MappingMode extends Enum<MappingMode>
```

要素が表面にどのようにマッピングされるかを決定します。 [MappingMode](../../com.aspose.threed/mappingmode) は、[VertexElement](../../com.aspose.threed/vertexelement) がジオメトリの表面にどのようにマッピングされるかを定義します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ALL_SAME](#ALL-SAME) | 1つのデータが全体の表面にマッピングされます。 |
| [CONTROL_POINT](#CONTROL-POINT) | 各データはジオメトリの制御点にマッピングされます。 |
| [EDGE](#EDGE) | データはエッジにマッピングされます。 |
| [POLYGON](#POLYGON) | データはポリゴンにマッピングされます。 |
| [POLYGON_VERTEX](#POLYGON-VERTEX) | データはポリゴンの頂点にマッピングされます。制御点が複数のポリゴンで共有され、データが [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX) としてマッピングされる場合、異なるポリゴンの頂点としての制御点はそれぞれ独自のデータを持ちます。 |
## Methods

| Method | 説明 |
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


1つのデータが全体の表面にマッピングされます。データが制御点／ポリゴンの頂点／エッジの端点として解釈される場合でも、データは常に [ALL\_SAME](../../com.aspose.threed/mappingmode\#ALL-SAME) で定義された通りに同一です。

### CONTROL_POINT {#CONTROL-POINT}
```
public static final MappingMode CONTROL_POINT
```


各データはジオメトリの制御点にマッピングされます。

### EDGE {#EDGE}
```
public static final MappingMode EDGE
```


データはエッジにマッピングされます。マッピングが [EDGE](../../com.aspose.threed/mappingmode\#EDGE) の場合、各エッジの端点は同じデータを共有します。

### POLYGON {#POLYGON}
```
public static final MappingMode POLYGON
```


データはポリゴンにマッピングされます。マッピングモードが [POLYGON](../../com.aspose.threed/mappingmode\#POLYGON) の場合、各ポリゴンの頂点は同じデータを共有します。

### POLYGON_VERTEX {#POLYGON-VERTEX}
```
public static final MappingMode POLYGON_VERTEX
```


データはポリゴンの頂点にマッピングされます。制御点が複数のポリゴンで共有され、データが [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX) としてマッピングされる場合、異なるポリゴンの頂点としての制御点はそれぞれ独自のデータを持ちます。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
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
| Parameter | Type | 説明 |
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
| Parameter | Type | 説明 |
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
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

