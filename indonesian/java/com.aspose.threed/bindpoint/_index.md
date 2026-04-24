---
title: BindPoint
second_title: Referensi API Aspose.3D untuk Java
description: Sebuah  biasanya dibuat pada properti objek, beberapa tipe properti berisi beberapa bidang komponen (seperti bidang Vector3) akan menghasilkan saluran untuk setiap bidang komponen dan menghubungkan bidang tersebut ke satu atau lebih instance urutan keyframe melalui saluran.
type: docs
weight: 19
url: /id/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

Sebuah [BindPoint](../../com.aspose.threed/bindpoint) biasanya dibuat pada properti objek, beberapa tipe properti berisi beberapa bidang komponen (seperti bidang Vector3), [BindPoint](../../com.aspose.threed/bindpoint) akan menghasilkan saluran untuk setiap bidang komponen dan menghubungkan bidang tersebut ke satu atau lebih instance urutan keyframe melalui saluran.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | Menginisialisasi instance baru dari kelas [BindPoint](../../com.aspose.threed/bindpoint). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | Menambahkan properti saluran yang ditentukan. |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | Menambahkan properti saluran yang ditentukan. |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | Mengikat urutan keyframe ke saluran yang ditentukan |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | Membuat kurva baru dan menghubungkannya ke saluran pertama dari pemetaan kurva |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [get(String channelName)](#get-java.lang.String-) | Mendapatkan saluran berdasarkan nama yang diberikan |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | Mendapatkan saluran berdasarkan nama yang diberikan |
| [getChannelsCount()](#getChannelsCount--) | Mendapatkan total jumlah saluran properti yang didefinisikan dalam pemetaan kurva animasi ini. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | Mendapatkan urutan keyframe pertama dalam saluran yang ditentukan |
| [getName()](#getName--) | Mendapatkan nama. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty()](#getProperty--) | Mendapatkan properti yang terkait dengan CurveMapping |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [resetChannels()](#resetChannels--) | Mengosongkan saluran properti dari pemetaan kurva animasi ini. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | Mendapatkan properti yang terkait dengan CurveMapping |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [toString()](#toString--) | Memformat objek menjadi string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


Menginisialisasi instance baru dari kelas [BindPoint](../../com.aspose.threed/bindpoint).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Adegan yang berisi animasi. |
| prop | [Property](../../com.aspose.threed/property) | Properti. |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


Menambahkan properti saluran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama. |
| type | java.lang.Class<?> | Tipe. |
| nilai | java.lang.Object | Nilai. |

**Returns:**
boolean - true, jika saluran ditambahkan, false jika tidak.
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


Menambahkan properti saluran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama. |
| nilai | java.lang.Object | Nilai. |

**Returns:**
boolean - true, jika saluran ditambahkan, false jika tidak.
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


Mengikat urutan keyframe ke saluran yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelName | java.lang.String | Saluran mana yang akan diikat oleh urutan keyframe |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Urutan keyframe yang akan diikat |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


Membuat kurva baru dan menghubungkannya ke saluran pertama dari pemetaan kurva

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama urutan baru. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


Mendapatkan saluran berdasarkan nama yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelName | java.lang.String | Nama saluran |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


Mendapatkan saluran berdasarkan nama yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelName | java.lang.String | Nama saluran yang akan dicari |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Mendapatkan total jumlah saluran properti yang didefinisikan dalam pemetaan kurva animasi ini.

**Returns:**
int - Jumlah saluran.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(String channelName) {#getKeyframeSequence-java.lang.String-}
```
public KeyframeSequence getKeyframeSequence(String channelName)
```


Mendapatkan urutan keyframe pertama dalam saluran yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelName | java.lang.String | Nama saluran yang akan dicari |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
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
### getProperty() {#getProperty--}
```
public Property getProperty()
```


Mendapatkan properti yang terkait dengan CurveMapping

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
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
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


Mengosongkan saluran properti dari pemetaan kurva animasi ini.

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengatur nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


Mendapatkan properti yang terkait dengan CurveMapping

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | Nilai baru |

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


Memformat objek menjadi string

**Returns:**
java.lang.String - String objek
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

