---
title: PixelFormat
second_title: Aspose.3D for Java API-referens
description: Pixelformatet som används i texturenheten.
type: docs
weight: 290
url: /sv/java/com.aspose.threed/pixelformat/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PixelFormat extends Enum<PixelFormat>
```

Pixelns format som används i texturenheten.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [A1R5G5B5](#A1R5G5B5) | 16-bitars pixelformat, 5 bitar för blå, grön, röd och 1 för alfa. |
| [A2B10G10R10](#A2B10G10R10) | 32-bitars pixelformat, 10 bitar för blå, grön och röd, 2 bitar för alfa. |
| [A2R10G10B10](#A2R10G10B10) | 32-bitars pixelformat, 2 bitar för alfa, 10 bitar för röd, grön och blå. |
| [A4L4](#A4L4) | 8-bitars pixelformat, 4 bitar alfa, 4 bitar luminans. |
| [A4R4G4B4](#A4R4G4B4) | 16-bitars pixelformat, 4 bitar för alfa, röd, grön och blå. |
| [A8](#A8) | 8-bitars pixelformat, alla bitar alfa. |
| [A8B8G8R8](#A8B8G8R8) | 32-bitars pixelformat, 8 bitar för blå, grön, röd och alfa. |
| [A8R8G8B8](#A8R8G8B8) | 32-bitars pixelformat, 8 bitar för alfa, röd, grön och blå. |
| [B5G6R5](#B5G6R5) | 16-bitars pixelformat, 5 bitar röd, 6 bitar grön, 5 bitar blå. |
| [B8](#B8) | 8-bitars pixelformat, alla bitar blå. |
| [B8G8R8](#B8G8R8) | 24-bitars pixelformat, 8 bitar för blå, grön och röd. |
| [B8G8R8A8](#B8G8R8A8) | 32-bitars pixelformat, 8 bitar för blå, grön, röd och alfa. |
| [BYTE_LA](#BYTE-LA) | 2-byte pixelformat, 1 byte luminans, 1 byte alfa |
| [DEPTH](#DEPTH) | Djuptexturformat. |
| [DXT1](#DXT1) | DDS (DirectDraw Surface) DXT1-format. |
| [DXT2](#DXT2) | DDS (DirectDraw Surface) DXT2-format. |
| [DXT3](#DXT3) | DDS (DirectDraw Surface) DXT3-format. |
| [DXT4](#DXT4) | DDS (DirectDraw Surface) DXT4-format. |
| [DXT5](#DXT5) | DDS (DirectDraw Surface) DXT5-format. |
| [FLOAT16_GR](#FLOAT16-GR) | 32-bit, 2-kanal s10e5 flyttal pixelformat, 16-bit grön, 16-bit röd |
| [FLOAT16_R](#FLOAT16-R) | 16-bit pixelformat, 16 bitar (flyttal) för röd |
| [FLOAT16_RGB](#FLOAT16-RGB) | 48-bit pixelformat, 16 bitar (flyttal) för röd, 16 bitar (flyttal) för grön, 16 bitar (flyttal) för blå |
| [FLOAT16_RGBA](#FLOAT16-RGBA) | 64-bit pixelformat, 16 bitar (flyttal) för röd, 16 bitar (flyttal) för grön, 16 bitar (flyttal) för blå, 16 bitar (flyttal) för alfa |
| [FLOAT32_GR](#FLOAT32-GR) | 64-bit, 2-kanal flyttal pixelformat, 32-bit grön, 32-bit röd |
| [FLOAT32_R](#FLOAT32-R) | 32-bit pixelformat, 32 bitar (flyttal) för röd |
| [FLOAT32_RGB](#FLOAT32-RGB) | 96-bit pixelformat, 32 bitar (flyttal) för röd, 32 bitar (flyttal) för grön, 32 bitar (flyttal) för blå |
| [FLOAT32_RGBA](#FLOAT32-RGBA) | 128-bit pixelformat, 32 bitar (flyttal) för röd, 32 bitar (flyttal) för grön, 32 bitar (flyttal) för blå, 32 bitar (flyttal) för alfa |
| [G8](#G8) | 8-bit pixelformat, alla bitar grön. |
| [L16](#L16) | 16-bit pixelformat, alla bitar luminans. |
| [L8](#L8) | 8-bit pixelformat, alla bitar luminans. |
| [R32G32B32A32_UINT](#R32G32B32A32-UINT) | 128-bit pixelformat, 32 bitar röd (unsigned int), 32 bitar blå (unsigned int), 32 bitar grön (unsigned int), 32 bitar alfa (unsigned int). |
| [R32G32_UINT](#R32G32-UINT) | 64-bit pixelformat, 32 bitar röd (unsigned int), 32 bitar blå (unsigned int). |
| [R32_UINT](#R32-UINT) | 32-bit pixelformat, 32 bitar röd (unsigned int). |
| [R3G3B2](#R3G3B2) | 8-bit pixelformat, 2 bitar blå, 3 bitar grön, 3 bitar röd. |
| [R5G6B5](#R5G6B5) | 16-bitars pixelformat, 5 bitar röd, 6 bitar grön, 5 bitar blå. |
| [R8](#R8) | 8-bit pixelformat, alla bitar röd. |
| [R8G8B8](#R8G8B8) | 24-bit pixelformat, 8 bitar för röd, grön och blå. |
| [R8G8B8A8](#R8G8B8A8) | 32-bit pixelformat, 8 bitar för röd, grön, blå och alfa. |
| [SHORT_GR](#SHORT-GR) | 32-bit pixelformat, 16-bit grön, 16-bit röd |
| [SHORT_RGB](#SHORT-RGB) | 48-bit pixelformat, 16 bitar för röd, grön och blå |
| [SHORT_RGBA](#SHORT-RGBA) | 64-bit pixelformat, 16 bitar för röd, grön, blå och alfa |
| [UNKNOWN](#UNKNOWN) | Okänt pixelformat. |
| [X8B8G8R8](#X8B8G8R8) | 32-bit pixelformat, 8 bitar för blå, 8 bitar för grön, 8 bitar för röd som A8B8G8R8, men alfa kommer att tas bort |
| [X8R8G8B8](#X8R8G8B8) | 32-bit pixelformat, 8 bitar för röd, 8 bitar för grön, 8 bitar för blå som A8R8G8B8, men alfa kommer att tas bort |
## Metoder

| Metod | Beskrivning |
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


16-bitars pixelformat, 5 bitar för blå, grön, röd och 1 för alfa.

### A2B10G10R10 {#A2B10G10R10}
```
public static final PixelFormat A2B10G10R10
```


32-bitars pixelformat, 10 bitar för blå, grön och röd, 2 bitar för alfa.

### A2R10G10B10 {#A2R10G10B10}
```
public static final PixelFormat A2R10G10B10
```


32-bitars pixelformat, 2 bitar för alfa, 10 bitar för röd, grön och blå.

### A4L4 {#A4L4}
```
public static final PixelFormat A4L4
```


8-bitars pixelformat, 4 bitar alfa, 4 bitar luminans.

### A4R4G4B4 {#A4R4G4B4}
```
public static final PixelFormat A4R4G4B4
```


16-bitars pixelformat, 4 bitar för alfa, röd, grön och blå.

### A8 {#A8}
```
public static final PixelFormat A8
```


8-bitars pixelformat, alla bitar alfa.

### A8B8G8R8 {#A8B8G8R8}
```
public static final PixelFormat A8B8G8R8
```


32-bitars pixelformat, 8 bitar för blå, grön, röd och alfa.

### A8R8G8B8 {#A8R8G8B8}
```
public static final PixelFormat A8R8G8B8
```


32-bitars pixelformat, 8 bitar för alfa, röd, grön och blå.

### B5G6R5 {#B5G6R5}
```
public static final PixelFormat B5G6R5
```


16-bitars pixelformat, 5 bitar röd, 6 bitar grön, 5 bitar blå.

### B8 {#B8}
```
public static final PixelFormat B8
```


8-bitars pixelformat, alla bitar blå.

### B8G8R8 {#B8G8R8}
```
public static final PixelFormat B8G8R8
```


24-bitars pixelformat, 8 bitar för blå, grön och röd.

### B8G8R8A8 {#B8G8R8A8}
```
public static final PixelFormat B8G8R8A8
```


32-bitars pixelformat, 8 bitar för blå, grön, röd och alfa.

### BYTE_LA {#BYTE-LA}
```
public static final PixelFormat BYTE_LA
```


2-byte pixelformat, 1 byte luminans, 1 byte alfa

### DEPTH {#DEPTH}
```
public static final PixelFormat DEPTH
```


Djuptexturformat.

### DXT1 {#DXT1}
```
public static final PixelFormat DXT1
```


DDS (DirectDraw Surface) DXT1-format.

### DXT2 {#DXT2}
```
public static final PixelFormat DXT2
```


DDS (DirectDraw Surface) DXT2-format.

### DXT3 {#DXT3}
```
public static final PixelFormat DXT3
```


DDS (DirectDraw Surface) DXT3-format.

### DXT4 {#DXT4}
```
public static final PixelFormat DXT4
```


DDS (DirectDraw Surface) DXT4-format.

### DXT5 {#DXT5}
```
public static final PixelFormat DXT5
```


DDS (DirectDraw Surface) DXT5-format.

### FLOAT16_GR {#FLOAT16-GR}
```
public static final PixelFormat FLOAT16_GR
```


32-bit, 2-kanal s10e5 flyttal pixelformat, 16-bit grön, 16-bit röd

### FLOAT16_R {#FLOAT16-R}
```
public static final PixelFormat FLOAT16_R
```


16-bit pixelformat, 16 bitar (flyttal) för röd

### FLOAT16_RGB {#FLOAT16-RGB}
```
public static final PixelFormat FLOAT16_RGB
```


48-bit pixelformat, 16 bitar (flyttal) för röd, 16 bitar (flyttal) för grön, 16 bitar (flyttal) för blå

### FLOAT16_RGBA {#FLOAT16-RGBA}
```
public static final PixelFormat FLOAT16_RGBA
```


64-bit pixelformat, 16 bitar (flyttal) för röd, 16 bitar (flyttal) för grön, 16 bitar (flyttal) för blå, 16 bitar (flyttal) för alfa

### FLOAT32_GR {#FLOAT32-GR}
```
public static final PixelFormat FLOAT32_GR
```


64-bit, 2-kanal flyttal pixelformat, 32-bit grön, 32-bit röd

### FLOAT32_R {#FLOAT32-R}
```
public static final PixelFormat FLOAT32_R
```


32-bit pixelformat, 32 bitar (flyttal) för röd

### FLOAT32_RGB {#FLOAT32-RGB}
```
public static final PixelFormat FLOAT32_RGB
```


96-bit pixelformat, 32 bitar (flyttal) för röd, 32 bitar (flyttal) för grön, 32 bitar (flyttal) för blå

### FLOAT32_RGBA {#FLOAT32-RGBA}
```
public static final PixelFormat FLOAT32_RGBA
```


128-bit pixelformat, 32 bitar (flyttal) för röd, 32 bitar (flyttal) för grön, 32 bitar (flyttal) för blå, 32 bitar (flyttal) för alfa

### G8 {#G8}
```
public static final PixelFormat G8
```


8-bit pixelformat, alla bitar grön.

### L16 {#L16}
```
public static final PixelFormat L16
```


16-bit pixelformat, alla bitar luminans.

### L8 {#L8}
```
public static final PixelFormat L8
```


8-bit pixelformat, alla bitar luminans.

### R32G32B32A32_UINT {#R32G32B32A32-UINT}
```
public static final PixelFormat R32G32B32A32_UINT
```


128-bit pixelformat, 32 bitar röd (unsigned int), 32 bitar blå (unsigned int), 32 bitar grön (unsigned int), 32 bitar alfa (unsigned int).

### R32G32_UINT {#R32G32-UINT}
```
public static final PixelFormat R32G32_UINT
```


64-bit pixelformat, 32 bitar röd (unsigned int), 32 bitar blå (unsigned int).

### R32_UINT {#R32-UINT}
```
public static final PixelFormat R32_UINT
```


32-bit pixelformat, 32 bitar röd (unsigned int).

### R3G3B2 {#R3G3B2}
```
public static final PixelFormat R3G3B2
```


8-bit pixelformat, 2 bitar blå, 3 bitar grön, 3 bitar röd.

### R5G6B5 {#R5G6B5}
```
public static final PixelFormat R5G6B5
```


16-bitars pixelformat, 5 bitar röd, 6 bitar grön, 5 bitar blå.

### R8 {#R8}
```
public static final PixelFormat R8
```


8-bit pixelformat, alla bitar röd.

### R8G8B8 {#R8G8B8}
```
public static final PixelFormat R8G8B8
```


24-bit pixelformat, 8 bitar för röd, grön och blå.

### R8G8B8A8 {#R8G8B8A8}
```
public static final PixelFormat R8G8B8A8
```


32-bit pixelformat, 8 bitar för röd, grön, blå och alfa.

### SHORT_GR {#SHORT-GR}
```
public static final PixelFormat SHORT_GR
```


32-bit pixelformat, 16-bit grön, 16-bit röd

### SHORT_RGB {#SHORT-RGB}
```
public static final PixelFormat SHORT_RGB
```


48-bit pixelformat, 16 bitar för röd, grön och blå

### SHORT_RGBA {#SHORT-RGBA}
```
public static final PixelFormat SHORT_RGBA
```


64-bit pixelformat, 16 bitar för röd, grön, blå och alfa

### UNKNOWN {#UNKNOWN}
```
public static final PixelFormat UNKNOWN
```


Okänt pixelformat.

### X8B8G8R8 {#X8B8G8R8}
```
public static final PixelFormat X8B8G8R8
```


32-bit pixelformat, 8 bitar för blå, 8 bitar för grön, 8 bitar för röd som A8B8G8R8, men alfa kommer att tas bort

### X8R8G8B8 {#X8R8G8B8}
```
public static final PixelFormat X8R8G8B8
```


32-bit pixelformat, 8 bitar för röd, 8 bitar för grön, 8 bitar för blå som A8R8G8B8, men alfa kommer att tas bort

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

