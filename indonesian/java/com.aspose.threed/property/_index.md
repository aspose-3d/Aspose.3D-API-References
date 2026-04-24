---
title: StructuralMetadata.Property
second_title: Referensi API Aspose.3D untuk Java
description: Definisi properti dalam kelas meta data.
type: docs
weight: 13
url: /id/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

Definisi properti dalam kelas metadata
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | Konstruktor properti metadata. |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | Konstruktor properti metadata. |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | Konstruktor properti metadata. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Jumlah data untuk array berukuran tetap. |
| [getDescription()](#getDescription--) | Deskripsi properti. |
| [getDisplayName()](#getDisplayName--) | Nama properti, digunakan oleh UI untuk representasi. |
| [getEnumType()](#getEnumType--) | Tipe enum. |
| [getName()](#getName--) | Nama unik properti. |
| [getNormalized()](#getNormalized--) | Apakah data dinormalisasi. |
| [getType()](#getType--) | Tipe data properti. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | Jumlah data untuk array berukuran tetap. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Deskripsi properti. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Nama properti, digunakan oleh UI untuk representasi. |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | Tipe enum. |
| [setNormalized(boolean value)](#setNormalized-boolean-) | Apakah data dinormalisasi. |
| [toString()](#toString--) | Mendapatkan representasi string dari instance ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


Konstruktor properti metadata.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama unik properti. |
| displayName | java.lang.String | Nama properti, digunakan oleh UI untuk representasi. |
| description | java.lang.String | Deskripsi properti. |
| type | java.lang.Class<?> | Tipe data properti. |
| normalized | boolean | Apakah data dinormalisasi |
| jumlah | java.lang.Integer | Jumlah data untuk array berukuran tetap |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


Konstruktor properti metadata.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama unik properti. |
| displayName | java.lang.String | Nama properti, digunakan oleh UI untuk representasi. |
| description | java.lang.String | Deskripsi properti. |
| type | [EnumType](../../com.aspose.threed/enumtype) | Tipe data properti. |
| array | boolean | Apakah setiap nilai properti berupa array atau skalar |
| jumlah | java.lang.Integer | Jumlah data untuk array berukuran tetap |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


Konstruktor properti metadata.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama unik properti. |
| type | java.lang.Class<?> | Tipe data properti. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public Integer getCount()
```


Jumlah data untuk array berukuran tetap.

**Returns:**
java.lang.Integer - Jumlah data untuk array berukuran tetap.
### getDescription() {#getDescription--}
```
public String getDescription()
```


Deskripsi properti.

**Returns:**
java.lang.String - Deskripsi properti
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


Nama properti, digunakan oleh UI untuk representasi.

**Returns:**
java.lang.String - Nama properti, digunakan oleh UI untuk representasi.
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


Tipe enum.

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


Nama unik properti.

**Returns:**
java.lang.String - Nama unik properti
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


Apakah data dinormalisasi.

**Returns:**
boolean - Apakah data dinormalisasi.
### getType() {#getType--}
```
public Class<?> getType()
```


Tipe data properti.

**Returns:**
java.lang.Class<?> - Tipe data properti
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




### setCount(Integer value) {#setCount-java.lang.Integer-}
```
public void setCount(Integer value)
```


Jumlah data untuk array berukuran tetap.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Integer | Nilai baru |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Deskripsi properti.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


Nama properti, digunakan oleh UI untuk representasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


Tipe enum.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | Nilai baru |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


Apakah data dinormalisasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### toString() {#toString--}
```
public String toString()
```


Mendapatkan representasi string dari instance ini.

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

