---
title: StructuralMetadata.PropertyTable
second_title: Aspose.3D for Java API-referens
description: Egenskapstabell.
type: docs
weight: 14
url: /sv/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

Egenskapstabell.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Konstruktor för egenskapstabellen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | Lägg till en ny egenskap i egenskapstabellen. |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | Lägg till en ny egenskap i egenskapstabellen. |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | Bifoga aktuell egenskapstabell till specificerad användardata |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | Extrahera bifogad egenskapstabell från specificerad användardata |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | Metaklassen för denna egenskapstabell. |
| [getName()](#getName--) | Namn på egenskapstabellen. |
| [getValue(String name)](#getValue-java.lang.String-) | Hämtar värdet för angivet egenskapsnamn |
| [getValues()](#getValues--) | Värden i egenskapstabellen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PropertyTable(String name, StructuralMetadata.ClassType mclass) {#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public PropertyTable(String name, StructuralMetadata.ClassType mclass)
```


Konstruktor för egenskapstabellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namnet på denna tabellinstans. |
| mclass | [ClassType](../../com.aspose.threed/classtype) | Metaklassdefinitionen för denna egenskapstabell |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


Lägg till en ny egenskap i egenskapstabellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | Vilken egenskap som ska läggas till med värde |
| värde | java.lang.Object | Array av värden |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


Lägg till en ny egenskap i egenskapstabellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propName | java.lang.String | Vilken egenskap som ska läggas till med värde |
| värde | java.lang.Object | Array av värden |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


Bifoga aktuell egenskapstabell till specificerad användardata

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


Extrahera bifogad egenskapstabell från specificerad användardata

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | Användardatan som är associerad med en egenskapstabell |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The associated property table instance
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMetaClass() {#getMetaClass--}
```
public StructuralMetadata.ClassType getMetaClass()
```


Metaklassen för denna egenskapstabell.

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


Namn på egenskapstabellen.

**Returns:**
java.lang.String - Namn på egenskapstabellen.
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


Hämtar värdet för angivet egenskapsnamn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Egenskapsnamn |

**Returns:**
java.lang.Object - Egendomsvärde eller null om det inte hittas
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


Värden i egenskapstabellen.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - Värden i egenskapstabellen.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

