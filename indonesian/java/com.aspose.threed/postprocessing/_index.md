---
title: PostProcessing
second_title: Referensi API Aspose.3D untuk Java
description: Efek pasca‑pemrosesan
type: docs
weight: 136
url: /id/java/com.aspose.threed/postprocessing/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public abstract class PostProcessing extends A3DObject
```

Efek pasca‑pemrosesan
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PostProcessing()](#PostProcessing--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getClass()](#getClass--) |  |
| [getInput()](#getInput--) | Masukan dari pemrosesan lanjutan ini |
| [getName()](#getName--) | Mendapatkan nama. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setInput(ITextureUnit value)](#setInput-com.aspose.threed.ITextureUnit-) | Masukan dari pemrosesan lanjutan ini |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PostProcessing() {#PostProcessing--}
```
public PostProcessing()
```


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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Menemukan properti. Itu dapat menjadi properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti asli (Diidentifikasi dengan namanya)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyName | java.lang.String | Nama properti. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInput() {#getInput--}
```
public abstract ITextureUnit getInput()
```


Masukan dari pemrosesan lanjutan ini

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Input of this post-processing
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Mendapatkan koleksi semua properti.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Dapatkan nilai properti yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Nama properti |

**Returns:**
java.lang.Object - Nilai dari properti yang ditemukan
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




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Menghapus properti dinamis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Properti mana yang akan dihapus |

**Returns:**
boolean - true jika properti berhasil dihapus
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Hapus properti yang ditentukan yang diidentifikasi dengan nama

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Properti mana yang akan dihapus |

**Returns:**
boolean - true jika properti berhasil dihapus
### setInput(ITextureUnit value) {#setInput-com.aspose.threed.ITextureUnit-}
```
public abstract void setInput(ITextureUnit value)
```


Masukan dari pemrosesan lanjutan ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | Nilai baru |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengatur nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Mengatur nilai properti yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Nama properti |
| nilai | java.lang.Object | Nilai properti |

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

