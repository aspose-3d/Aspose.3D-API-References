---
title: AnimationNode
second_title: Referensi API Aspose.3D untuk Java
description: Aspose.3Ds mendukung hierarki animasi, setiap animasi dapat terdiri dari beberapa animasi dan definisi key-frame animasi.
type: docs
weight: 15
url: /id/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D mendukung hierarki animasi, setiap animasi dapat terdiri dari beberapa animasi dan definisi key-frame animasi. [AnimationNode](../../com.aspose.threed/animationnode) mendefinisikan transformasi nilai properti seiring waktu, misalnya, node animasi dapat digunakan untuk mengontrol transformasi node atau properti numerik objek [A3DObject](../../com.aspose.threed/a3dobject) lainnya.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | Menginisialisasi instance baru dari kelas [AnimationNode](../../com.aspose.threed/animationnode). |
| [AnimationNode()](#AnimationNode--) | Menginisialisasi instance baru dari kelas [AnimationNode](../../com.aspose.threed/animationnode). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Membuat BindPoint berdasarkan tipe data properti. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Menemukan bind point berdasarkan target dan nama. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Mendapatkan bind point animasi pada properti yang diberikan. |
| [getBindPoints()](#getBindPoints--) | Mendapatkan bind point properti saat ini |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Mendapatkan urutan keyframe pada properti yang diberikan. |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | Mendapatkan urutan keyframe pada properti dan saluran yang diberikan. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getSubAnimations()](#getSubAnimations--) | Mendapatkan node sub-animasi di bawah animasi saat ini |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


Menginisialisasi instance baru dari kelas [AnimationNode](../../com.aspose.threed/animationnode).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


Menginisialisasi instance baru dari kelas [AnimationNode](../../com.aspose.threed/animationnode).

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


Membuat BindPoint berdasarkan tipe data properti.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | Objek. |
| propName | java.lang.String | Nama properti. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


Menemukan bind point berdasarkan target dan nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Target titik ikatan yang akan dicari. |
| nama | java.lang.String | Nama titik ikatan yang akan dicari. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


Mendapatkan bind point animasi pada properti yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Pada objek mana untuk membuat titik ikatan. |
| propName | java.lang.String | Nama properti. |
| buat | boolean | Jika disetel ke  true  buat titik ikatan jika belum ada. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


Mendapatkan bind point properti saat ini

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - titik ikatan properti saat ini
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(A3DObject target, String propName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, boolean create)
```


Mendapatkan urutan keyframe pada properti yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Pada instance mana untuk membuat urutan keyframe. |
| propName | java.lang.String | Nama properti. |
| buat | boolean | Jika disetel ke  true , buat urutan jika belum ada. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


Mendapatkan urutan keyframe pada properti dan saluran yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Pada instance mana untuk membuat urutan keyframe. |
| propName | java.lang.String | Nama properti. |
| channelName | java.lang.String | Nama saluran. |
| buat | boolean | Jika disetel ke  true  buat urutan animasi jika belum ada. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


Mendapatkan node sub-animasi di bawah animasi saat ini

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - node sub-animasi di bawah animasi saat ini
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

