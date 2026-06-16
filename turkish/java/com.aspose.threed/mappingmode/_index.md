---
title: "MappingMode"
second_title: "Aspose.3D for Java API Referansı"
description: "Elemanın bir yüzeye nasıl eşlendiğini belirler."
type: docs
weight: 285
url: /tr/java/com.aspose.threed/mappingmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MappingMode extends Enum<MappingMode>
```

Elemanın bir yüzeye nasıl eşlendiğini belirler. [MappingMode](../../com.aspose.threed/mappingmode) öğesi, [VertexElement](../../com.aspose.threed/vertexelement) öğesinin geometrinin yüzeyine nasıl eşlendiğini tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ALL_SAME](#ALL-SAME) | Tüm yüzeye eşlenen bir veri. |
| [CONTROL_POINT](#CONTROL-POINT) | Her veri, geometrinin kontrol noktasına eşlenir. |
| [EDGE](#EDGE) | Veri kenara eşlenir. |
| [POLYGON](#POLYGON) | Veri çokgene eşlenir. |
| [POLYGON_VERTEX](#POLYGON-VERTEX) | Veri, çokgenin köşesine eşlenir. Bir kontrol noktası birden fazla çokgen tarafından paylaşıldığında ve veri [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX) olarak eşlendiğinde, farklı çokgen köşesi olarak kullanılan kontrol noktası kendi verisine sahip olacaktır. |
## Yöntemler

| Yöntem | Açıklama |
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


Tüm yüzeye eşlenen bir veri. Kontrol noktası/çokgen köşesi/kenar uç noktaları olarak yorumlanan veri ne olursa olsun, veri her zaman [ALL\_SAME](../../com.aspose.threed/mappingmode\#ALL-SAME) tarafından tanımlandığı gibi aynı kalır.

### CONTROL_POINT {#CONTROL-POINT}
```
public static final MappingMode CONTROL_POINT
```


Her veri, geometrinin kontrol noktasına eşlenir.

### EDGE {#EDGE}
```
public static final MappingMode EDGE
```


Veri kenara eşlenir. Kenarın her uç noktası, eşleme [EDGE](../../com.aspose.threed/mappingmode\#EDGE) olduğunda aynı veriyi paylaşır.

### POLYGON {#POLYGON}
```
public static final MappingMode POLYGON
```


Veri çokgene eşlenir. Çokgenin her köşesi, eşleme modu [POLYGON](../../com.aspose.threed/mappingmode\#POLYGON) olduğunda aynı veriyi paylaşır.

### POLYGON_VERTEX {#POLYGON-VERTEX}
```
public static final MappingMode POLYGON_VERTEX
```


Veri, çokgenin köşesine eşlenir. Bir kontrol noktası birden fazla çokgen tarafından paylaşıldığında ve veri [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX) olarak eşlendiğinde, farklı çokgen köşesi olarak kullanılan kontrol noktası kendi verisine sahip olacaktır.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

