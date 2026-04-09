---
title: PixelFormat
second_title: Referensi API Aspose.3D untuk Java
description: Format piksel yang digunakan dalam unit tekstur.
type: docs
weight: 290
url: /id/java/com.aspose.threed/pixelformat/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PixelFormat extends Enum<PixelFormat>
```

Format piksel yang digunakan dalam unit tekstur.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [A1R5G5B5](#A1R5G5B5) | Format piksel 16-bit, 5 bit untuk biru, hijau, merah, dan 1 untuk alfa. |
| [A2B10G10R10](#A2B10G10R10) | Format piksel 32-bit, 10 bit untuk biru, hijau, dan merah, 2 bit untuk alfa. |
| [A2R10G10B10](#A2R10G10B10) | Format piksel 32-bit, 2 bit untuk alfa, 10 bit untuk merah, hijau, dan biru. |
| [A4L4](#A4L4) | Format piksel 8-bit, 4 bit alfa, 4 bit luminansi. |
| [A4R4G4B4](#A4R4G4B4) | Format piksel 16-bit, 4 bit untuk alfa, merah, hijau, dan biru. |
| [A8](#A8) | Format piksel 8-bit, semua bit alfa. |
| [A8B8G8R8](#A8B8G8R8) | Format piksel 32-bit, 8 bit untuk biru, hijau, merah, dan alfa. |
| [A8R8G8B8](#A8R8G8B8) | Format piksel 32-bit, 8 bit untuk alfa, merah, hijau, dan biru. |
| [B5G6R5](#B5G6R5) | Format piksel 16-bit, 5 bit merah, 6 bit hijau, 5 bit biru. |
| [B8](#B8) | Format piksel 8-bit, semua bit biru. |
| [B8G8R8](#B8G8R8) | Format piksel 24-bit, 8 bit untuk biru, hijau, dan merah. |
| [B8G8R8A8](#B8G8R8A8) | Format piksel 32-bit, 8 bit untuk biru, hijau, merah, dan alfa. |
| [BYTE_LA](#BYTE-LA) | Format piksel 2 byte, 1 byte luminansi, 1 byte alfa |
| [DEPTH](#DEPTH) | Format tekstur kedalaman. |
| [DXT1](#DXT1) | Format DDS (DirectDraw Surface) DXT1. |
| [DXT2](#DXT2) | Format DDS (DirectDraw Surface) DXT2. |
| [DXT3](#DXT3) | Format DDS (DirectDraw Surface) DXT3. |
| [DXT4](#DXT4) | Format DDS (DirectDraw Surface) DXT4. |
| [DXT5](#DXT5) | Format DDS (DirectDraw Surface) DXT5. |
| [FLOAT16_GR](#FLOAT16-GR) | 32-bit, 2-kanal s10e5 format piksel titik mengambang, 16-bit hijau, 16-bit merah |
| [FLOAT16_R](#FLOAT16-R) | format piksel 16-bit, 16 bit (float) untuk merah |
| [FLOAT16_RGB](#FLOAT16-RGB) | format piksel 48-bit, 16 bit (float) untuk merah, 16 bit (float) untuk hijau, 16 bit (float) untuk biru |
| [FLOAT16_RGBA](#FLOAT16-RGBA) | format piksel 64-bit, 16 bit (float) untuk merah, 16 bit (float) untuk hijau, 16 bit (float) untuk biru, 16 bit (float) untuk alpha |
| [FLOAT32_GR](#FLOAT32-GR) | 64-bit, 2-kanal format piksel titik mengambang, 32-bit hijau, 32-bit merah |
| [FLOAT32_R](#FLOAT32-R) | format piksel 32-bit, 32 bit (float) untuk merah |
| [FLOAT32_RGB](#FLOAT32-RGB) | format piksel 96-bit, 32 bit (float) untuk merah, 32 bit (float) untuk hijau, 32 bit (float) untuk biru |
| [FLOAT32_RGBA](#FLOAT32-RGBA) | format piksel 128-bit, 32 bit (float) untuk merah, 32 bit (float) untuk hijau, 32 bit (float) untuk biru, 32 bit (float) untuk alpha |
| [G8](#G8) | format piksel 8-bit, semua bit hijau. |
| [L16](#L16) | format piksel 16-bit, semua bit luminansi. |
| [L8](#L8) | format piksel 8-bit, semua bit luminansi. |
| [R32G32B32A32_UINT](#R32G32B32A32-UINT) | format piksel 128-bit, 32 bit merah (int tak bertanda), 32 bit biru (int tak bertanda), 32 bit hijau (int tak bertanda), 32 bit alpha (int tak bertanda). |
| [R32G32_UINT](#R32G32-UINT) | format piksel 64-bit, 32 bit merah (int tak bertanda), 32 bit biru (int tak bertanda). |
| [R32_UINT](#R32-UINT) | format piksel 32-bit, 32 bit merah (int tak bertanda). |
| [R3G3B2](#R3G3B2) | format piksel 8-bit, 2 bit biru, 3 bit hijau, 3 bit merah. |
| [R5G6B5](#R5G6B5) | Format piksel 16-bit, 5 bit merah, 6 bit hijau, 5 bit biru. |
| [R8](#R8) | format piksel 8-bit, semua bit merah. |
| [R8G8B8](#R8G8B8) | format piksel 24-bit, 8 bit untuk merah, hijau, dan biru. |
| [R8G8B8A8](#R8G8B8A8) | format piksel 32-bit, 8 bit untuk merah, hijau, biru, dan alpha. |
| [SHORT_GR](#SHORT-GR) | format piksel 32-bit, 16-bit hijau, 16-bit merah |
| [SHORT_RGB](#SHORT-RGB) | format piksel 48-bit, 16 bit untuk merah, hijau, dan biru |
| [SHORT_RGBA](#SHORT-RGBA) | format piksel 64-bit, 16 bit untuk merah, hijau, biru, dan alpha |
| [UNKNOWN](#UNKNOWN) | Format piksel tidak diketahui. |
| [X8B8G8R8](#X8B8G8R8) | format piksel 32-bit, 8 bit untuk biru, 8 bit untuk hijau, 8 bit untuk merah seperti A8B8G8R8, tetapi alpha akan dibuang |
| [X8R8G8B8](#X8R8G8B8) | format piksel 32-bit, 8 bit untuk merah, 8 bit untuk hijau, 8 bit untuk biru seperti A8R8G8B8, tetapi alpha akan dibuang |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### A1R5G5B5 {#A1R5G5B5}
```
public static final PixelFormat A1R5G5B5
```


Format piksel 16-bit, 5 bit untuk biru, hijau, merah, dan 1 untuk alfa.

### A2B10G10R10 {#A2B10G10R10}
```
public static final PixelFormat A2B10G10R10
```


Format piksel 32-bit, 10 bit untuk biru, hijau, dan merah, 2 bit untuk alfa.

### A2R10G10B10 {#A2R10G10B10}
```
public static final PixelFormat A2R10G10B10
```


Format piksel 32-bit, 2 bit untuk alfa, 10 bit untuk merah, hijau, dan biru.

### A4L4 {#A4L4}
```
public static final PixelFormat A4L4
```


Format piksel 8-bit, 4 bit alfa, 4 bit luminansi.

### A4R4G4B4 {#A4R4G4B4}
```
public static final PixelFormat A4R4G4B4
```


Format piksel 16-bit, 4 bit untuk alfa, merah, hijau, dan biru.

### A8 {#A8}
```
public static final PixelFormat A8
```


Format piksel 8-bit, semua bit alfa.

### A8B8G8R8 {#A8B8G8R8}
```
public static final PixelFormat A8B8G8R8
```


Format piksel 32-bit, 8 bit untuk biru, hijau, merah, dan alfa.

### A8R8G8B8 {#A8R8G8B8}
```
public static final PixelFormat A8R8G8B8
```


Format piksel 32-bit, 8 bit untuk alfa, merah, hijau, dan biru.

### B5G6R5 {#B5G6R5}
```
public static final PixelFormat B5G6R5
```


Format piksel 16-bit, 5 bit merah, 6 bit hijau, 5 bit biru.

### B8 {#B8}
```
public static final PixelFormat B8
```


Format piksel 8-bit, semua bit biru.

### B8G8R8 {#B8G8R8}
```
public static final PixelFormat B8G8R8
```


Format piksel 24-bit, 8 bit untuk biru, hijau, dan merah.

### B8G8R8A8 {#B8G8R8A8}
```
public static final PixelFormat B8G8R8A8
```


Format piksel 32-bit, 8 bit untuk biru, hijau, merah, dan alfa.

### BYTE_LA {#BYTE-LA}
```
public static final PixelFormat BYTE_LA
```


Format piksel 2 byte, 1 byte luminansi, 1 byte alfa

### DEPTH {#DEPTH}
```
public static final PixelFormat DEPTH
```


Format tekstur kedalaman.

### DXT1 {#DXT1}
```
public static final PixelFormat DXT1
```


Format DDS (DirectDraw Surface) DXT1.

### DXT2 {#DXT2}
```
public static final PixelFormat DXT2
```


Format DDS (DirectDraw Surface) DXT2.

### DXT3 {#DXT3}
```
public static final PixelFormat DXT3
```


Format DDS (DirectDraw Surface) DXT3.

### DXT4 {#DXT4}
```
public static final PixelFormat DXT4
```


Format DDS (DirectDraw Surface) DXT4.

### DXT5 {#DXT5}
```
public static final PixelFormat DXT5
```


Format DDS (DirectDraw Surface) DXT5.

### FLOAT16_GR {#FLOAT16-GR}
```
public static final PixelFormat FLOAT16_GR
```


32-bit, 2-kanal s10e5 format piksel titik mengambang, 16-bit hijau, 16-bit merah

### FLOAT16_R {#FLOAT16-R}
```
public static final PixelFormat FLOAT16_R
```


format piksel 16-bit, 16 bit (float) untuk merah

### FLOAT16_RGB {#FLOAT16-RGB}
```
public static final PixelFormat FLOAT16_RGB
```


format piksel 48-bit, 16 bit (float) untuk merah, 16 bit (float) untuk hijau, 16 bit (float) untuk biru

### FLOAT16_RGBA {#FLOAT16-RGBA}
```
public static final PixelFormat FLOAT16_RGBA
```


format piksel 64-bit, 16 bit (float) untuk merah, 16 bit (float) untuk hijau, 16 bit (float) untuk biru, 16 bit (float) untuk alpha

### FLOAT32_GR {#FLOAT32-GR}
```
public static final PixelFormat FLOAT32_GR
```


64-bit, 2-kanal format piksel titik mengambang, 32-bit hijau, 32-bit merah

### FLOAT32_R {#FLOAT32-R}
```
public static final PixelFormat FLOAT32_R
```


format piksel 32-bit, 32 bit (float) untuk merah

### FLOAT32_RGB {#FLOAT32-RGB}
```
public static final PixelFormat FLOAT32_RGB
```


format piksel 96-bit, 32 bit (float) untuk merah, 32 bit (float) untuk hijau, 32 bit (float) untuk biru

### FLOAT32_RGBA {#FLOAT32-RGBA}
```
public static final PixelFormat FLOAT32_RGBA
```


format piksel 128-bit, 32 bit (float) untuk merah, 32 bit (float) untuk hijau, 32 bit (float) untuk biru, 32 bit (float) untuk alpha

### G8 {#G8}
```
public static final PixelFormat G8
```


format piksel 8-bit, semua bit hijau.

### L16 {#L16}
```
public static final PixelFormat L16
```


format piksel 16-bit, semua bit luminansi.

### L8 {#L8}
```
public static final PixelFormat L8
```


format piksel 8-bit, semua bit luminansi.

### R32G32B32A32_UINT {#R32G32B32A32-UINT}
```
public static final PixelFormat R32G32B32A32_UINT
```


format piksel 128-bit, 32 bit merah (int tak bertanda), 32 bit biru (int tak bertanda), 32 bit hijau (int tak bertanda), 32 bit alpha (int tak bertanda).

### R32G32_UINT {#R32G32-UINT}
```
public static final PixelFormat R32G32_UINT
```


format piksel 64-bit, 32 bit merah (int tak bertanda), 32 bit biru (int tak bertanda).

### R32_UINT {#R32-UINT}
```
public static final PixelFormat R32_UINT
```


format piksel 32-bit, 32 bit merah (int tak bertanda).

### R3G3B2 {#R3G3B2}
```
public static final PixelFormat R3G3B2
```


format piksel 8-bit, 2 bit biru, 3 bit hijau, 3 bit merah.

### R5G6B5 {#R5G6B5}
```
public static final PixelFormat R5G6B5
```


Format piksel 16-bit, 5 bit merah, 6 bit hijau, 5 bit biru.

### R8 {#R8}
```
public static final PixelFormat R8
```


format piksel 8-bit, semua bit merah.

### R8G8B8 {#R8G8B8}
```
public static final PixelFormat R8G8B8
```


format piksel 24-bit, 8 bit untuk merah, hijau, dan biru.

### R8G8B8A8 {#R8G8B8A8}
```
public static final PixelFormat R8G8B8A8
```


format piksel 32-bit, 8 bit untuk merah, hijau, biru, dan alpha.

### SHORT_GR {#SHORT-GR}
```
public static final PixelFormat SHORT_GR
```


format piksel 32-bit, 16-bit hijau, 16-bit merah

### SHORT_RGB {#SHORT-RGB}
```
public static final PixelFormat SHORT_RGB
```


format piksel 48-bit, 16 bit untuk merah, hijau, dan biru

### SHORT_RGBA {#SHORT-RGBA}
```
public static final PixelFormat SHORT_RGBA
```


format piksel 64-bit, 16 bit untuk merah, hijau, biru, dan alpha

### UNKNOWN {#UNKNOWN}
```
public static final PixelFormat UNKNOWN
```


Format piksel tidak diketahui.

### X8B8G8R8 {#X8B8G8R8}
```
public static final PixelFormat X8B8G8R8
```


format piksel 32-bit, 8 bit untuk biru, 8 bit untuk hijau, 8 bit untuk merah seperti A8B8G8R8, tetapi alpha akan dibuang

### X8R8G8B8 {#X8R8G8B8}
```
public static final PixelFormat X8R8G8B8
```


format piksel 32-bit, 8 bit untuk merah, 8 bit untuk hijau, 8 bit untuk biru seperti A8R8G8B8, tetapi alpha akan dibuang

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PixelFormat valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat)
### values() {#values--}
```
public static PixelFormat[] values()
```




**Returns:**
com.aspose.threed.PixelFormat[]
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

