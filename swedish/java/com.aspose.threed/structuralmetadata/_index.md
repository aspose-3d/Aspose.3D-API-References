---
title: StructuralMetadata
second_title: Aspose.3D for Java API-referens
description: Denna klass tillhandahåller stöd för EXT_structural_metadata som endast används i glTF.
type: docs
weight: 180
url: /sv/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

Denna klass tillhandahåller stöd för EXT\_structural\_metadata, som endast används i glTF.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | Bifoga aktuell metadata till angiven scen |
| [createClass(String name)](#createClass-java.lang.String-) | Skapa en metaklass-typ |
| [createEnum(String name)](#createEnum-java.lang.String-) | Skapa en uppräkningstyp |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Skapa en ny egenskapstabell med given metaklass-typ |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | Hämta [StructuralMetadata](../../com.aspose.threed/structuralmetadata) som är associerad med angiven scen. |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | Klassdefinitionerna. |
| [getEnums()](#getEnums--) | Uppräkningstypdefinitionerna |
| [getPropertyTables()](#getPropertyTables--) | Egenskapstabellerna i denna metadata. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructuralMetadata() {#StructuralMetadata--}
```
public StructuralMetadata()
```


### attach(Scene scene) {#attach-com.aspose.threed.Scene-}
```
public void attach(Scene scene)
```


Bifoga aktuell metadata till angiven scen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


Skapa en metaklass-typ

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Klassens namn |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


Skapa en uppräkningstyp

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Enum-typens namn |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


Skapa en ny egenskapstabell med given metaklass-typ

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namnet på egenskapstabellen |
| clazz | [ClassType](../../com.aspose.threed/classtype) | Klass-typen för den nya egenskapstabellen |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
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
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


Hämta [StructuralMetadata](../../com.aspose.threed/structuralmetadata) som är associerad med angiven scen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Vilken scen som ska sökas efter den strukturella metadata |

**Returns:**
[StructuralMetadata](../../com.aspose.threed/structuralmetadata) - A valid instance of [StructuralMetadata](../../com.aspose.threed/structuralmetadata) if its found in the scene, otherwise null returned
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClasses() {#getClasses--}
```
public HashMap<String,StructuralMetadata.ClassType> getClasses()
```


Klassdefinitionerna.

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - Klassdefinitionerna .
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


Uppräkningstypdefinitionerna

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - Enum-typdefinitionerna
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


Egenskapstabellerna i denna metadata.

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - Egenskapstabellerna i denna metadata.
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

