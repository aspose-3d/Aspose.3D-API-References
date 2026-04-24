---
title: PixelFormat
second_title: Aspose.3D for Java API-referentie
description: Het pixelformaat dat wordt gebruikt in de texture-eenheid.
type: docs
weight: 290
url: /nl/java/com.aspose.threed/pixelformat/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PixelFormat extends Enum<PixelFormat>
```

Het pixelformaat dat wordt gebruikt in de texture-eenheid.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [A1R5G5B5](#A1R5G5B5) | 16-bits pixelformaat, 5 bits voor blauw, groen, rood en 1 voor alfa. |
| [A2B10G10R10](#A2B10G10R10) | 32-bits pixelformaat, 10 bits voor blauw, groen en rood, 2 bits voor alfa. |
| [A2R10G10B10](#A2R10G10B10) | 32-bits pixelformaat, 2 bits voor alfa, 10 bits voor rood, groen en blauw. |
| [A4L4](#A4L4) | 8-bits pixelformaat, 4 bits alfa, 4 bits luminantie. |
| [A4R4G4B4](#A4R4G4B4) | 16-bits pixelformaat, 4 bits voor alfa, rood, groen en blauw. |
| [A8](#A8) | 8-bits pixelformaat, alle bits alfa. |
| [A8B8G8R8](#A8B8G8R8) | 32-bits pixelformaat, 8 bits voor blauw, groen, rood en alfa. |
| [A8R8G8B8](#A8R8G8B8) | 32-bits pixelformaat, 8 bits voor alfa, rood, groen en blauw. |
| [B5G6R5](#B5G6R5) | 16-bits pixelformaat, 5 bits rood, 6 bits groen, 5 bits blauw. |
| [B8](#B8) | 8-bits pixelformaat, alle bits blauw. |
| [B8G8R8](#B8G8R8) | 24-bits pixelformaat, 8 bits voor blauw, groen en rood. |
| [B8G8R8A8](#B8G8R8A8) | 32-bits pixelformaat, 8 bits voor blauw, groen, rood en alfa. |
| [BYTE_LA](#BYTE-LA) | 2-byte pixelformaat, 1 byte luminantie, 1 byte alfa |
| [DEPTH](#DEPTH) | Diepte-textureformaat. |
| [DXT1](#DXT1) | DDS (DirectDraw Surface) DXT1-formaat. |
| [DXT2](#DXT2) | DDS (DirectDraw Surface) DXT2-formaat. |
| [DXT3](#DXT3) | DDS (DirectDraw Surface) DXT3-formaat. |
| [DXT4](#DXT4) | DDS (DirectDraw Surface) DXT4-formaat. |
| [DXT5](#DXT5) | DDS (DirectDraw Surface) DXT5-formaat. |
| [FLOAT16_GR](#FLOAT16-GR) | 32-bit, 2-kanaals s10e5 floating point pixelindeling, 16-bit groen, 16-bit rood |
| [FLOAT16_R](#FLOAT16-R) | 16-bit pixelindeling, 16 bits (float) voor rood |
| [FLOAT16_RGB](#FLOAT16-RGB) | 48-bit pixelindeling, 16 bits (float) voor rood, 16 bits (float) voor groen, 16 bits (float) voor blauw |
| [FLOAT16_RGBA](#FLOAT16-RGBA) | 64-bit pixelindeling, 16 bits (float) voor rood, 16 bits (float) voor groen, 16 bits (float) voor blauw, 16 bits (float) voor alfa |
| [FLOAT32_GR](#FLOAT32-GR) | 64-bit, 2-kanaals floating point pixelindeling, 32-bit groen, 32-bit rood |
| [FLOAT32_R](#FLOAT32-R) | 32-bit pixelindeling, 32 bits (float) voor rood |
| [FLOAT32_RGB](#FLOAT32-RGB) | 96-bit pixelindeling, 32 bits (float) voor rood, 32 bits (float) voor groen, 32 bits (float) voor blauw |
| [FLOAT32_RGBA](#FLOAT32-RGBA) | 128-bit pixelindeling, 32 bits (float) voor rood, 32 bits (float) voor groen, 32 bits (float) voor blauw, 32 bits (float) voor alfa |
| [G8](#G8) | 8-bit pixelindeling, alle bits groen. |
| [L16](#L16) | 16-bit pixelindeling, alle bits luminantie. |
| [L8](#L8) | 8-bit pixelindeling, alle bits luminantie. |
| [R32G32B32A32_UINT](#R32G32B32A32-UINT) | 128-bit pixelindeling, 32 bits rood (unsigned int), 32 bits blauw (unsigned int), 32 bits groen (unsigned int), 32 bits alfa (unsigned int). |
| [R32G32_UINT](#R32G32-UINT) | 64-bit pixelindeling, 32 bits rood (unsigned int), 32 bits blauw (unsigned int). |
| [R32_UINT](#R32-UINT) | 32-bit pixelindeling, 32 bits rood (unsigned int). |
| [R3G3B2](#R3G3B2) | 8-bit pixelindeling, 2 bits blauw, 3 bits groen, 3 bits rood. |
| [R5G6B5](#R5G6B5) | 16-bits pixelformaat, 5 bits rood, 6 bits groen, 5 bits blauw. |
| [R8](#R8) | 8-bit pixelindeling, alle bits rood. |
| [R8G8B8](#R8G8B8) | 24-bit pixelindeling, 8 bits voor rood, groen en blauw. |
| [R8G8B8A8](#R8G8B8A8) | 32-bit pixelindeling, 8 bits voor rood, groen, blauw en alfa. |
| [SHORT_GR](#SHORT-GR) | 32-bit pixelindeling, 16-bit groen, 16-bit rood |
| [SHORT_RGB](#SHORT-RGB) | 48-bit pixelindeling, 16 bits voor rood, groen en blauw |
| [SHORT_RGBA](#SHORT-RGBA) | 64-bit pixelindeling, 16 bits voor rood, groen, blauw en alfa |
| [UNKNOWN](#UNKNOWN) | Onbekende pixelindeling. |
| [X8B8G8R8](#X8B8G8R8) | 32-bit pixelindeling, 8 bits voor blauw, 8 bits voor groen, 8 bits voor rood zoals A8B8G8R8, maar alfa wordt weggegooid |
| [X8R8G8B8](#X8R8G8B8) | 32-bit pixelindeling, 8 bits voor rood, 8 bits voor groen, 8 bits voor blauw zoals A8R8G8B8, maar alfa wordt weggegooid |
## Methoden

| Methode | Beschrijving |
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


16-bits pixelformaat, 5 bits voor blauw, groen, rood en 1 voor alfa.

### A2B10G10R10 {#A2B10G10R10}
```
public static final PixelFormat A2B10G10R10
```


32-bits pixelformaat, 10 bits voor blauw, groen en rood, 2 bits voor alfa.

### A2R10G10B10 {#A2R10G10B10}
```
public static final PixelFormat A2R10G10B10
```


32-bits pixelformaat, 2 bits voor alfa, 10 bits voor rood, groen en blauw.

### A4L4 {#A4L4}
```
public static final PixelFormat A4L4
```


8-bits pixelformaat, 4 bits alfa, 4 bits luminantie.

### A4R4G4B4 {#A4R4G4B4}
```
public static final PixelFormat A4R4G4B4
```


16-bits pixelformaat, 4 bits voor alfa, rood, groen en blauw.

### A8 {#A8}
```
public static final PixelFormat A8
```


8-bits pixelformaat, alle bits alfa.

### A8B8G8R8 {#A8B8G8R8}
```
public static final PixelFormat A8B8G8R8
```


32-bits pixelformaat, 8 bits voor blauw, groen, rood en alfa.

### A8R8G8B8 {#A8R8G8B8}
```
public static final PixelFormat A8R8G8B8
```


32-bits pixelformaat, 8 bits voor alfa, rood, groen en blauw.

### B5G6R5 {#B5G6R5}
```
public static final PixelFormat B5G6R5
```


16-bits pixelformaat, 5 bits rood, 6 bits groen, 5 bits blauw.

### B8 {#B8}
```
public static final PixelFormat B8
```


8-bits pixelformaat, alle bits blauw.

### B8G8R8 {#B8G8R8}
```
public static final PixelFormat B8G8R8
```


24-bits pixelformaat, 8 bits voor blauw, groen en rood.

### B8G8R8A8 {#B8G8R8A8}
```
public static final PixelFormat B8G8R8A8
```


32-bits pixelformaat, 8 bits voor blauw, groen, rood en alfa.

### BYTE_LA {#BYTE-LA}
```
public static final PixelFormat BYTE_LA
```


2-byte pixelformaat, 1 byte luminantie, 1 byte alfa

### DEPTH {#DEPTH}
```
public static final PixelFormat DEPTH
```


Diepte-textureformaat.

### DXT1 {#DXT1}
```
public static final PixelFormat DXT1
```


DDS (DirectDraw Surface) DXT1-formaat.

### DXT2 {#DXT2}
```
public static final PixelFormat DXT2
```


DDS (DirectDraw Surface) DXT2-formaat.

### DXT3 {#DXT3}
```
public static final PixelFormat DXT3
```


DDS (DirectDraw Surface) DXT3-formaat.

### DXT4 {#DXT4}
```
public static final PixelFormat DXT4
```


DDS (DirectDraw Surface) DXT4-formaat.

### DXT5 {#DXT5}
```
public static final PixelFormat DXT5
```


DDS (DirectDraw Surface) DXT5-formaat.

### FLOAT16_GR {#FLOAT16-GR}
```
public static final PixelFormat FLOAT16_GR
```


32-bit, 2-kanaals s10e5 floating point pixelindeling, 16-bit groen, 16-bit rood

### FLOAT16_R {#FLOAT16-R}
```
public static final PixelFormat FLOAT16_R
```


16-bit pixelindeling, 16 bits (float) voor rood

### FLOAT16_RGB {#FLOAT16-RGB}
```
public static final PixelFormat FLOAT16_RGB
```


48-bit pixelindeling, 16 bits (float) voor rood, 16 bits (float) voor groen, 16 bits (float) voor blauw

### FLOAT16_RGBA {#FLOAT16-RGBA}
```
public static final PixelFormat FLOAT16_RGBA
```


64-bit pixelindeling, 16 bits (float) voor rood, 16 bits (float) voor groen, 16 bits (float) voor blauw, 16 bits (float) voor alfa

### FLOAT32_GR {#FLOAT32-GR}
```
public static final PixelFormat FLOAT32_GR
```


64-bit, 2-kanaals floating point pixelindeling, 32-bit groen, 32-bit rood

### FLOAT32_R {#FLOAT32-R}
```
public static final PixelFormat FLOAT32_R
```


32-bit pixelindeling, 32 bits (float) voor rood

### FLOAT32_RGB {#FLOAT32-RGB}
```
public static final PixelFormat FLOAT32_RGB
```


96-bit pixelindeling, 32 bits (float) voor rood, 32 bits (float) voor groen, 32 bits (float) voor blauw

### FLOAT32_RGBA {#FLOAT32-RGBA}
```
public static final PixelFormat FLOAT32_RGBA
```


128-bit pixelindeling, 32 bits (float) voor rood, 32 bits (float) voor groen, 32 bits (float) voor blauw, 32 bits (float) voor alfa

### G8 {#G8}
```
public static final PixelFormat G8
```


8-bit pixelindeling, alle bits groen.

### L16 {#L16}
```
public static final PixelFormat L16
```


16-bit pixelindeling, alle bits luminantie.

### L8 {#L8}
```
public static final PixelFormat L8
```


8-bit pixelindeling, alle bits luminantie.

### R32G32B32A32_UINT {#R32G32B32A32-UINT}
```
public static final PixelFormat R32G32B32A32_UINT
```


128-bit pixelindeling, 32 bits rood (unsigned int), 32 bits blauw (unsigned int), 32 bits groen (unsigned int), 32 bits alfa (unsigned int).

### R32G32_UINT {#R32G32-UINT}
```
public static final PixelFormat R32G32_UINT
```


64-bit pixelindeling, 32 bits rood (unsigned int), 32 bits blauw (unsigned int).

### R32_UINT {#R32-UINT}
```
public static final PixelFormat R32_UINT
```


32-bit pixelindeling, 32 bits rood (unsigned int).

### R3G3B2 {#R3G3B2}
```
public static final PixelFormat R3G3B2
```


8-bit pixelindeling, 2 bits blauw, 3 bits groen, 3 bits rood.

### R5G6B5 {#R5G6B5}
```
public static final PixelFormat R5G6B5
```


16-bits pixelformaat, 5 bits rood, 6 bits groen, 5 bits blauw.

### R8 {#R8}
```
public static final PixelFormat R8
```


8-bit pixelindeling, alle bits rood.

### R8G8B8 {#R8G8B8}
```
public static final PixelFormat R8G8B8
```


24-bit pixelindeling, 8 bits voor rood, groen en blauw.

### R8G8B8A8 {#R8G8B8A8}
```
public static final PixelFormat R8G8B8A8
```


32-bit pixelindeling, 8 bits voor rood, groen, blauw en alfa.

### SHORT_GR {#SHORT-GR}
```
public static final PixelFormat SHORT_GR
```


32-bit pixelindeling, 16-bit groen, 16-bit rood

### SHORT_RGB {#SHORT-RGB}
```
public static final PixelFormat SHORT_RGB
```


48-bit pixelindeling, 16 bits voor rood, groen en blauw

### SHORT_RGBA {#SHORT-RGBA}
```
public static final PixelFormat SHORT_RGBA
```


64-bit pixelindeling, 16 bits voor rood, groen, blauw en alfa

### UNKNOWN {#UNKNOWN}
```
public static final PixelFormat UNKNOWN
```


Onbekende pixelindeling.

### X8B8G8R8 {#X8B8G8R8}
```
public static final PixelFormat X8B8G8R8
```


32-bit pixelindeling, 8 bits voor blauw, 8 bits voor groen, 8 bits voor rood zoals A8B8G8R8, maar alfa wordt weggegooid

### X8R8G8B8 {#X8R8G8B8}
```
public static final PixelFormat X8R8G8B8
```


32-bit pixelindeling, 8 bits voor rood, 8 bits voor groen, 8 bits voor blauw zoals A8R8G8B8, maar alfa wordt weggegooid

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

