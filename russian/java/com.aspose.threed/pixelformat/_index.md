---
title: PixelFormat
second_title: Справочник API Aspose.3D для Java
description: Формат пикселей, используемый в текстурном блоке.
type: docs
weight: 290
url: /ru/java/com.aspose.threed/pixelformat/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PixelFormat extends Enum<PixelFormat>
```

Формат пикселя, используемый в текстурном блоке.
## Поля

| Поле | Описание |
| --- | --- |
| [A1R5G5B5](#A1R5G5B5) | 16‑битный формат пикселей, 5 бит для синего, зелёного, красного и 1 бит для альфа‑канала. |
| [A2B10G10R10](#A2B10G10R10) | 32‑битный формат пикселей, 10 бит для синего, зелёного и красного, 2 бита для альфа‑канала. |
| [A2R10G10B10](#A2R10G10B10) | 32‑битный формат пикселей, 2 бита для альфа‑канала, 10 бит для красного, зелёного и синего. |
| [A4L4](#A4L4) | 8‑битный формат пикселей, 4 бита альфа, 4 бита яркости. |
| [A4R4G4B4](#A4R4G4B4) | 16‑битный формат пикселей, 4 бита для альфа, красного, зелёного и синего. |
| [A8](#A8) | 8‑битный формат пикселей, все биты альфа. |
| [A8B8G8R8](#A8B8G8R8) | 32‑битный формат пикселей, 8 бит для синего, зелёного, красного и альфа‑канала. |
| [A8R8G8B8](#A8R8G8B8) | 32‑битный формат пикселей, 8 бит для альфа‑канала, красного, зелёного и синего. |
| [B5G6R5](#B5G6R5) | 16‑битный формат пикселей, 5 бит красного, 6 бит зелёного, 5 бит синего. |
| [B8](#B8) | 8‑битный формат пикселей, все биты синего. |
| [B8G8R8](#B8G8R8) | 24‑битный формат пикселей, 8 бит для синего, зелёного и красного. |
| [B8G8R8A8](#B8G8R8A8) | 32‑битный формат пикселей, 8 бит для синего, зелёного, красного и альфа‑канала. |
| [BYTE_LA](#BYTE-LA) | 2‑байтовый формат пикселей, 1 байт яркости, 1 байт альфа‑канала |
| [DEPTH](#DEPTH) | Формат глубинной текстуры. |
| [DXT1](#DXT1) | Формат DDS (DirectDraw Surface) DXT1. |
| [DXT2](#DXT2) | Формат DDS (DirectDraw Surface) DXT2. |
| [DXT3](#DXT3) | Формат DDS (DirectDraw Surface) DXT3. |
| [DXT4](#DXT4) | Формат DDS (DirectDraw Surface) DXT4. |
| [DXT5](#DXT5) | Формат DDS (DirectDraw Surface) DXT5. |
| [FLOAT16_GR](#FLOAT16-GR) | 32-bit, 2-channel s10e5 floating point pixel format, 16-bit green, 16-bit red |
| [FLOAT16_R](#FLOAT16-R) | 16-bit pixel format, 16 bits (float) for red |
| [FLOAT16_RGB](#FLOAT16-RGB) | 48-bit pixel format, 16 bits (float) for red, 16 bits (float) for green, 16 bits (float) for blue |
| [FLOAT16_RGBA](#FLOAT16-RGBA) | 64-bit pixel format, 16 bits (float) for red, 16 bits (float) for green, 16 bits (float) for blue, 16 bits (float) for alpha |
| [FLOAT32_GR](#FLOAT32-GR) | 64-bit, 2-channel floating point pixel format, 32-bit green, 32-bit red |
| [FLOAT32_R](#FLOAT32-R) | 32-bit pixel format, 32 bits (float) for red |
| [FLOAT32_RGB](#FLOAT32-RGB) | 96-bit pixel format, 32 bits (float) for red, 32 bits (float) for green, 32 bits (float) for blue |
| [FLOAT32_RGBA](#FLOAT32-RGBA) | 128-bit pixel format, 32 bits (float) for red, 32 bits (float) for green, 32 bits (float) for blue, 32 bits (float) for alpha |
| [G8](#G8) | 8-bit pixel format, all bits green. |
| [L16](#L16) | 16-bit pixel format, all bits luminance. |
| [L8](#L8) | 8-bit pixel format, all bits luminance. |
| [R32G32B32A32_UINT](#R32G32B32A32-UINT) | 128-bit pixel format, 32 bits red (unsigned int), 32 bits blue (unsigned int), 32 bits green (unsigned int), 32 bits alpha (unsigned int). |
| [R32G32_UINT](#R32G32-UINT) | 64-bit pixel format, 32 bits red (unsigned int), 32 bits blue (unsigned int). |
| [R32_UINT](#R32-UINT) | 32-bit pixel format, 32 bits red (unsigned int). |
| [R3G3B2](#R3G3B2) | 8-bit pixel format, 2 bits blue, 3 bits green, 3 bits red. |
| [R5G6B5](#R5G6B5) | 16‑битный формат пикселей, 5 бит красного, 6 бит зелёного, 5 бит синего. |
| [R8](#R8) | 8-bit pixel format, all bits red. |
| [R8G8B8](#R8G8B8) | 24-bit pixel format, 8 bits for red, green and blue. |
| [R8G8B8A8](#R8G8B8A8) | 32-bit pixel format, 8 bits for red, green, blue and alpha. |
| [SHORT_GR](#SHORT-GR) | 32-bit pixel format, 16-bit green, 16-bit red |
| [SHORT_RGB](#SHORT-RGB) | 48-bit pixel format, 16 bits for red, green and blue |
| [SHORT_RGBA](#SHORT-RGBA) | 64-bit pixel format, 16 bits for red, green, blue and alpha |
| [UNKNOWN](#UNKNOWN) | Unknown pixel format. |
| [X8B8G8R8](#X8B8G8R8) | 32-bit pixel format, 8 bits for blue, 8 bits for green, 8 bits for red like A8B8G8R8, but alpha will get discarded |
| [X8R8G8B8](#X8R8G8B8) | 32-bit pixel format, 8 bits for red, 8 bits for green, 8 bits for blue like A8R8G8B8, but alpha will get discarded |
## Методы

| Метод | Описание |
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


16‑битный формат пикселей, 5 бит для синего, зелёного, красного и 1 бит для альфа‑канала.

### A2B10G10R10 {#A2B10G10R10}
```
public static final PixelFormat A2B10G10R10
```


32‑битный формат пикселей, 10 бит для синего, зелёного и красного, 2 бита для альфа‑канала.

### A2R10G10B10 {#A2R10G10B10}
```
public static final PixelFormat A2R10G10B10
```


32‑битный формат пикселей, 2 бита для альфа‑канала, 10 бит для красного, зелёного и синего.

### A4L4 {#A4L4}
```
public static final PixelFormat A4L4
```


8‑битный формат пикселей, 4 бита альфа, 4 бита яркости.

### A4R4G4B4 {#A4R4G4B4}
```
public static final PixelFormat A4R4G4B4
```


16‑битный формат пикселей, 4 бита для альфа, красного, зелёного и синего.

### A8 {#A8}
```
public static final PixelFormat A8
```


8‑битный формат пикселей, все биты альфа.

### A8B8G8R8 {#A8B8G8R8}
```
public static final PixelFormat A8B8G8R8
```


32‑битный формат пикселей, 8 бит для синего, зелёного, красного и альфа‑канала.

### A8R8G8B8 {#A8R8G8B8}
```
public static final PixelFormat A8R8G8B8
```


32‑битный формат пикселей, 8 бит для альфа‑канала, красного, зелёного и синего.

### B5G6R5 {#B5G6R5}
```
public static final PixelFormat B5G6R5
```


16‑битный формат пикселей, 5 бит красного, 6 бит зелёного, 5 бит синего.

### B8 {#B8}
```
public static final PixelFormat B8
```


8‑битный формат пикселей, все биты синего.

### B8G8R8 {#B8G8R8}
```
public static final PixelFormat B8G8R8
```


24‑битный формат пикселей, 8 бит для синего, зелёного и красного.

### B8G8R8A8 {#B8G8R8A8}
```
public static final PixelFormat B8G8R8A8
```


32‑битный формат пикселей, 8 бит для синего, зелёного, красного и альфа‑канала.

### BYTE_LA {#BYTE-LA}
```
public static final PixelFormat BYTE_LA
```


2‑байтовый формат пикселей, 1 байт яркости, 1 байт альфа‑канала

### DEPTH {#DEPTH}
```
public static final PixelFormat DEPTH
```


Формат глубинной текстуры.

### DXT1 {#DXT1}
```
public static final PixelFormat DXT1
```


Формат DDS (DirectDraw Surface) DXT1.

### DXT2 {#DXT2}
```
public static final PixelFormat DXT2
```


Формат DDS (DirectDraw Surface) DXT2.

### DXT3 {#DXT3}
```
public static final PixelFormat DXT3
```


Формат DDS (DirectDraw Surface) DXT3.

### DXT4 {#DXT4}
```
public static final PixelFormat DXT4
```


Формат DDS (DirectDraw Surface) DXT4.

### DXT5 {#DXT5}
```
public static final PixelFormat DXT5
```


Формат DDS (DirectDraw Surface) DXT5.

### FLOAT16_GR {#FLOAT16-GR}
```
public static final PixelFormat FLOAT16_GR
```


32-bit, 2-channel s10e5 floating point pixel format, 16-bit green, 16-bit red

### FLOAT16_R {#FLOAT16-R}
```
public static final PixelFormat FLOAT16_R
```


16-bit pixel format, 16 bits (float) for red

### FLOAT16_RGB {#FLOAT16-RGB}
```
public static final PixelFormat FLOAT16_RGB
```


48-bit pixel format, 16 bits (float) for red, 16 bits (float) for green, 16 bits (float) for blue

### FLOAT16_RGBA {#FLOAT16-RGBA}
```
public static final PixelFormat FLOAT16_RGBA
```


64-bit pixel format, 16 bits (float) for red, 16 bits (float) for green, 16 bits (float) for blue, 16 bits (float) for alpha

### FLOAT32_GR {#FLOAT32-GR}
```
public static final PixelFormat FLOAT32_GR
```


64-bit, 2-channel floating point pixel format, 32-bit green, 32-bit red

### FLOAT32_R {#FLOAT32-R}
```
public static final PixelFormat FLOAT32_R
```


32-bit pixel format, 32 bits (float) for red

### FLOAT32_RGB {#FLOAT32-RGB}
```
public static final PixelFormat FLOAT32_RGB
```


96-bit pixel format, 32 bits (float) for red, 32 bits (float) for green, 32 bits (float) for blue

### FLOAT32_RGBA {#FLOAT32-RGBA}
```
public static final PixelFormat FLOAT32_RGBA
```


128-bit pixel format, 32 bits (float) for red, 32 bits (float) for green, 32 bits (float) for blue, 32 bits (float) for alpha

### G8 {#G8}
```
public static final PixelFormat G8
```


8-bit pixel format, all bits green.

### L16 {#L16}
```
public static final PixelFormat L16
```


16-bit pixel format, all bits luminance.

### L8 {#L8}
```
public static final PixelFormat L8
```


8-bit pixel format, all bits luminance.

### R32G32B32A32_UINT {#R32G32B32A32-UINT}
```
public static final PixelFormat R32G32B32A32_UINT
```


128-bit pixel format, 32 bits red (unsigned int), 32 bits blue (unsigned int), 32 bits green (unsigned int), 32 bits alpha (unsigned int).

### R32G32_UINT {#R32G32-UINT}
```
public static final PixelFormat R32G32_UINT
```


64-bit pixel format, 32 bits red (unsigned int), 32 bits blue (unsigned int).

### R32_UINT {#R32-UINT}
```
public static final PixelFormat R32_UINT
```


32-bit pixel format, 32 bits red (unsigned int).

### R3G3B2 {#R3G3B2}
```
public static final PixelFormat R3G3B2
```


8-bit pixel format, 2 bits blue, 3 bits green, 3 bits red.

### R5G6B5 {#R5G6B5}
```
public static final PixelFormat R5G6B5
```


16‑битный формат пикселей, 5 бит красного, 6 бит зелёного, 5 бит синего.

### R8 {#R8}
```
public static final PixelFormat R8
```


8-bit pixel format, all bits red.

### R8G8B8 {#R8G8B8}
```
public static final PixelFormat R8G8B8
```


24-bit pixel format, 8 bits for red, green and blue.

### R8G8B8A8 {#R8G8B8A8}
```
public static final PixelFormat R8G8B8A8
```


32-bit pixel format, 8 bits for red, green, blue and alpha.

### SHORT_GR {#SHORT-GR}
```
public static final PixelFormat SHORT_GR
```


32-bit pixel format, 16-bit green, 16-bit red

### SHORT_RGB {#SHORT-RGB}
```
public static final PixelFormat SHORT_RGB
```


48-bit pixel format, 16 bits for red, green and blue

### SHORT_RGBA {#SHORT-RGBA}
```
public static final PixelFormat SHORT_RGBA
```


64-bit pixel format, 16 bits for red, green, blue and alpha

### UNKNOWN {#UNKNOWN}
```
public static final PixelFormat UNKNOWN
```


Unknown pixel format.

### X8B8G8R8 {#X8B8G8R8}
```
public static final PixelFormat X8B8G8R8
```


32-bit pixel format, 8 bits for blue, 8 bits for green, 8 bits for red like A8B8G8R8, but alpha will get discarded

### X8R8G8B8 {#X8R8G8B8}
```
public static final PixelFormat X8R8G8B8
```


32-bit pixel format, 8 bits for red, 8 bits for green, 8 bits for blue like A8R8G8B8, but alpha will get discarded

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

