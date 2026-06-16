---
title: "PixelFormat"
second_title: "Aspose.3D for Java API Referansı"
description: "Doku biriminde kullanılan piksel biçimi."
type: docs
weight: 290
url: /tr/java/com.aspose.threed/pixelformat/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PixelFormat extends Enum<PixelFormat>
```

Doku biriminde kullanılan piksel formatı.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [A1R5G5B5](#A1R5G5B5) | 16 bit piksel biçimi, mavi, yeşil, kırmızı için 5 bit ve alfa için 1 bit. |
| [A2B10G10R10](#A2B10G10R10) | 32 bit piksel biçimi, mavi, yeşil ve kırmızı için 10 bit, alfa için 2 bit. |
| [A2R10G10B10](#A2R10G10B10) | 32 bit piksel biçimi, alfa için 2 bit, kırmızı, yeşil ve mavi için 10 bit. |
| [A4L4](#A4L4) | 8 bit piksel biçimi, 4 bit alfa, 4 bit parlaklık. |
| [A4R4G4B4](#A4R4G4B4) | 16 bit piksel biçimi, alfa, kırmızı, yeşil ve mavi için 4 bit. |
| [A8](#A8) | 8 bit piksel biçimi, tüm bitler alfa. |
| [A8B8G8R8](#A8B8G8R8) | 32 bit piksel biçimi, mavi, yeşil, kırmızı ve alfa için 8 bit. |
| [A8R8G8B8](#A8R8G8B8) | 32 bit piksel biçimi, alfa, kırmızı, yeşil ve mavi için 8 bit. |
| [B5G6R5](#B5G6R5) | 16 bit piksel biçimi, kırmızı için 5 bit, yeşil için 6 bit, mavi için 5 bit. |
| [B8](#B8) | 8 bit piksel biçimi, tüm bitler mavi. |
| [B8G8R8](#B8G8R8) | 24 bit piksel biçimi, mavi, yeşil ve kırmızı için 8 bit. |
| [B8G8R8A8](#B8G8R8A8) | 32 bit piksel biçimi, mavi, yeşil, kırmızı ve alfa için 8 bit. |
| [BYTE_LA](#BYTE-LA) | 2 bayt piksel biçimi, 1 bayt parlaklık, 1 bayt alfa |
| [DEPTH](#DEPTH) | Derinlik doku biçimi. |
| [DXT1](#DXT1) | DDS (DirectDraw Surface) DXT1 biçimi. |
| [DXT2](#DXT2) | DDS (DirectDraw Surface) DXT2 biçimi. |
| [DXT3](#DXT3) | DDS (DirectDraw Surface) DXT3 biçimi. |
| [DXT4](#DXT4) | DDS (DirectDraw Surface) DXT4 biçimi. |
| [DXT5](#DXT5) | DDS (DirectDraw Surface) DXT5 biçimi. |
| [FLOAT16_GR](#FLOAT16-GR) | 32-bit, 2-kanallı s10e5 kayan nokta piksel biçimi, 16-bit yeşil, 16-bit kırmızı |
| [FLOAT16_R](#FLOAT16-R) | 16-bit piksel biçimi, kırmızı için 16 bit (float) |
| [FLOAT16_RGB](#FLOAT16-RGB) | 48-bit piksel biçimi, kırmızı için 16 bit (float), yeşil için 16 bit (float), mavi için 16 bit (float) |
| [FLOAT16_RGBA](#FLOAT16-RGBA) | 64-bit piksel biçimi, kırmızı için 16 bit (float), yeşil için 16 bit (float), mavi için 16 bit (float), alfa için 16 bit (float) |
| [FLOAT32_GR](#FLOAT32-GR) | 64-bit, 2-kanallı kayan nokta piksel biçimi, 32-bit yeşil, 32-bit kırmızı |
| [FLOAT32_R](#FLOAT32-R) | 32-bit piksel biçimi, kırmızı için 32 bit (float) |
| [FLOAT32_RGB](#FLOAT32-RGB) | 96-bit piksel biçimi, kırmızı için 32 bit (float), yeşil için 32 bit (float), mavi için 32 bit (float) |
| [FLOAT32_RGBA](#FLOAT32-RGBA) | 128-bit piksel biçimi, kırmızı için 32 bit (float), yeşil için 32 bit (float), mavi için 32 bit (float), alfa için 32 bit (float) |
| [G8](#G8) | 8-bit piksel biçimi, tüm bitler yeşil. |
| [L16](#L16) | 16-bit piksel biçimi, tüm bitler parlaklık. |
| [L8](#L8) | 8-bit piksel biçimi, tüm bitler parlaklık. |
| [R32G32B32A32_UINT](#R32G32B32A32-UINT) | 128-bit piksel biçimi, 32 bit kırmızı (unsigned int), 32 bit mavi (unsigned int), 32 bit yeşil (unsigned int), 32 bit alfa (unsigned int). |
| [R32G32_UINT](#R32G32-UINT) | 64-bit piksel biçimi, 32 bit kırmızı (unsigned int), 32 bit mavi (unsigned int). |
| [R32_UINT](#R32-UINT) | 32-bit piksel biçimi, 32 bit kırmızı (unsigned int). |
| [R3G3B2](#R3G3B2) | 8-bit piksel biçimi, 2 bit mavi, 3 bit yeşil, 3 bit kırmızı. |
| [R5G6B5](#R5G6B5) | 16 bit piksel biçimi, kırmızı için 5 bit, yeşil için 6 bit, mavi için 5 bit. |
| [R8](#R8) | 8-bit piksel biçimi, tüm bitler kırmızı. |
| [R8G8B8](#R8G8B8) | 24-bit piksel biçimi, kırmızı, yeşil ve mavi için 8 bit. |
| [R8G8B8A8](#R8G8B8A8) | 32-bit piksel biçimi, kırmızı, yeşil, mavi ve alfa için 8 bit. |
| [SHORT_GR](#SHORT-GR) | 32-bit piksel biçimi, 16-bit yeşil, 16-bit kırmızı |
| [SHORT_RGB](#SHORT-RGB) | 48-bit piksel biçimi, kırmızı, yeşil ve mavi için 16 bit |
| [SHORT_RGBA](#SHORT-RGBA) | 64-bit piksel biçimi, kırmızı, yeşil, mavi ve alfa için 16 bit |
| [UNKNOWN](#UNKNOWN) | Bilinmeyen piksel biçimi. |
| [X8B8G8R8](#X8B8G8R8) | 32-bit piksel biçimi, A8B8G8R8 gibi mavi için 8 bit, yeşil için 8 bit, kırmızı için 8 bit, ancak alfa atılacak |
| [X8R8G8B8](#X8R8G8B8) | 32-bit piksel biçimi, A8R8G8B8 gibi kırmızı için 8 bit, yeşil için 8 bit, mavi için 8 bit, ancak alfa atılacak |
## Yöntemler

| Yöntem | Açıklama |
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


16 bit piksel biçimi, mavi, yeşil, kırmızı için 5 bit ve alfa için 1 bit.

### A2B10G10R10 {#A2B10G10R10}
```
public static final PixelFormat A2B10G10R10
```


32 bit piksel biçimi, mavi, yeşil ve kırmızı için 10 bit, alfa için 2 bit.

### A2R10G10B10 {#A2R10G10B10}
```
public static final PixelFormat A2R10G10B10
```


32 bit piksel biçimi, alfa için 2 bit, kırmızı, yeşil ve mavi için 10 bit.

### A4L4 {#A4L4}
```
public static final PixelFormat A4L4
```


8 bit piksel biçimi, 4 bit alfa, 4 bit parlaklık.

### A4R4G4B4 {#A4R4G4B4}
```
public static final PixelFormat A4R4G4B4
```


16 bit piksel biçimi, alfa, kırmızı, yeşil ve mavi için 4 bit.

### A8 {#A8}
```
public static final PixelFormat A8
```


8 bit piksel biçimi, tüm bitler alfa.

### A8B8G8R8 {#A8B8G8R8}
```
public static final PixelFormat A8B8G8R8
```


32 bit piksel biçimi, mavi, yeşil, kırmızı ve alfa için 8 bit.

### A8R8G8B8 {#A8R8G8B8}
```
public static final PixelFormat A8R8G8B8
```


32 bit piksel biçimi, alfa, kırmızı, yeşil ve mavi için 8 bit.

### B5G6R5 {#B5G6R5}
```
public static final PixelFormat B5G6R5
```


16 bit piksel biçimi, kırmızı için 5 bit, yeşil için 6 bit, mavi için 5 bit.

### B8 {#B8}
```
public static final PixelFormat B8
```


8 bit piksel biçimi, tüm bitler mavi.

### B8G8R8 {#B8G8R8}
```
public static final PixelFormat B8G8R8
```


24 bit piksel biçimi, mavi, yeşil ve kırmızı için 8 bit.

### B8G8R8A8 {#B8G8R8A8}
```
public static final PixelFormat B8G8R8A8
```


32 bit piksel biçimi, mavi, yeşil, kırmızı ve alfa için 8 bit.

### BYTE_LA {#BYTE-LA}
```
public static final PixelFormat BYTE_LA
```


2 bayt piksel biçimi, 1 bayt parlaklık, 1 bayt alfa

### DEPTH {#DEPTH}
```
public static final PixelFormat DEPTH
```


Derinlik doku biçimi.

### DXT1 {#DXT1}
```
public static final PixelFormat DXT1
```


DDS (DirectDraw Surface) DXT1 biçimi.

### DXT2 {#DXT2}
```
public static final PixelFormat DXT2
```


DDS (DirectDraw Surface) DXT2 biçimi.

### DXT3 {#DXT3}
```
public static final PixelFormat DXT3
```


DDS (DirectDraw Surface) DXT3 biçimi.

### DXT4 {#DXT4}
```
public static final PixelFormat DXT4
```


DDS (DirectDraw Surface) DXT4 biçimi.

### DXT5 {#DXT5}
```
public static final PixelFormat DXT5
```


DDS (DirectDraw Surface) DXT5 biçimi.

### FLOAT16_GR {#FLOAT16-GR}
```
public static final PixelFormat FLOAT16_GR
```


32-bit, 2-kanallı s10e5 kayan nokta piksel biçimi, 16-bit yeşil, 16-bit kırmızı

### FLOAT16_R {#FLOAT16-R}
```
public static final PixelFormat FLOAT16_R
```


16-bit piksel biçimi, kırmızı için 16 bit (float)

### FLOAT16_RGB {#FLOAT16-RGB}
```
public static final PixelFormat FLOAT16_RGB
```


48-bit piksel biçimi, kırmızı için 16 bit (float), yeşil için 16 bit (float), mavi için 16 bit (float)

### FLOAT16_RGBA {#FLOAT16-RGBA}
```
public static final PixelFormat FLOAT16_RGBA
```


64-bit piksel biçimi, kırmızı için 16 bit (float), yeşil için 16 bit (float), mavi için 16 bit (float), alfa için 16 bit (float)

### FLOAT32_GR {#FLOAT32-GR}
```
public static final PixelFormat FLOAT32_GR
```


64-bit, 2-kanallı kayan nokta piksel biçimi, 32-bit yeşil, 32-bit kırmızı

### FLOAT32_R {#FLOAT32-R}
```
public static final PixelFormat FLOAT32_R
```


32-bit piksel biçimi, kırmızı için 32 bit (float)

### FLOAT32_RGB {#FLOAT32-RGB}
```
public static final PixelFormat FLOAT32_RGB
```


96-bit piksel biçimi, kırmızı için 32 bit (float), yeşil için 32 bit (float), mavi için 32 bit (float)

### FLOAT32_RGBA {#FLOAT32-RGBA}
```
public static final PixelFormat FLOAT32_RGBA
```


128-bit piksel biçimi, kırmızı için 32 bit (float), yeşil için 32 bit (float), mavi için 32 bit (float), alfa için 32 bit (float)

### G8 {#G8}
```
public static final PixelFormat G8
```


8-bit piksel biçimi, tüm bitler yeşil.

### L16 {#L16}
```
public static final PixelFormat L16
```


16-bit piksel biçimi, tüm bitler parlaklık.

### L8 {#L8}
```
public static final PixelFormat L8
```


8-bit piksel biçimi, tüm bitler parlaklık.

### R32G32B32A32_UINT {#R32G32B32A32-UINT}
```
public static final PixelFormat R32G32B32A32_UINT
```


128-bit piksel biçimi, 32 bit kırmızı (unsigned int), 32 bit mavi (unsigned int), 32 bit yeşil (unsigned int), 32 bit alfa (unsigned int).

### R32G32_UINT {#R32G32-UINT}
```
public static final PixelFormat R32G32_UINT
```


64-bit piksel biçimi, 32 bit kırmızı (unsigned int), 32 bit mavi (unsigned int).

### R32_UINT {#R32-UINT}
```
public static final PixelFormat R32_UINT
```


32-bit piksel biçimi, 32 bit kırmızı (unsigned int).

### R3G3B2 {#R3G3B2}
```
public static final PixelFormat R3G3B2
```


8-bit piksel biçimi, 2 bit mavi, 3 bit yeşil, 3 bit kırmızı.

### R5G6B5 {#R5G6B5}
```
public static final PixelFormat R5G6B5
```


16 bit piksel biçimi, kırmızı için 5 bit, yeşil için 6 bit, mavi için 5 bit.

### R8 {#R8}
```
public static final PixelFormat R8
```


8-bit piksel biçimi, tüm bitler kırmızı.

### R8G8B8 {#R8G8B8}
```
public static final PixelFormat R8G8B8
```


24-bit piksel biçimi, kırmızı, yeşil ve mavi için 8 bit.

### R8G8B8A8 {#R8G8B8A8}
```
public static final PixelFormat R8G8B8A8
```


32-bit piksel biçimi, kırmızı, yeşil, mavi ve alfa için 8 bit.

### SHORT_GR {#SHORT-GR}
```
public static final PixelFormat SHORT_GR
```


32-bit piksel biçimi, 16-bit yeşil, 16-bit kırmızı

### SHORT_RGB {#SHORT-RGB}
```
public static final PixelFormat SHORT_RGB
```


48-bit piksel biçimi, kırmızı, yeşil ve mavi için 16 bit

### SHORT_RGBA {#SHORT-RGBA}
```
public static final PixelFormat SHORT_RGBA
```


64-bit piksel biçimi, kırmızı, yeşil, mavi ve alfa için 16 bit

### UNKNOWN {#UNKNOWN}
```
public static final PixelFormat UNKNOWN
```


Bilinmeyen piksel biçimi.

### X8B8G8R8 {#X8B8G8R8}
```
public static final PixelFormat X8B8G8R8
```


32-bit piksel biçimi, A8B8G8R8 gibi mavi için 8 bit, yeşil için 8 bit, kırmızı için 8 bit, ancak alfa atılacak

### X8R8G8B8 {#X8R8G8B8}
```
public static final PixelFormat X8R8G8B8
```


32-bit piksel biçimi, A8R8G8B8 gibi kırmızı için 8 bit, yeşil için 8 bit, mavi için 8 bit, ancak alfa atılacak

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

