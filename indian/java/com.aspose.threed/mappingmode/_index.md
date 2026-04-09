---
title: MappingMode
second_title: Aspose.3D for Java API Reference
description: निर्धारित करता है कि तत्व सतह पर कैसे मैप किया जाता है।
type: docs
weight: 285
url: /hi/java/com.aspose.threed/mappingmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MappingMode extends Enum<MappingMode>
```

Determines how the element is mapped to a surface. The [MappingMode](../../com.aspose.threed/mappingmode) defined how [VertexElement](../../com.aspose.threed/vertexelement) is mapped to the surface of geometry.
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ALL_SAME](#ALL-SAME) | एक डेटा पूरे सतह पर मैप किया गया है। |
| [CONTROL_POINT](#CONTROL-POINT) | प्रत्येक डेटा ज्यामिति के नियंत्रण बिंदु पर मैप किया जाता है। |
| [EDGE](#EDGE) | डेटा किनारे पर मैप किया गया है। |
| [POLYGON](#POLYGON) | डेटा बहुभुज पर मैप किया गया है। |
| [POLYGON_VERTEX](#POLYGON-VERTEX) | डेटा बहुभुज के शीर्ष बिंदु पर मैप किया जाता है जब एक नियंत्रण बिंदु कई बहुभुजों द्वारा साझा किया जाता है, और डेटा को [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX) के रूप में मैप किया जाता है, तो विभिन्न बहुभुज शीर्ष बिंदु के रूप में नियंत्रण बिंदु का अपना डेटा होगा। |
## Methods

| Method | विवरण |
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


एक डेटा पूरे सतह पर मैप किया गया है। चाहे डेटा को नियंत्रण बिंदु/बहुभुज शीर्ष बिंदु/किनारे के अंत बिंदु के रूप में व्याख्यायित किया जाए, डेटा हमेशा वही रहता है जैसा कि यह [ALL\_SAME](../../com.aspose.threed/mappingmode\#ALL-SAME) द्वारा परिभाषित है।

### CONTROL_POINT {#CONTROL-POINT}
```
public static final MappingMode CONTROL_POINT
```


प्रत्येक डेटा ज्यामिति के नियंत्रण बिंदु पर मैप किया जाता है।

### EDGE {#EDGE}
```
public static final MappingMode EDGE
```


डेटा किनारे पर मैप किया गया है। जब मैपिंग [EDGE](../../com.aspose.threed/mappingmode\#EDGE) है, तो प्रत्येक किनारे के अंत बिंदु एक ही डेटा साझा करते हैं।

### POLYGON {#POLYGON}
```
public static final MappingMode POLYGON
```


डेटा बहुभुज पर मैप किया गया है। जब मैपिंग मोड [POLYGON](../../com.aspose.threed/mappingmode\#POLYGON) है, तो प्रत्येक बहुभुज शीर्ष बिंदु एक ही डेटा साझा करता है।

### POLYGON_VERTEX {#POLYGON-VERTEX}
```
public static final MappingMode POLYGON_VERTEX
```


डेटा बहुभुज के शीर्ष बिंदु पर मैप किया जाता है जब एक नियंत्रण बिंदु कई बहुभुजों द्वारा साझा किया जाता है, और डेटा को [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX) के रूप में मैप किया जाता है, तो विभिन्न बहुभुज शीर्ष बिंदु के रूप में नियंत्रण बिंदु का अपना डेटा होगा।

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

