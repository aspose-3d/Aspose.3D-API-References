---
title: "StructuralMetadata"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Cette classe fournit la prise en charge de EXT_structural_metadata uniquement utilisé dans glTF."
type: docs
weight: 180
url: /fr/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

Cette classe fournit la prise en charge de EXT\_structural\_metadata, uniquement utilisé dans glTF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | Attacher les métadonnées actuelles à la scène spécifiée |
| [createClass(String name)](#createClass-java.lang.String-) | Créer un type de classe méta |
| [createEnum(String name)](#createEnum-java.lang.String-) | Créer un type d'énumération |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Créer une nouvelle table de propriétés avec le type de classe méta donné |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | Obtenir [StructuralMetadata](../../com.aspose.threed/structuralmetadata) associé à la scène spécifiée. |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | Les définitions de classe. |
| [getEnums()](#getEnums--) | Les définitions de type d'énumération |
| [getPropertyTables()](#getPropertyTables--) | Les tables de propriétés dans ces métadonnées. |
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


Attacher les métadonnées actuelles à la scène spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


Créer un type de classe méta

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom de la classe |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


Créer un type d'énumération

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom du type d'énumération |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


Créer une nouvelle table de propriétés avec le type de classe méta donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom de la table de propriétés |
| clazz | [ClassType](../../com.aspose.threed/classtype) | Le type de classe de la nouvelle table de propriétés |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


Obtenir [StructuralMetadata](../../com.aspose.threed/structuralmetadata) associé à la scène spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Quelle scène rechercher pour les métadonnées structurelles |

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


Les définitions de classe.

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - Les définitions de classe .
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


Les définitions de type d'énumération

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - Les définitions du type d'énumération
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


Les tables de propriétés dans ces métadonnées.

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - Les tables de propriétés dans ces métadonnées.
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

