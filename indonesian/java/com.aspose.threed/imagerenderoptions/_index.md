---
title: ImageRenderOptions
second_title: Referensi API Aspose.3D untuk Java
description: Opsi untuk  dan
type: docs
weight: 83
url: /id/java/com.aspose.threed/imagerenderoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class ImageRenderOptions extends A3DObject
```

Opsi untuk [Scene](../../com.aspose.threed/scene) dan [Scene](../../com.aspose.threed/scene)
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageRenderOptions()](#ImageRenderOptions--) | Inisialisasi sebuah instance dari [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getAssetDirectories()](#getAssetDirectories--) | Direktori yang menyimpan aset eksternal (seperti tekstur) |
| [getBackgroundColor()](#getBackgroundColor--) | Warna latar belakang dari hasil render. |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Mendapatkan apakah harus merender bayangan. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setAssetDirectories(ArrayList<String> value)](#setAssetDirectories-java.util.ArrayList-java.lang.String--) | Direktori yang menyimpan aset eksternal (seperti tekstur) |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | Warna latar belakang dari hasil render. |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Mengatur apakah harus merender bayangan. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageRenderOptions() {#ImageRenderOptions--}
```
public ImageRenderOptions()
```


Inisialisasi sebuah instance dari [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions)

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
### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Direktori yang menyimpan aset eksternal (seperti tekstur)

**Returns:**
java.util.ArrayList<java.lang.String> - Direktori yang menyimpan aset eksternal (seperti tekstur)
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


Warna latar belakang dari hasil render.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The background color of the render result.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableShadows() {#getEnableShadows--}
```
public boolean getEnableShadows()
```


Mendapatkan apakah harus merender bayangan.

**Returns:**
boolean - apakah harus merender bayangan.
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
### setAssetDirectories(ArrayList<String> value) {#setAssetDirectories-java.util.ArrayList-java.lang.String--}
```
public void setAssetDirectories(ArrayList<String> value)
```


Direktori yang menyimpan aset eksternal (seperti tekstur)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.ArrayList<java.lang.String> | Nilai baru |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


Warna latar belakang dari hasil render.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Mengatur apakah harus merender bayangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

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

