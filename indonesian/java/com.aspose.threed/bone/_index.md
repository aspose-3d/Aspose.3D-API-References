---
title: Tulang
second_title: Referensi API Aspose.3D untuk Java
description: Sebuah tulang mendefinisikan subset titik kontrol geometri dan mendefinisikan bobot campuran untuk setiap titik kontrol.
type: docs
weight: 20
url: /id/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

Sebuah tulang mendefinisikan subset titik kontrol geometri, dan mendefinisikan bobot campuran untuk setiap titik kontrol. Objek [Bone](../../com.aspose.threed/bone) tidak dapat digunakan secara langsung, sebuah instance [SkinDeformer](../../com.aspose.threed/skindeformer) digunakan untuk mendistorsi geometri, dan [SkinDeformer](../../com.aspose.threed/skindeformer) dilengkapi dengan sekumpulan tulang, masing‑masing tulang terhubung ke sebuah node. CATATAN: Sebuah titik kontrol dari sebuah geometri dapat terikat ke lebih dari satu Tulang.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [Bone](../../com.aspose.threed/bone). |
| [Bone()](#Bone--) | Menginisialisasi sebuah instance baru dari kelas [Bone](../../com.aspose.threed/bone). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [get(int index)](#get-int-) | Mendapatkan bobot campuran dari titik kontrol yang ditentukan |
| [getBoneTransform()](#getBoneTransform--) | Mendapatkan matriks transformasi dari tulang. |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | Mode tautan tulang mengacu pada cara tulang terhubung atau ditautkan ke tulang induknya dalam struktur hierarkis. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getNode()](#getNode--) | Mendapatkan node. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getTransform()](#getTransform--) | Mendapatkan matriks transformasi dari node yang berisi tulang. |
| [getWeight(int index)](#getWeight-int-) | Mendapatkan berat untuk titik kontrol yang ditentukan oleh indeks |
| [getWeightCount()](#getWeightCount--) | Mendapatkan jumlah berat, ini secara otomatis diperluas oleh [setWeight](../../com.aspose.threed/bone\#setWeight) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [set(int index, double value)](#set-int-double-) | Mengatur berat blend dari titik kontrol yang ditentukan |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | Mengatur matriks transformasi tulang. |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | Mode tautan tulang mengacu pada cara tulang terhubung atau ditautkan ke tulang induknya dalam struktur hierarkis. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Mengatur node. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | Mengatur matriks transformasi dari node yang berisi tulang. |
| [setWeight(int index, double weight)](#setWeight-int-double-) | Mengatur berat untuk titik kontrol yang ditentukan oleh indeks |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


Menginisialisasi sebuah instance baru dari kelas [Bone](../../com.aspose.threed/bone).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama. |

### Bone() {#Bone--}
```
public Bone()
```


Menginisialisasi sebuah instance baru dari kelas [Bone](../../com.aspose.threed/bone).

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
### get(int index) {#get-int-}
```
public double get(int index)
```


Mendapatkan bobot campuran dari titik kontrol yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks berat |

**Returns:**
double - Berat
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


Mendapatkan matriks transformasi dari tulang.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the bone.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLinkMode() {#getLinkMode--}
```
public BoneLinkMode getLinkMode()
```


Mode tautan tulang mengacu pada cara tulang terhubung atau ditautkan ke tulang induknya dalam struktur hierarkis.

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getNode() {#getNode--}
```
public Node getNode()
```


Mendapatkan node. Node tulang adalah tulang yang terhubung dengan kulit, [SkinDeformer](../../com.aspose.threed/skindeformer) akan menggunakan node tulang untuk memengaruhi perpindahan titik kontrol. Node tulang biasanya memiliki [Skeleton](../../com.aspose.threed/skeleton) yang terpasang, tetapi tidak wajib. [Skeleton](../../com.aspose.threed/skeleton) yang terpasang biasanya digunakan oleh perangkat lunak DCC untuk menampilkan kerangka kepada pengguna.

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


Mendapatkan matriks transformasi dari node yang berisi tulang.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


Mendapatkan berat untuk titik kontrol yang ditentukan oleh indeks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks titik kontrol |

**Returns:**
double - berat pada indeks yang ditentukan, atau 0 jika indeks tidak valid
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


Mendapatkan jumlah berat, ini secara otomatis diperluas oleh [setWeight](../../com.aspose.threed/bone\#setWeight)

**Returns:**
int - jumlah berat, ini secara otomatis diperluas oleh [setWeight](../../com.aspose.threed/bone\#setWeight)
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


Mengatur berat blend dari titik kontrol yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks berat |
| nilai | double | Nilai baru |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


Mengatur matriks transformasi tulang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nilai baru |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


Mode tautan tulang mengacu pada cara tulang terhubung atau ditautkan ke tulang induknya dalam struktur hierarkis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | Nilai baru |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengatur nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Mengatur node. Node tulang adalah tulang yang terhubung dengan kulit, [SkinDeformer](../../com.aspose.threed/skindeformer) akan menggunakan node tulang untuk memengaruhi perpindahan titik kontrol. Node tulang biasanya memiliki [Skeleton](../../com.aspose.threed/skeleton) yang terpasang, tetapi tidak wajib. [Skeleton](../../com.aspose.threed/skeleton) yang terpasang biasanya digunakan oleh perangkat lunak DCC untuk menampilkan kerangka kepada pengguna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nilai baru |

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


Mengatur matriks transformasi dari node yang berisi tulang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nilai baru |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


Mengatur berat untuk titik kontrol yang ditentukan oleh indeks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks titik kontrol |
| berat | double | Berat baru |

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

