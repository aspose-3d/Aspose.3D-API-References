---
title: "StructuralMetadata.PropertyTable"
second_title: "Aspose.3D for Java API Referansı"
description: "Özellik tablosu."
type: docs
weight: 14
url: /tr/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

Özellik tablosu.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Property table'ın yapıcı metodu. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | Property table'a yeni bir özellik ekle. |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | Property table'a yeni bir özellik ekle. |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | Mevcut property table'ı belirtilen kullanıcı verisine ekle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | Belirtilen kullanıcı verisinden ekli property table'ı çıkar. |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | Bu property table'ın meta sınıfı. |
| [getName()](#getName--) | Property table'ın adı. |
| [getValue(String name)](#getValue-java.lang.String-) | Belirtilen özellik adının değerini alır. |
| [getValues()](#getValues--) | Property table'ın değerleri. |
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


Property table'ın yapıcı metodu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Bu tablo örneğinin adı. |
| mclass | [ClassType](../../com.aspose.threed/classtype) | Bu property table'ın meta sınıf tanımı. |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


Property table'a yeni bir özellik ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | Hangi özelliği değerle ekleyeceksiniz |
| değer | java.lang.Object | Değerler dizisi |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


Property table'a yeni bir özellik ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propName | java.lang.String | Hangi özelliği değerle ekleyeceksiniz |
| değer | java.lang.Object | Değerler dizisi |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


Mevcut property table'ı belirtilen kullanıcı verisine ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

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
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


Belirtilen kullanıcı verisinden ekli property table'ı çıkar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | Bir property table ile ilişkili kullanıcı verisi. |

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


Bu property table'ın meta sınıfı.

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


Property table'ın adı.

**Returns:**
java.lang.String - Property table'ın adı.
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


Belirtilen özellik adının değerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Özellik adı |

**Returns:**
java.lang.Object - Özellik değeri veya bulunamazsa null
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


Property table'ın değerleri.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - Property table'ın değerleri.
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

