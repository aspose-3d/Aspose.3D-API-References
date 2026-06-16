---
title: "StructuralMetadata"
second_title: "Aspose.3D for Java API Referansı"
description: "Bu sınıf, yalnızca glTF'de kullanılan EXT_structural_metadata desteği sağlar."
type: docs
weight: 180
url: /tr/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

Bu sınıf, yalnızca glTF'de kullanılan EXT\\_structural\\_metadata desteği sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | Mevcut meta veriyi belirtilen sahneye ekle |
| [createClass(String name)](#createClass-java.lang.String-) | Bir meta sınıf türü oluştur |
| [createEnum(String name)](#createEnum-java.lang.String-) | Bir enum türü oluştur |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Verilen meta sınıf türüyle yeni bir özellik tablosu oluştur |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | Belirtilen sahneyle ilişkili [StructuralMetadata](../../com.aspose.threed/structuralmetadata) alın. |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | Sınıf tanımları. |
| [getEnums()](#getEnums--) | Enum türü tanımları |
| [getPropertyTables()](#getPropertyTables--) | Bu meta verideki özellik tabloları. |
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


Mevcut meta veriyi belirtilen sahneye ekle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


Bir meta sınıf türü oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Sınıfın adı |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


Bir enum türü oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Enum tipinin adı |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


Verilen meta sınıf türüyle yeni bir özellik tablosu oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Özellik tablosunun adı |
| clazz | [ClassType](../../com.aspose.threed/classtype) | Yeni özellik tablosunun sınıf tipi |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


Belirtilen sahneyle ilişkili [StructuralMetadata](../../com.aspose.threed/structuralmetadata) alın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Yapısal meta veriyi aramak için hangi sahne |

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


Sınıf tanımları.

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - Sınıf tanımları.
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


Enum türü tanımları

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - Enum tipi tanımları
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


Bu meta verideki özellik tabloları.

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - Bu meta verideki özellik tabloları.
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

