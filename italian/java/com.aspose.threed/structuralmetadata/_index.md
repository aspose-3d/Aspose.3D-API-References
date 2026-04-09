---
title: StructuralMetadata
second_title: Aspose.3D for Java API Reference
description: Questa classe fornisce supporto per EXT_structural_metadata utilizzato solo in glTF.
type: docs
weight: 180
url: /it/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

Questa classe fornisce supporto per EXT\_structural\_metadata, usato solo in glTF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | Allega i metadati correnti alla scena specificata |
| [createClass(String name)](#createClass-java.lang.String-) | Crea un tipo di classe meta |
| [createEnum(String name)](#createEnum-java.lang.String-) | Crea un tipo enum |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Crea una nuova tabella delle proprietà con il tipo di classe meta fornito |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | Ottieni [StructuralMetadata](../../com.aspose.threed/structuralmetadata) associato alla scena specificata. |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | Le definizioni della classe. |
| [getEnums()](#getEnums--) | Le definizioni del tipo enum |
| [getPropertyTables()](#getPropertyTables--) | Le tabelle delle proprietà in questi metadati. |
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


Allega i metadati correnti alla scena specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


Crea un tipo di classe meta

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome della classe |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


Crea un tipo enum

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome del tipo enum |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


Crea una nuova tabella delle proprietà con il tipo di classe meta fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome della tabella delle proprietà |
| clazz | [ClassType](../../com.aspose.threed/classtype) | Il tipo di classe della nuova tabella delle proprietà |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


Ottieni [StructuralMetadata](../../com.aspose.threed/structuralmetadata) associato alla scena specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Quale scena cercare per i metadati strutturali |

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


Le definizioni della classe.

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - Le definizioni di classe.
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


Le definizioni del tipo enum

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - Le definizioni del tipo enum
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


Le tabelle delle proprietà in questi metadati.

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - Le tabelle delle proprietà in questi metadati.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

