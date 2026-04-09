---
title: StructuralMetadata.PropertyTable
second_title: Referensi API Aspose.3D untuk Java
description: Tabel properti.
type: docs
weight: 14
url: /id/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

Tabel properti.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Konstruktor dari tabel properti. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | Tambahkan properti baru ke tabel properti. |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | Tambahkan properti baru ke tabel properti. |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | Lampirkan tabel properti saat ini ke data pengguna yang ditentukan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | Ekstrak tabel properti yang terlampir dari data pengguna yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | Kelas meta dari tabel properti ini. |
| [getName()](#getName--) | Nama tabel properti. |
| [getValue(String name)](#getValue-java.lang.String-) | Mendapatkan nilai dari nama properti yang ditentukan. |
| [getValues()](#getValues--) | Nilai-nilai tabel properti. |
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


Konstruktor dari tabel properti.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama dari instance tabel ini. |
| mclass | [ClassType](../../com.aspose.threed/classtype) | Definisi kelas meta dari tabel properti ini. |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


Tambahkan properti baru ke tabel properti.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | Properti mana yang akan ditambahkan dengan nilai. |
| nilai | java.lang.Object | Array nilai. |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


Tambahkan properti baru ke tabel properti.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propName | java.lang.String | Properti mana yang akan ditambahkan dengan nilai. |
| nilai | java.lang.Object | Array nilai. |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


Lampirkan tabel properti saat ini ke data pengguna yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


Ekstrak tabel properti yang terlampir dari data pengguna yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | Data pengguna yang terkait dengan tabel properti. |

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


Kelas meta dari tabel properti ini.

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


Nama tabel properti.

**Returns:**
java.lang.String - Nama tabel properti.
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


Mendapatkan nilai dari nama properti yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama properti |

**Returns:**
java.lang.Object - Nilai properti atau null jika tidak ditemukan.
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


Nilai-nilai tabel properti.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - Nilai-nilai tabel properti.
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

