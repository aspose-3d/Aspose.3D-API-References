---
title: StructuralMetadata
second_title: Referencia de API de Aspose.3D para Java
description: Esta clase proporciona soporte para EXT_structural_metadata, solo usado en glTF.
type: docs
weight: 180
url: /es/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

Esta clase brinda soporte para EXT\_structural\_metadata, solo usado en glTF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | Adjuntar los metadatos actuales a la escena especificada |
| [createClass(String name)](#createClass-java.lang.String-) | Crear un tipo de clase meta |
| [createEnum(String name)](#createEnum-java.lang.String-) | Crear un tipo enum |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Crear una nueva tabla de propiedades con el tipo de clase meta dado |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | Obtener [StructuralMetadata](../../com.aspose.threed/structuralmetadata) asociado con la escena especificada. |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | Las definiciones de clase. |
| [getEnums()](#getEnums--) | Las definiciones de tipo enum |
| [getPropertyTables()](#getPropertyTables--) | Las tablas de propiedades en estos metadatos. |
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


Adjuntar los metadatos actuales a la escena especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


Crear un tipo de clase meta

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre de la clase |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


Crear un tipo enum

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre del tipo enum |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


Crear una nueva tabla de propiedades con el tipo de clase meta dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre de la tabla de propiedades |
| clazz | [ClassType](../../com.aspose.threed/classtype) | El tipo de clase de la nueva tabla de propiedades |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


Obtener [StructuralMetadata](../../com.aspose.threed/structuralmetadata) asociado con la escena especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Qué escena buscar para los metadatos estructurales |

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


Las definiciones de clase.

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - Las definiciones de clase.
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


Las definiciones de tipo enum

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - Las definiciones del tipo enum
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


Las tablas de propiedades en estos metadatos.

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - Las tablas de propiedades en estos metadatos.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

