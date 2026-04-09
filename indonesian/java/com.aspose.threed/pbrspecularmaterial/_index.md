---
title: PbrSpecularMaterial
second_title: Referensi API Aspose.3D untuk Java
description: Material for physically based rendering based on diffuse color/specular/glossiness
type: docs
weight: 122
url: /id/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

Material for physically based rendering based on diffuse color/specular/glossiness
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | Konstruktor dari [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur ambient. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur diffuse. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur emissive. |
| [MAP_NORMAL](#MAP-NORMAL) | Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur normal. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Digunakan dalam [setTexture](../../com.aspose.threed/material\#setTexture) untuk menetapkan pemetaan tekstur specular. |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | Peta tekstur untuk kilap spekular |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | Mendapatkan warna difus material, nilai default adalah (1, 1, 1) |
| [getDiffuseTexture()](#getDiffuseTexture--) | Mendapatkan tekstur untuk difus |
| [getEmissiveColor()](#getEmissiveColor--) | Mendapatkan warna emisif, nilai default adalah (0, 0, 0) |
| [getEmissiveTexture()](#getEmissiveTexture--) | Mendapatkan tekstur untuk emisif |
| [getGlossinessFactor()](#getGlossinessFactor--) | Mendapatkan glossiness (kehalusan) material, 1 berarti sangat halus dan 0 berarti sangat kasar, nilai default adalah 1, rentang [0, 1] |
| [getName()](#getName--) | Mendapatkan nama. |
| [getNormalTexture()](#getNormalTexture--) | Mendapatkan tekstur pemetaan normal |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getSpecular()](#getSpecular--) | Mendapatkan warna spekular material, nilai default adalah (1, 1, 1). |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | Mendapatkan tekstur untuk warna spekular, saluran RGB menyimpan warna spekular dan saluran A menyimpan glossiness. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Mendapatkan tekstur dari slot yang ditentukan, dapat berupa nama properti material atau nama parameter shader |
| [getTransparency()](#getTransparency--) | Mendapatkan faktor transparansi. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Mendapatkan enumerator untuk mengiterasi slot tekstur internal. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | Mengatur warna difus material, nilai default adalah (1, 1, 1) |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | Mengatur tekstur untuk difus |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Mengatur warna emisif, nilai default adalah (0, 0, 0) |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Mengatur tekstur untuk emisif |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | Mengatur kilap (kehalusan) material, 1 berarti sangat halus dan 0 berarti sangat kasar, nilai default adalah 1, rentang adalah [0, 1] |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Mengatur tekstur pemetaan normal |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | Mengatur warna spekular material, nilai default adalah (1, 1, 1). |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | Mengatur tekstur untuk warna spekular, kanal RGB menyimpan warna spekular dan kanal A menyimpan kilap. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Mengatur tekstur ke slot yang ditentukan |
| [setTransparency(double value)](#setTransparency-double-) | Mengatur faktor transparansi. |
| [toString()](#toString--) | Memformat objek menjadi string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


Konstruktor dari [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial)

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

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


Peta tekstur untuk kilap spekular

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
### getDiffuse() {#getDiffuse--}
```
public Vector3 getDiffuse()
```


Mendapatkan warna difus material, nilai default adalah (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


Mendapatkan tekstur untuk difus

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Mendapatkan warna emisif, nilai default adalah (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Mendapatkan tekstur untuk emisif

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


Mendapatkan glossiness (kehalusan) material, 1 berarti sangat halus dan 0 berarti sangat kasar, nilai default adalah 1, rentang [0, 1]

**Returns:**
double - kilap (kehalusan) material, 1 berarti sangat halus dan 0 berarti sangat kasar, nilai default adalah 1, rentang adalah [0, 1]
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


Mendapatkan tekstur pemetaan normal

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
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
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


Mendapatkan warna spekular material, nilai default adalah (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


Mendapatkan tekstur untuk warna spekular, saluran RGB menyimpan warna spekular dan saluran A menyimpan glossiness.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
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
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


Mengatur warna difus material, nilai default adalah (1, 1, 1)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


Mengatur tekstur untuk difus

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nilai baru |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Mengatur warna emisif, nilai default adalah (0, 0, 0)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


Mengatur tekstur untuk emisif

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nilai baru |

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


Mengatur kilap (kehalusan) material, 1 berarti sangat halus dan 0 berarti sangat kasar, nilai default adalah 1, rentang adalah [0, 1]

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

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


Mengatur tekstur pemetaan normal

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nilai baru |

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

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


Mengatur warna spekular material, nilai default adalah (1, 1, 1).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


Mengatur tekstur untuk warna spekular, kanal RGB menyimpan warna spekular dan kanal A menyimpan kilap.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nilai baru |

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

