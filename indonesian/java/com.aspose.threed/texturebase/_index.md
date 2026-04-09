---
title: TextureBase
second_title: Referensi API Aspose.3D untuk Java
description: Kelas dasar untuk semua tekstur konkret.
type: docs
weight: 185
url: /id/java/com.aspose.threed/texturebase/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureBase extends A3DObject
```

Kelas dasar untuk semua tekstur konkret. Texture mendefinisikan tampilan dan nuansa permukaan geometri.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextureBase(String name)](#TextureBase-java.lang.String-) | Menginisialisasi instance baru dari kelas [TextureBase](../../com.aspose.threed/texturebase). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getAlpha()](#getAlpha--) | Mendapatkan nilai alfa default dari tekstur. Ini berlaku ketika [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) adalah [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Nilai default adalah 1.0, rentang nilai yang valid antara 0 dan 1. |
| [getAlphaSource()](#getAlphaSource--) | Mendapatkan apakah tekstur mendefinisikan saluran alfa. |
| [getClass()](#getClass--) |  |
| [getMagFilter()](#getMagFilter--) | Mendapatkan filter untuk pembesaran. |
| [getMinFilter()](#getMinFilter--) | Mendapatkan filter untuk pengecilan. |
| [getMipFilter()](#getMipFilter--) | Mendapatkan filter untuk sampling tingkat mip. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getUVRotation()](#getUVRotation--) | Mendapatkan rotasi tekstur. |
| [getUVScale()](#getUVScale--) | Mendapatkan skala UV. |
| [getUVTranslation()](#getUVTranslation--) | Mendapatkan translasi UV. |
| [getWrapModeU()](#getWrapModeU--) | Mendapatkan mode pembungkus tekstur pada U. |
| [getWrapModeV()](#getWrapModeV--) | Mendapatkan mode pembungkus tekstur pada V. |
| [getWrapModeW()](#getWrapModeW--) | Mendapatkan mode pembungkus tekstur pada W. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setAlpha(double value)](#setAlpha-double-) | Mengatur nilai alfa default dari tekstur. Ini berlaku ketika [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) adalah [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Nilai default adalah 1.0, rentang nilai yang valid antara 0 dan 1. |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | Mengatur apakah tekstur mendefinisikan saluran alfa. |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | Mengatur filter untuk pembesaran. |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | Mengatur filter untuk pengecilan. |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | Mengatur filter untuk sampling tingkat mip. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setRotation(double u, double v)](#setRotation-double-double-) | Mengatur rotasi UV. |
| [setScale(double u, double v)](#setScale-double-double-) | Mengatur skala UV. |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | Mengatur translasi UV. |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | Mengatur rotasi tekstur |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | Mengatur skala UV. |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | Mengatur translasi UV. |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | Mengatur mode pembungkus tekstur pada U. |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | Mengatur mode pembungkus tekstur pada V. |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | Mengatur mode pembungkus tekstur pada W. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBase(String name) {#TextureBase-java.lang.String-}
```
public TextureBase(String name)
```


Menginisialisasi instance baru dari kelas [TextureBase](../../com.aspose.threed/texturebase).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama. |

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
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


Mendapatkan nilai alfa default dari tekstur. Ini berlaku ketika [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) adalah [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Nilai default adalah 1.0, rentang nilai yang valid antara 0 dan 1.

**Returns:**
double - nilai alfa default tekstur. Ini berlaku ketika [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) adalah [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) Nilai default adalah 1.0, rentang nilai yang valid antara 0 dan 1
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


Mendapatkan apakah tekstur mendefinisikan saluran alfa. Nilai default adalah [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Returns:**
[AlphaSource](../../com.aspose.threed/alphasource) - whether the texture defines the alpha channel. Default value is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


Mendapatkan filter untuk pembesaran.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


Mendapatkan filter untuk pengecilan.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


Mendapatkan filter untuk sampling tingkat mip.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
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
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


Mendapatkan rotasi tekstur.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


Mendapatkan skala UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


Mendapatkan translasi UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


Mendapatkan mode pembungkus tekstur pada U.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


Mendapatkan mode pembungkus tekstur pada V.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


Mendapatkan mode pembungkus tekstur pada W.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in W.
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
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


Mengatur nilai alfa default dari tekstur. Ini berlaku ketika [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) adalah [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Nilai default adalah 1.0, rentang nilai yang valid antara 0 dan 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


Mengatur apakah tekstur mendefinisikan saluran alfa. Nilai default adalah [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | Nilai baru |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


Mengatur filter untuk pembesaran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nilai baru |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


Mengatur filter untuk pengecilan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nilai baru |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


Mengatur filter untuk sampling tingkat mip.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nilai baru |

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

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


Mengatur rotasi UV.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


Mengatur skala UV.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


Mengatur translasi UV.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


Mengatur rotasi tekstur

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


Mengatur skala UV.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


Mengatur translasi UV.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


Mengatur mode pembungkus tekstur pada U.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nilai baru |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


Mengatur mode pembungkus tekstur pada V.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nilai baru |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


Mengatur mode pembungkus tekstur pada W.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nilai baru |

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

