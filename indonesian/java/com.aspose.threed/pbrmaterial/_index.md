---
title: PbrMaterial
second_title: Referensi API Aspose.3D untuk Java
description: Material for physically based rendering based on albedo color/metallic/roughness
type: docs
weight: 121
url: /id/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

Material for physically based rendering based on albedo color/metallic/roughness
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | Membuat instance material PBR default |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | Membuat material PBR default dengan nilai warna albedo yang ditentukan. |
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
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | Izinkan mengonversi material lain ke PbrMaterial **Example:** |
| [getAlbedo()](#getAlbedo--) | Mendapatkan warna dasar material |
| [getAlbedoTexture()](#getAlbedoTexture--) | Mendapatkan tekstur untuk albedo |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | Mendapatkan warna emissive |
| [getEmissiveTexture()](#getEmissiveTexture--) | Mendapatkan tekstur untuk emisif |
| [getMetallicFactor()](#getMetallicFactor--) | Mendapatkan tingkat logam material, nilai 1 berarti material tersebut adalah logam dan nilai 0 berarti material tersebut adalah dielektrik. |
| [getMetallicRoughness()](#getMetallicRoughness--) | Mendapatkan tekstur untuk metallic (pada saluran R) dan roughness (pada saluran G) |
| [getName()](#getName--) | Mendapatkan nama. |
| [getNormalTexture()](#getNormalTexture--) | Mendapatkan tekstur pemetaan normal |
| [getOcclusionFactor()](#getOcclusionFactor--) | Mendapatkan faktor ambient occlusion |
| [getOcclusionTexture()](#getOcclusionTexture--) | Mendapatkan tekstur untuk ambient occlusion |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getRoughnessFactor()](#getRoughnessFactor--) | Mendapatkan tingkat kekasaran material, nilai 1 berarti material sangat kasar dan nilai 0 berarti material sangat halus |
| [getSpecularTexture()](#getSpecularTexture--) | Mendapatkan tekstur untuk warna specular |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Mendapatkan tekstur dari slot yang ditentukan, dapat berupa nama properti material atau nama parameter shader |
| [getTransparency()](#getTransparency--) | Mendapatkan faktor transparansi. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Mendapatkan enumerator untuk mengiterasi slot tekstur internal. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | Mengatur warna dasar material |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | Mengatur tekstur untuk albedo |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Mengatur warna emissive |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Mengatur tekstur untuk emisif |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | Mengatur metalness material, nilai 1 berarti material tersebut adalah logam dan nilai 0 berarti material tersebut adalah dielektrik. |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | Mengatur tekstur untuk metallic (pada saluran R) dan roughness (pada saluran G) |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Mengatur tekstur pemetaan normal |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | Mengatur faktor ambient occlusion |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | Mengatur tekstur untuk ambient occlusion |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | Mengatur roughness material, nilai 1 berarti material tersebut sepenuhnya kasar dan nilai 0 berarti material tersebut sepenuhnya halus |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | Mengatur tekstur untuk warna specular |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Mengatur tekstur ke slot yang ditentukan |
| [setTransparency(double value)](#setTransparency-double-) | Mengatur faktor transparansi. |
| [toString()](#toString--) | Memformat objek menjadi string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


Membuat instance material PBR default

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


Membuat material PBR default dengan nilai warna albedo yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | Nilai warna albedo default |

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
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


Izinkan mengonversi material lain ke PbrMaterial **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


Mendapatkan warna dasar material

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


Mendapatkan tekstur untuk albedo

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for albedo
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Mendapatkan warna emissive

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Mendapatkan tekstur untuk emisif

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


Mendapatkan tingkat logam material, nilai 1 berarti material tersebut adalah logam dan nilai 0 berarti material tersebut adalah dielektrik.

**Returns:**
double - metalness material, nilai 1 berarti material tersebut adalah logam dan nilai 0 berarti material tersebut adalah dielektrik.
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


Mendapatkan tekstur untuk metallic (pada saluran R) dan roughness (pada saluran G)

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
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
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


Mendapatkan faktor ambient occlusion

**Returns:**
double - faktor ambient occlusion
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


Mendapatkan tekstur untuk ambient occlusion

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
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
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


Mendapatkan tingkat kekasaran material, nilai 1 berarti material sangat kasar dan nilai 0 berarti material sangat halus

**Returns:**
double - roughness material, nilai 1 berarti material tersebut sepenuhnya kasar dan nilai 0 berarti material tersebut sepenuhnya halus
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


Mendapatkan tekstur untuk warna specular

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
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
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


Mengatur warna dasar material

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


Mengatur tekstur untuk albedo

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nilai baru |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Mengatur warna emissive

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

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


Mengatur metalness material, nilai 1 berarti material tersebut adalah logam dan nilai 0 berarti material tersebut adalah dielektrik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


Mengatur tekstur untuk metallic (pada saluran R) dan roughness (pada saluran G)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nilai baru |

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

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


Mengatur faktor ambient occlusion

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


Mengatur tekstur untuk ambient occlusion

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

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


Mengatur roughness material, nilai 1 berarti material tersebut sepenuhnya kasar dan nilai 0 berarti material tersebut sepenuhnya halus

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


Mengatur tekstur untuk warna specular

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

