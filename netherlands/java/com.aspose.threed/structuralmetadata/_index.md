---
title: StructuralMetadata
second_title: Aspose.3D for Java API-referentie
description: Deze klasse biedt ondersteuning voor EXT_structural_metadata, alleen gebruikt in glTF.
type: docs
weight: 180
url: /nl/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

Deze klasse biedt ondersteuning voor EXT\_structural\_metadata, alleen gebruikt in glTF.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | Huidige metagegevens aan de opgegeven scène koppelen |
| [createClass(String name)](#createClass-java.lang.String-) | Een meta‑klassetype maken |
| [createEnum(String name)](#createEnum-java.lang.String-) | Een enum‑type maken |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Een nieuwe eigenschapstabel maken met het opgegeven meta‑klassetype |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | Haalt [StructuralMetadata](../../com.aspose.threed/structuralmetadata) op die aan de opgegeven scène is gekoppeld. |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | De klassedefinities. |
| [getEnums()](#getEnums--) | De enum‑type-definities |
| [getPropertyTables()](#getPropertyTables--) | De eigenschapstabellen in deze metadata. |
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


Huidige metagegevens aan de opgegeven scène koppelen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


Een meta‑klassetype maken

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van de klasse |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


Een enum‑type maken

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van het enumtype |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


Een nieuwe eigenschapstabel maken met het opgegeven meta‑klassetype

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van de eigenschapstabel |
| clazz | [ClassType](../../com.aspose.threed/classtype) | Het klassetype van de nieuwe eigenschapstabel |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


Haalt [StructuralMetadata](../../com.aspose.threed/structuralmetadata) op die aan de opgegeven scène is gekoppeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Welke scène moet worden doorzocht voor de structurele metadata |

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


De klassedefinities.

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - De klasse-definities.
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


De enum‑type-definities

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - De enumtype-definities
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


De eigenschapstabellen in deze metadata.

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - De eigenschapstabellen in deze metadata.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

