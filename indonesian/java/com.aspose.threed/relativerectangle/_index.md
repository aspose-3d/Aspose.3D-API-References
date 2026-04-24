---
title: RelativeRectangle
second_title: Referensi API Aspose.3D untuk Java
description: Relative rectangle  Rumus antara komponen relatif ke nilai absolut adalah  Scale  Reference Width  offset  Jadi jika kita ingin itu mewakili nilai absolut, biarkan semua bidang skala nol dan gunakan bidang offset sebagai gantinya.
type: docs
weight: 147
url: /id/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

Persegi panjang relatif Rumus antara komponen relatif ke nilai absolut adalah: Scale \* (Reference Width) + offset. Jadi jika kita ingin itu mewakili nilai absolut, biarkan semua bidang skala nol, dan gunakan bidang offset sebagai gantinya.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | Buat sebuah [RelativeRectangle](../../com.aspose.threed/relativerectangle) |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | Buat sebuah [RelativeRectangle](../../com.aspose.threed/relativerectangle) dengan semua bidang offset nol dan bidang skala dari parameter yang diberikan. |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | Mendapatkan offset untuk tinggi |
| [getOffsetWidth()](#getOffsetWidth--) | Mendapatkan offset untuk lebar |
| [getOffsetX()](#getOffsetX--) | Mendapatkan offset untuk koordinat X |
| [getOffsetY()](#getOffsetY--) | Mendapatkan offset untuk koordinat Y |
| [getScaleHeight()](#getScaleHeight--) | Tinggi relatif |
| [getScaleWidth()](#getScaleWidth--) | Lebar relatif |
| [getScaleX()](#getScaleX--) | Koordinat X relatif |
| [getScaleY()](#getScaleY--) | Koordinat Y relatif |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | Mengatur offset untuk tinggi |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | Mengatur offset untuk lebar |
| [setOffsetX(int value)](#setOffsetX-int-) | Mengatur offset untuk koordinat X |
| [setOffsetY(int value)](#setOffsetY-int-) | Mengatur offset untuk koordinat Y |
| [setScaleHeight(float value)](#setScaleHeight-float-) | Tinggi relatif |
| [setScaleWidth(float value)](#setScaleWidth-float-) | Lebar relatif |
| [setScaleX(float value)](#setScaleX-float-) | Koordinat X relatif |
| [setScaleY(float value)](#setScaleY-float-) | Koordinat Y relatif |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | Konversi rectangle relatif menjadi rectangle absolut |
| [toString()](#toString--) | Mengonversi nilai instance ini menjadi java.lang.String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


Buat sebuah [RelativeRectangle](../../com.aspose.threed/relativerectangle)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kiri | int |  |
| atas | int |  |
| lebar | int |  |
| tinggi | int |  |

### RelativeRectangle() {#RelativeRectangle--}
```
public RelativeRectangle()
```


### clone() {#clone--}
```
public RelativeRectangle clone()
```


Clone current instance

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### copyFrom(RelativeRectangle src) {#copyFrom-com.aspose.threed.RelativeRectangle-}
```
public void copyFrom(RelativeRectangle src)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


Buat sebuah [RelativeRectangle](../../com.aspose.threed/relativerectangle) dengan semua bidang offset nol dan bidang skala dari parameter yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleX | float |  |
| scaleY | float |  |
| scaleWidth | float |  |
| scaleHeight | float |  |

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOffsetHeight() {#getOffsetHeight--}
```
public int getOffsetHeight()
```


Mendapatkan offset untuk tinggi

**Returns:**
int - offset untuk tinggi
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


Mendapatkan offset untuk lebar

**Returns:**
int - offset untuk lebar
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


Mendapatkan offset untuk koordinat X

**Returns:**
int - offset untuk koordinat X
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


Mendapatkan offset untuk koordinat Y

**Returns:**
int - offset untuk koordinat Y
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


Tinggi relatif

**Returns:**
float - Tinggi relatif
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


Lebar relatif

**Returns:**
float - Lebar relatif
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Koordinat X relatif

**Returns:**
float - Koordinat relatif X
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Koordinat Y relatif

**Returns:**
float - Koordinat relatif Y
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setOffsetHeight(int value) {#setOffsetHeight-int-}
```
public void setOffsetHeight(int value)
```


Mengatur offset untuk tinggi

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


Mengatur offset untuk lebar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


Mengatur offset untuk koordinat X

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


Mengatur offset untuk koordinat Y

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


Tinggi relatif

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


Lebar relatif

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Koordinat X relatif

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Koordinat Y relatif

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


Konversi rectangle relatif menjadi rectangle absolut

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kiri | int | Kiri dari persegi panjang |
| atas | int | Atas persegi panjang |
| lebar | int | Lebar persegi panjang |
| tinggi | int | Tinggi persegi panjang |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


Mengonversi nilai instance ini menjadi java.lang.String.

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

