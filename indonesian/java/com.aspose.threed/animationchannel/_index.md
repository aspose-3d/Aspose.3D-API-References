---
title: AnimationChannel
second_title: Referensi API Aspose.3D untuk Java
description: Sebuah saluran memetakan bidang komponen properti ke sekumpulan urutan keyframe
type: docs
weight: 13
url: /id/java/com.aspose.threed/animationchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.KeyframeSequence](../../com.aspose.threed/keyframesequence)
```
public class AnimationChannel extends KeyframeSequence
```

Sebuah saluran memetakan bidang komponen properti ke sekumpulan urutan keyframe.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | Buat key frame baru dengan nilai yang ditentukan |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | Buat key frame baru dengan nilai yang ditentukan |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getBindPoint()](#getBindPoint--) | Mendapatkan titik pengikatan properti yang memiliki kurva ini |
| [getClass()](#getClass--) |  |
| [getComponentType()](#getComponentType--) | Mendapatkan tipe bidang komponen |
| [getDefaultValue()](#getDefaultValue--) | Mendapatkan nilai Default saluran. |
| [getKeyFrames()](#getKeyFrames--) | Mendapatkan key frame dari kurva ini. |
| [getKeyframeSequence()](#getKeyframeSequence--) | Mendapatkan urutan keyframe terkait di dalam saluran ini |
| [getName()](#getName--) | Mendapatkan nama. |
| [getPostBehavior()](#getPostBehavior--) | Mendapatkan perilaku pasca yang menunjukkan nilai yang disampel seharusnya setelah key frame terakhir. |
| [getPreBehavior()](#getPreBehavior--) | Mendapatkan perilaku pra yang menunjukkan nilai yang disampel seharusnya sebelum key pertama. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Mendapatkan enumerator untuk menelusuri semua key frame. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [reset()](#reset--) | Menghapus semua key frame dan mengatur ulang perilaku pasca/ pra. |
| [setDefaultValue(Object value)](#setDefaultValue-java.lang.Object-) | Mengatur nilai Default saluran. |
| [setKeyframeSequence(KeyframeSequence value)](#setKeyframeSequence-com.aspose.threed.KeyframeSequence-) | Mendapatkan urutan keyframe terkait di dalam saluran ini |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


Buat key frame baru dengan nilai yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| waktu | double | Posisi waktu (diukur dalam detik) |
| nilai | float | Nilai pada posisi waktu ini |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


Buat key frame baru dengan nilai yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| waktu | double | Posisi waktu (diukur dalam detik) |
| nilai | float | Nilai pada posisi waktu ini |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | Tipe interpolasi dari key frame ini |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


Mendapatkan titik pengikatan properti yang memiliki kurva ini

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - the property bind point which owns this curve
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComponentType() {#getComponentType--}
```
public Class<?> getComponentType()
```


Mendapatkan tipe bidang komponen

**Returns:**
java.lang.Class<?> - tipe bidang komponen
### getDefaultValue() {#getDefaultValue--}
```
public Object getDefaultValue()
```


Mendapatkan nilai Default saluran. Jika sebuah saluran tidak memiliki urutan keyframe yang terhubung, nilai default akan digunakan selama evaluasi animasi. Contoh nyata: Animasi hanya menggerakkan koordinat x sebuah node, sementara y dan z tidak berubah, maka nilai default akan digunakan selama evaluasi translasi penuh.

**Returns:**
java.lang.Object - nilai Default saluran. Jika sebuah saluran tidak memiliki urutan keyframe yang terhubung, nilai default akan digunakan selama evaluasi animasi. Contoh nyata: Animasi hanya menggerakkan koordinat x sebuah node, sementara y dan z tidak berubah, maka nilai default akan digunakan selama evaluasi translasi penuh.
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


Mendapatkan key frame dari kurva ini.

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - key frame dari kurva ini.
### getKeyframeSequence() {#getKeyframeSequence--}
```
public KeyframeSequence getKeyframeSequence()
```


Mendapatkan urutan keyframe terkait di dalam saluran ini

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - associated keyframe sequence inside this channel
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


Mendapatkan perilaku pasca yang menunjukkan nilai yang disampel seharusnya setelah key frame terakhir.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


Mendapatkan perilaku pra yang menunjukkan nilai yang disampel seharusnya sebelum key pertama.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


Mendapatkan enumerator untuk menelusuri semua key frame.

**Returns:**
java.util.Iterator<com.aspose.threed.KeyFrame>
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
### reset() {#reset--}
```
public void reset()
```


Menghapus semua key frame dan mengatur ulang perilaku pasca/ pra.

### setDefaultValue(Object value) {#setDefaultValue-java.lang.Object-}
```
public void setDefaultValue(Object value)
```


Mengatur nilai Default saluran. Jika sebuah saluran tidak memiliki urutan keyframe yang terhubung, nilai default akan digunakan selama evaluasi animasi. Contoh nyata: Animasi hanya menggerakkan koordinat x sebuah node, sementara y dan z tidak berubah, maka nilai default akan digunakan selama evaluasi translasi penuh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object | Nilai baru |

### setKeyframeSequence(KeyframeSequence value) {#setKeyframeSequence-com.aspose.threed.KeyframeSequence-}
```
public void setKeyframeSequence(KeyframeSequence value)
```


Mendapatkan urutan keyframe terkait di dalam saluran ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Nilai baru |

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

