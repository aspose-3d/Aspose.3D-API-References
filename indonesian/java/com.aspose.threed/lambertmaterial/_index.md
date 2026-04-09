---
title: LambertMaterial
second_title: Referensi API Aspose.3D untuk Java
description: Material untuk model shading Lambert
type: docs
weight: 92
url: /id/java/com.aspose.threed/lambertmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class LambertMaterial extends Material
```

Material untuk model shading Lambert
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LambertMaterial()](#LambertMaterial--) | Menginisialisasi sebuah instance baru dari kelas [LambertMaterial](../../com.aspose.threed/lambertmaterial). |
| [LambertMaterial(String name)](#LambertMaterial-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [LambertMaterial](../../com.aspose.threed/lambertmaterial). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur ambient. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur diffuse. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur emissive. |
| [MAP_NORMAL](#MAP-NORMAL) | Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur normal. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur specular. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getAmbientColor()](#getAmbientColor--) | Mendapatkan warna ambient |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | Mendapatkan warna diffuse |
| [getEmissiveColor()](#getEmissiveColor--) | Mendapatkan warna emissive |
| [getName()](#getName--) | Mendapatkan nama. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Mendapatkan tekstur dari slot yang ditentukan, dapat berupa nama properti material atau nama parameter shader |
| [getTransparency()](#getTransparency--) | Mendapatkan faktor transparansi. |
| [getTransparentColor()](#getTransparentColor--) | Mendapatkan warna transparan. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Mendapatkan enumerator untuk mengiterasi slot tekstur internal. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | Mengatur warna ambient |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | Mengatur warna diffuse |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Mengatur warna emissive |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Mengatur tekstur ke slot yang ditentukan |
| [setTransparency(double value)](#setTransparency-double-) | Mengatur faktor transparansi. |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | Mengatur warna transparan. |
| [toString()](#toString--) | Memformat objek menjadi string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LambertMaterial() {#LambertMaterial--}
```
public LambertMaterial()
```


Menginisialisasi sebuah instance baru dari kelas [LambertMaterial](../../com.aspose.threed/lambertmaterial).

### LambertMaterial(String name) {#LambertMaterial-java.lang.String-}
```
public LambertMaterial(String name)
```


Menginisialisasi sebuah instance baru dari kelas [LambertMaterial](../../com.aspose.threed/lambertmaterial).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama |

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur ambient.

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur diffuse.

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur emissive.

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur normal.

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur specular.

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
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


Mendapatkan warna ambient

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the ambient color
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuseColor() {#getDiffuseColor--}
```
public Vector3 getDiffuseColor()
```


Mendapatkan warna diffuse

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Mendapatkan warna emissive

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color **Example:**

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
```
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
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


Mendapatkan tekstur dari slot yang ditentukan, dapat berupa nama properti material atau nama parameter shader

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slotName | java.lang.String | Nama slot. |

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - The texture. **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     tex = (Texture)mat.getTexture(Material.MAP_DIFFUSE);
```
### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Mendapatkan faktor transparansi. Faktor harus berada dalam rentang antara 0 (0%, sepenuhnya tidak tembus) dan 1 (100%, sepenuhnya tembus). Nilai faktor yang tidak valid akan dipotong.

**Returns:**
double - faktor transparansi. Faktor harus berada dalam rentang antara 0 (0%, sepenuhnya tidak tembus) dan 1 (100%, sepenuhnya tembus). Nilai faktor yang tidak valid akan dipotong.
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


Mendapatkan warna transparan.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the transparent color.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<TextureSlot> iterator()
```


Mendapatkan enumerator untuk mengiterasi slot tekstur internal.

**Returns:**
java.util.Iterator<com.aspose.threed.TextureSlot>
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
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


Mengatur warna ambient

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


Mengatur warna diffuse

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Mengatur warna emissive

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru **Example:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

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

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


Mengatur tekstur ke slot yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slotName | java.lang.String | Nama slot. |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | Tekstur. **Example:** |

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_NORMAL, tex);
``` |

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Mengatur faktor transparansi. Faktor harus berada dalam rentang antara 0 (0%, sepenuhnya tidak tembus) dan 1 (100%, sepenuhnya tembus). Nilai faktor yang tidak valid akan dipotong.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


Mengatur warna transparan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

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

