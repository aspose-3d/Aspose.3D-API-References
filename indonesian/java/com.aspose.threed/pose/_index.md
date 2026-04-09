---
title: Pose
second_title: Referensi API Aspose.3D untuk Java
description: Pose digunakan untuk menyimpan matriks transformasi ketika geometri di‑skin.
type: docs
weight: 135
url: /id/java/com.aspose.threed/pose/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Pose extends A3DObject
```

Pose digunakan untuk menyimpan matriks transformasi ketika geometri di‑skin. Pose adalah sekumpulan [BonePose](../../com.aspose.threed/bonepose), setiap [BonePose](../../com.aspose.threed/bonepose) menyimpan informasi transformasi konkret dari node tulang.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Pose(String name)](#Pose-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [Pose](../../com.aspose.threed/pose). |
| [Pose()](#Pose--) | Menginisialisasi sebuah instance baru dari kelas [Pose](../../com.aspose.threed/pose). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addBonePose(Node node, Matrix4 matrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | Menyimpan matriks transformasi pose untuk node tulang yang diberikan. |
| [addBonePose(Node node, Matrix4 matrix, boolean localMatrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-) | Menyimpan matriks transformasi pose untuk node tulang yang diberikan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getBonePoses()](#getBonePoses--) | Mendapatkan semua [BonePose](../../com.aspose.threed/bonepose). |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Mendapatkan nama. |
| [getPoseType()](#getPoseType--) | Mendapatkan tipe pose. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setPoseType(PoseType value)](#setPoseType-com.aspose.threed.PoseType-) | Mengatur tipe pose. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pose(String name) {#Pose-java.lang.String-}
```
public Pose(String name)
```


Menginisialisasi sebuah instance baru dari kelas [Pose](../../com.aspose.threed/pose).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama |

### Pose() {#Pose--}
```
public Pose()
```


Menginisialisasi sebuah instance baru dari kelas [Pose](../../com.aspose.threed/pose).

### addBonePose(Node node, Matrix4 matrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public void addBonePose(Node node, Matrix4 matrix)
```


Menyimpan matriks transformasi pose untuk node tulang yang diberikan. Matriks transformasi global diasumsikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Node Tulang. |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | Matriks transformasi. |

### addBonePose(Node node, Matrix4 matrix, boolean localMatrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-}
```
public void addBonePose(Node node, Matrix4 matrix, boolean localMatrix)
```


Menyimpan matriks transformasi pose untuk node tulang yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Node Tulang. |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | Matriks transformasi. |
| localMatrix | boolean | Jika diatur ke true berarti menggunakan matriks lokal, jika tidak berarti matriks global. |

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
### getBonePoses() {#getBonePoses--}
```
public List<BonePose> getBonePoses()
```


Mendapatkan semua [BonePose](../../com.aspose.threed/bonepose).

**Returns:**
java.util.List<com.aspose.threed.BonePose> - semua [BonePose](../../com.aspose.threed/bonepose).
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getPoseType() {#getPoseType--}
```
public PoseType getPoseType()
```


Mendapatkan tipe pose.

**Returns:**
[PoseType](../../com.aspose.threed/posetype) - the type of the pose.
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
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengatur nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setPoseType(PoseType value) {#setPoseType-com.aspose.threed.PoseType-}
```
public void setPoseType(PoseType value)
```


Mengatur tipe pose.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PoseType](../../com.aspose.threed/posetype) | Nilai baru |

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

