---
title: MorphTargetChannel
second_title: Referensi API Aspose.3D untuk Java
description: Sebuah MorphTargetChannel digunakan oleh  untuk mengatur geometri target.
type: docs
weight: 107
url: /id/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

Sebuah MorphTargetChannel digunakan oleh [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) untuk mengatur geometri target. Beberapa format file seperti FBX mendukung beberapa saluran secara paralel. **Remarks:** Berat berada di antara 0 dan 1.0, dan berat default untuk target adalah 0.0;
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
| [MorphTargetChannel()](#MorphTargetChannel--) | Menginisialisasi sebuah instance baru dari kelas [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | Berat default untuk target morf. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Mendapatkan berat untuk geometri yang ditentukan |
| [getChannelWeight()](#getChannelWeight--) | Mendapatkan berat deformer dari saluran ini. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Mendapatkan nama. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getTargets()](#getTargets--) | Mendapatkan semua target yang terkait dengan saluran. |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | Mendapatkan berat untuk target yang ditentukan, jika target tidak termasuk dalam saluran ini, nilai default 0 dikembalikan. |
| [getWeights()](#getWeights--) | Mendapatkan nilai berat penuh dari geometri target. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Mengatur berat untuk geometri yang ditentukan |
| [setChannelWeight(double value)](#setChannelWeight-double-) | Mengatur berat deformer dari saluran ini. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | Mengatur berat untuk target yang ditentukan, nilai default adalah 1, rentang harus antara 0~1 |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | Mengatur berat untuk target yang ditentukan, nilai default adalah 1, rentang harus antara 0~1 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


Menginisialisasi sebuah instance baru dari kelas [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama. |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


Menginisialisasi sebuah instance baru dari kelas [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


Berat default untuk target morf.

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


Mendapatkan berat untuk geometri yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Geometri target. |

**Returns:**
double - Berat
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


Mendapatkan berat deformer dari saluran ini. Berat berada antara 0.0 dan 1.0

**Returns:**
double - berat deformer dari saluran ini. Berat berada antara 0.0 dan 1.0
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


Mendapatkan semua target yang terkait dengan saluran.

**Returns:**
java.util.List<com.aspose.threed.Shape> - semua target yang terkait dengan saluran.
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


Mendapatkan berat untuk target yang ditentukan, jika target tidak termasuk dalam saluran ini, nilai default 0 dikembalikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


Mendapatkan nilai berat penuh dari geometri target.

**Returns:**
java.util.List<java.lang.Double> - nilai berat penuh dari geometri target.
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


Mengatur berat untuk geometri yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Geometri target. |
| nilai | double | Nilai baru |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


Mengatur berat deformer dari saluran ini. Berat berada antara 0.0 dan 1.0

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


Mengatur berat untuk target yang ditentukan, nilai default adalah 1, rentang harus antara 0~1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


Mengatur berat untuk target yang ditentukan, nilai default adalah 1, rentang harus antara 0~1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| berat | double |  |

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

