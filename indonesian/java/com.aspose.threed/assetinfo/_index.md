---
title: AssetInfo
second_title: Referensi API Aspose.3D untuk Java
description: Informasi aset.
type: docs
weight: 17
url: /id/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

Informasi aset. Informasi aset dapat dilampirkan ke [Scene](../../com.aspose.threed/scene). Anak [Scene](../../com.aspose.threed/scene) dapat memiliki [AssetInfo](../../com.aspose.threed/assetinfo) miliknya sendiri untuk mengganti definisi orang tua. **Example:** Kode berikut menunjukkan cara membaca info aset dari file fbx:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | Menginisialisasi instance baru dari kelas [AssetInfo](../../com.aspose.threed/assetinfo). |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | Menginisialisasi instance baru dari kelas [AssetInfo](../../com.aspose.threed/assetinfo). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getAmbient()](#getAmbient--) | Mendapatkan atau Mengatur warna ambient default dari aset ini |
| [getApplicationName()](#getApplicationName--) | Mendapatkan aplikasi yang membuat aset ini |
| [getApplicationVendor()](#getApplicationVendor--) | Mendapatkan nama vendor aplikasi |
| [getApplicationVersion()](#getApplicationVersion--) | Mendapatkan versi aplikasi yang membuat aset ini. |
| [getAuthor()](#getAuthor--) | Mendapatkan penulis aset ini |
| [getAxisSystem()](#getAxisSystem--) | Mendapatkan sistem koordinat/vektor atas/vektor depan dari info aset. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Mendapatkan komentar aset ini. |
| [getCoordinateSystem()](#getCoordinateSystem--) | Mendapatkan sistem koordinat yang digunakan dalam aset ini. |
| [getCopyright()](#getCopyright--) | Mendapatkan hak cipta dokumen |
| [getCreationTime()](#getCreationTime--) | Mendapatkan atau Mengatur waktu pembuatan aset ini |
| [getFrontVector()](#getFrontVector--) | Mendapatkan vektor depan yang digunakan dalam aset ini. |
| [getKeywords()](#getKeywords--) | Mendapatkan kata kunci aset ini |
| [getModificationTime()](#getModificationTime--) | Mendapatkan atau Mengatur waktu modifikasi aset ini |
| [getName()](#getName--) | Mendapatkan nama. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getRevision()](#getRevision--) | Mendapatkan nomor revisi aset ini, biasanya digunakan dalam sistem kontrol versi. |
| [getSubject()](#getSubject--) | Mendapatkan subjek aset ini |
| [getTitle()](#getTitle--) | Mendapatkan judul aset ini |
| [getUnitName()](#getUnitName--) | Mendapatkan satuan panjang yang digunakan dalam aset ini. |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | Mendapatkan faktor skala ke meter dunia nyata. |
| [getUpVector()](#getUpVector--) | Mendapatkan vektor atas yang digunakan dalam aset ini. |
| [getUrl()](#getUrl--) | Mendapatkan atau Mengatur URL aset ini. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | Mendapatkan atau Mengatur warna ambient default dari aset ini |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | Mengatur aplikasi yang membuat aset ini |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | Mengatur nama vendor aplikasi |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | Mengatur versi aplikasi yang membuat aset ini. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Mengatur penulis aset ini |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Mengatur sistem koordinat/vektor atas/vektor depan dari informasi aset. |
| [setComment(String value)](#setComment-java.lang.String-) | Mengatur komentar aset ini. |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | Mengatur sistem koordinat yang digunakan dalam aset ini. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Mengatur hak cipta dokumen |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | Mendapatkan atau Mengatur waktu pembuatan aset ini |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | Mengatur vektor depan yang digunakan dalam aset ini. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Mengatur kata kunci aset ini |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | Mendapatkan atau Mengatur waktu modifikasi aset ini |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setRevision(String value)](#setRevision-java.lang.String-) | Mengatur nomor revisi aset ini, biasanya digunakan dalam sistem kontrol versi. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Mengatur subjek aset ini |
| [setTitle(String value)](#setTitle-java.lang.String-) | Mengatur judul aset ini |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | Mengatur satuan panjang yang digunakan dalam aset ini. |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | Mengatur faktor skala ke meter dunia nyata. |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | Mengatur vektor atas yang digunakan dalam aset ini. |
| [setUrl(String value)](#setUrl-java.lang.String-) | Mendapatkan atau Mengatur URL aset ini. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


Menginisialisasi instance baru dari kelas [AssetInfo](../../com.aspose.threed/assetinfo).

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


Menginisialisasi instance baru dari kelas [AssetInfo](../../com.aspose.threed/assetinfo).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama |

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
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


Mendapatkan atau Mengatur warna ambient default dari aset ini

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


Mendapatkan aplikasi yang membuat aset ini

**Returns:**
java.lang.String - aplikasi yang membuat aset ini
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


Mendapatkan nama vendor aplikasi

**Returns:**
java.lang.String - nama vendor aplikasi
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


Mendapatkan versi aplikasi yang membuat aset ini.

**Returns:**
java.lang.String - versi aplikasi yang membuat aset ini.
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Mendapatkan penulis aset ini

**Returns:**
java.lang.String - penulis aset ini
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Mendapatkan sistem koordinat/vektor atas/vektor depan dari info aset.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the coordinate system/up vector/front vector of the asset info.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public String getComment()
```


Mendapatkan komentar aset ini.

**Returns:**
java.lang.String - komentar aset ini.
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


Mendapatkan sistem koordinat yang digunakan dalam aset ini.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Mendapatkan hak cipta dokumen

**Returns:**
java.lang.String - hak cipta dokumen
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


Mendapatkan atau Mengatur waktu pembuatan aset ini

**Returns:**
java.util.Calendar - atau Mengatur waktu pembuatan aset ini
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


Mendapatkan vektor depan yang digunakan dalam aset ini.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Mendapatkan kata kunci aset ini

**Returns:**
java.lang.String - kata kunci aset ini
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


Mendapatkan atau Mengatur waktu modifikasi aset ini

**Returns:**
java.util.Calendar - atau Mengatur waktu modifikasi aset ini
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
### getRevision() {#getRevision--}
```
public String getRevision()
```


Mendapatkan nomor revisi aset ini, biasanya digunakan dalam sistem kontrol versi.

**Returns:**
java.lang.String - nomor revisi aset ini, biasanya digunakan dalam sistem kontrol versi.
### getSubject() {#getSubject--}
```
public String getSubject()
```


Mendapatkan subjek aset ini

**Returns:**
java.lang.String - subjek aset ini
### getTitle() {#getTitle--}
```
public String getTitle()
```


Mendapatkan judul aset ini

**Returns:**
java.lang.String - judul aset ini
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


Mendapatkan satuan panjang yang digunakan dalam aset ini. misalnya cm/m/km/inci/kaki

**Returns:**
java.lang.String - satuan panjang yang digunakan dalam aset ini. misalnya cm/m/km/inci/kaki
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


Mendapatkan faktor skala ke meter dunia nyata.

**Returns:**
double - faktor skala ke meter dunia nyata. **Remarks:** Ini diabaikan selama serialisasi jika nama satuan bernilai null.
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


Mendapatkan vektor atas yang digunakan dalam aset ini.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


Mendapatkan atau Mengatur URL aset ini.

**Returns:**
java.lang.String - atau Mengatur URL aset ini.
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
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


Mendapatkan atau Mengatur warna ambient default dari aset ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | Nilai baru |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


Mengatur aplikasi yang membuat aset ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


Mengatur nama vendor aplikasi

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


Mengatur versi aplikasi yang membuat aset ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Mengatur penulis aset ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Mengatur sistem koordinat/vektor atas/vektor depan dari informasi aset.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Nilai baru |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Mengatur komentar aset ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


Mengatur sistem koordinat yang digunakan dalam aset ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Nilai baru |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Mengatur hak cipta dokumen

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


Mendapatkan atau Mengatur waktu pembuatan aset ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Calendar | Nilai baru |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


Mengatur vektor depan yang digunakan dalam aset ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Nilai baru |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Mengatur kata kunci aset ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


Mendapatkan atau Mengatur waktu modifikasi aset ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Calendar | Nilai baru |

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

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


Mengatur nomor revisi aset ini, biasanya digunakan dalam sistem kontrol versi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Mengatur subjek aset ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Mengatur judul aset ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


Mengatur satuan panjang yang digunakan dalam aset ini. misalnya cm/m/km/inci/kaki

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


Mengatur faktor skala ke meter dunia nyata.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru **Remarks:** Ini diabaikan selama serialisasi jika nama satuan bernilai null. |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


Mengatur vektor atas yang digunakan dalam aset ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Nilai baru |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


Mendapatkan atau Mengatur URL aset ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

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

