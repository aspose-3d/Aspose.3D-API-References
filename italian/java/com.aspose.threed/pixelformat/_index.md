---
title: PixelFormat
second_title: Aspose.3D for Java API Reference
description: Il formato dei pixel utilizzato nell'unità di texture.
type: docs
weight: 290
url: /it/java/com.aspose.threed/pixelformat/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PixelFormat extends Enum<PixelFormat>
```

Il formato del pixel utilizzato nell'unità di texture.
## Campi

| Campo | Descrizione |
| --- | --- |
| [A1R5G5B5](#A1R5G5B5) | Formato pixel a 16 bit, 5 bit per blu, verde, rosso e 1 per alfa. |
| [A2B10G10R10](#A2B10G10R10) | Formato pixel a 32 bit, 10 bit per blu, verde e rosso, 2 bit per alfa. |
| [A2R10G10B10](#A2R10G10B10) | Formato pixel a 32 bit, 2 bit per alfa, 10 bit per rosso, verde e blu. |
| [A4L4](#A4L4) | Formato pixel a 8 bit, 4 bit alfa, 4 bit luminanza. |
| [A4R4G4B4](#A4R4G4B4) | Formato pixel a 16 bit, 4 bit per alfa, rosso, verde e blu. |
| [A8](#A8) | Formato pixel a 8 bit, tutti i bit alfa. |
| [A8B8G8R8](#A8B8G8R8) | Formato pixel a 32 bit, 8 bit per blu, verde, rosso e alfa. |
| [A8R8G8B8](#A8R8G8B8) | Formato pixel a 32 bit, 8 bit per alfa, rosso, verde e blu. |
| [B5G6R5](#B5G6R5) | Formato pixel a 16 bit, 5 bit rosso, 6 bit verde, 5 bit blu. |
| [B8](#B8) | Formato pixel a 8 bit, tutti i bit blu. |
| [B8G8R8](#B8G8R8) | Formato pixel a 24 bit, 8 bit per blu, verde e rosso. |
| [B8G8R8A8](#B8G8R8A8) | Formato pixel a 32 bit, 8 bit per blu, verde, rosso e alfa. |
| [BYTE_LA](#BYTE-LA) | Formato pixel a 2 byte, 1 byte luminanza, 1 byte alfa |
| [DEPTH](#DEPTH) | Formato texture di profondità. |
| [DXT1](#DXT1) | Formato DDS (DirectDraw Surface) DXT1. |
| [DXT2](#DXT2) | Formato DDS (DirectDraw Surface) DXT2. |
| [DXT3](#DXT3) | Formato DDS (DirectDraw Surface) DXT3. |
| [DXT4](#DXT4) | Formato DDS (DirectDraw Surface) DXT4. |
| [DXT5](#DXT5) | Formato DDS (DirectDraw Surface) DXT5. |
| [FLOAT16_GR](#FLOAT16-GR) | Formato pixel a 32 bit, 2 canali, 16 bit verde, 16 bit rosso |
| [FLOAT16_R](#FLOAT16-R) | Formato pixel a 16 bit, 16 bit (float) per il rosso |
| [FLOAT16_RGB](#FLOAT16-RGB) | Formato pixel a 48 bit, 16 bit (float) per il rosso, 16 bit (float) per il verde, 16 bit (float) per il blu |
| [FLOAT16_RGBA](#FLOAT16-RGBA) | Formato pixel a 64 bit, 16 bit (float) per il rosso, 16 bit (float) per il verde, 16 bit (float) per il blu, 16 bit (float) per l'alpha |
| [FLOAT32_GR](#FLOAT32-GR) | Formato pixel a virgola mobile a 64 bit, 2 canali, 32 bit verde, 32 bit rosso |
| [FLOAT32_R](#FLOAT32-R) | Formato pixel a 32 bit, 32 bit (float) per il rosso |
| [FLOAT32_RGB](#FLOAT32-RGB) | Formato pixel a 96 bit, 32 bit (float) per il rosso, 32 bit (float) per il verde, 32 bit (float) per il blu |
| [FLOAT32_RGBA](#FLOAT32-RGBA) | Formato pixel a 128 bit, 32 bit (float) per il rosso, 32 bit (float) per il verde, 32 bit (float) per il blu, 32 bit (float) per l'alpha |
| [G8](#G8) | Formato pixel a 8 bit, tutti i bit verde. |
| [L16](#L16) | Formato pixel a 16 bit, tutti i bit luminanza. |
| [L8](#L8) | Formato pixel a 8 bit, tutti i bit luminanza. |
| [R32G32B32A32_UINT](#R32G32B32A32-UINT) | Formato pixel a 128 bit, 32 bit rosso (unsigned int), 32 bit blu (unsigned int), 32 bit verde (unsigned int), 32 bit alpha (unsigned int). |
| [R32G32_UINT](#R32G32-UINT) | Formato pixel a 64 bit, 32 bit rosso (unsigned int), 32 bit blu (unsigned int). |
| [R32_UINT](#R32-UINT) | Formato pixel a 32 bit, 32 bit rosso (unsigned int). |
| [R3G3B2](#R3G3B2) | Formato pixel a 8 bit, 2 bit blu, 3 bit verde, 3 bit rosso. |
| [R5G6B5](#R5G6B5) | Formato pixel a 16 bit, 5 bit rosso, 6 bit verde, 5 bit blu. |
| [R8](#R8) | Formato pixel a 8 bit, tutti i bit rosso. |
| [R8G8B8](#R8G8B8) | Formato pixel a 24 bit, 8 bit per rosso, verde e blu. |
| [R8G8B8A8](#R8G8B8A8) | Formato pixel a 32 bit, 8 bit per rosso, verde, blu e alpha. |
| [SHORT_GR](#SHORT-GR) | Formato pixel a 32 bit, 16 bit verde, 16 bit rosso |
| [SHORT_RGB](#SHORT-RGB) | Formato pixel a 48 bit, 16 bit per rosso, verde e blu |
| [SHORT_RGBA](#SHORT-RGBA) | Formato pixel a 64 bit, 16 bit per rosso, verde, blu e alpha |
| [UNKNOWN](#UNKNOWN) | Formato pixel sconosciuto. |
| [X8B8G8R8](#X8B8G8R8) | Formato pixel a 32 bit, 8 bit per blu, 8 bit per verde, 8 bit per rosso come A8B8G8R8, ma l'alpha verrà scartato |
| [X8R8G8B8](#X8R8G8B8) | Formato pixel a 32 bit, 8 bit per rosso, 8 bit per verde, 8 bit per blu come A8R8G8B8, ma l'alpha verrà scartato |
## Metodi

| Metodo | Descrizione |
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


Formato pixel a 16 bit, 5 bit per blu, verde, rosso e 1 per alfa.

### A2B10G10R10 {#A2B10G10R10}
```
public static final PixelFormat A2B10G10R10
```


Formato pixel a 32 bit, 10 bit per blu, verde e rosso, 2 bit per alfa.

### A2R10G10B10 {#A2R10G10B10}
```
public static final PixelFormat A2R10G10B10
```


Formato pixel a 32 bit, 2 bit per alfa, 10 bit per rosso, verde e blu.

### A4L4 {#A4L4}
```
public static final PixelFormat A4L4
```


Formato pixel a 8 bit, 4 bit alfa, 4 bit luminanza.

### A4R4G4B4 {#A4R4G4B4}
```
public static final PixelFormat A4R4G4B4
```


Formato pixel a 16 bit, 4 bit per alfa, rosso, verde e blu.

### A8 {#A8}
```
public static final PixelFormat A8
```


Formato pixel a 8 bit, tutti i bit alfa.

### A8B8G8R8 {#A8B8G8R8}
```
public static final PixelFormat A8B8G8R8
```


Formato pixel a 32 bit, 8 bit per blu, verde, rosso e alfa.

### A8R8G8B8 {#A8R8G8B8}
```
public static final PixelFormat A8R8G8B8
```


Formato pixel a 32 bit, 8 bit per alfa, rosso, verde e blu.

### B5G6R5 {#B5G6R5}
```
public static final PixelFormat B5G6R5
```


Formato pixel a 16 bit, 5 bit rosso, 6 bit verde, 5 bit blu.

### B8 {#B8}
```
public static final PixelFormat B8
```


Formato pixel a 8 bit, tutti i bit blu.

### B8G8R8 {#B8G8R8}
```
public static final PixelFormat B8G8R8
```


Formato pixel a 24 bit, 8 bit per blu, verde e rosso.

### B8G8R8A8 {#B8G8R8A8}
```
public static final PixelFormat B8G8R8A8
```


Formato pixel a 32 bit, 8 bit per blu, verde, rosso e alfa.

### BYTE_LA {#BYTE-LA}
```
public static final PixelFormat BYTE_LA
```


Formato pixel a 2 byte, 1 byte luminanza, 1 byte alfa

### DEPTH {#DEPTH}
```
public static final PixelFormat DEPTH
```


Formato texture di profondità.

### DXT1 {#DXT1}
```
public static final PixelFormat DXT1
```


Formato DDS (DirectDraw Surface) DXT1.

### DXT2 {#DXT2}
```
public static final PixelFormat DXT2
```


Formato DDS (DirectDraw Surface) DXT2.

### DXT3 {#DXT3}
```
public static final PixelFormat DXT3
```


Formato DDS (DirectDraw Surface) DXT3.

### DXT4 {#DXT4}
```
public static final PixelFormat DXT4
```


Formato DDS (DirectDraw Surface) DXT4.

### DXT5 {#DXT5}
```
public static final PixelFormat DXT5
```


Formato DDS (DirectDraw Surface) DXT5.

### FLOAT16_GR {#FLOAT16-GR}
```
public static final PixelFormat FLOAT16_GR
```


Formato pixel a 32 bit, 2 canali, 16 bit verde, 16 bit rosso

### FLOAT16_R {#FLOAT16-R}
```
public static final PixelFormat FLOAT16_R
```


Formato pixel a 16 bit, 16 bit (float) per il rosso

### FLOAT16_RGB {#FLOAT16-RGB}
```
public static final PixelFormat FLOAT16_RGB
```


Formato pixel a 48 bit, 16 bit (float) per il rosso, 16 bit (float) per il verde, 16 bit (float) per il blu

### FLOAT16_RGBA {#FLOAT16-RGBA}
```
public static final PixelFormat FLOAT16_RGBA
```


Formato pixel a 64 bit, 16 bit (float) per il rosso, 16 bit (float) per il verde, 16 bit (float) per il blu, 16 bit (float) per l'alpha

### FLOAT32_GR {#FLOAT32-GR}
```
public static final PixelFormat FLOAT32_GR
```


Formato pixel a virgola mobile a 64 bit, 2 canali, 32 bit verde, 32 bit rosso

### FLOAT32_R {#FLOAT32-R}
```
public static final PixelFormat FLOAT32_R
```


Formato pixel a 32 bit, 32 bit (float) per il rosso

### FLOAT32_RGB {#FLOAT32-RGB}
```
public static final PixelFormat FLOAT32_RGB
```


Formato pixel a 96 bit, 32 bit (float) per il rosso, 32 bit (float) per il verde, 32 bit (float) per il blu

### FLOAT32_RGBA {#FLOAT32-RGBA}
```
public static final PixelFormat FLOAT32_RGBA
```


Formato pixel a 128 bit, 32 bit (float) per il rosso, 32 bit (float) per il verde, 32 bit (float) per il blu, 32 bit (float) per l'alpha

### G8 {#G8}
```
public static final PixelFormat G8
```


Formato pixel a 8 bit, tutti i bit verde.

### L16 {#L16}
```
public static final PixelFormat L16
```


Formato pixel a 16 bit, tutti i bit luminanza.

### L8 {#L8}
```
public static final PixelFormat L8
```


Formato pixel a 8 bit, tutti i bit luminanza.

### R32G32B32A32_UINT {#R32G32B32A32-UINT}
```
public static final PixelFormat R32G32B32A32_UINT
```


Formato pixel a 128 bit, 32 bit rosso (unsigned int), 32 bit blu (unsigned int), 32 bit verde (unsigned int), 32 bit alpha (unsigned int).

### R32G32_UINT {#R32G32-UINT}
```
public static final PixelFormat R32G32_UINT
```


Formato pixel a 64 bit, 32 bit rosso (unsigned int), 32 bit blu (unsigned int).

### R32_UINT {#R32-UINT}
```
public static final PixelFormat R32_UINT
```


Formato pixel a 32 bit, 32 bit rosso (unsigned int).

### R3G3B2 {#R3G3B2}
```
public static final PixelFormat R3G3B2
```


Formato pixel a 8 bit, 2 bit blu, 3 bit verde, 3 bit rosso.

### R5G6B5 {#R5G6B5}
```
public static final PixelFormat R5G6B5
```


Formato pixel a 16 bit, 5 bit rosso, 6 bit verde, 5 bit blu.

### R8 {#R8}
```
public static final PixelFormat R8
```


Formato pixel a 8 bit, tutti i bit rosso.

### R8G8B8 {#R8G8B8}
```
public static final PixelFormat R8G8B8
```


Formato pixel a 24 bit, 8 bit per rosso, verde e blu.

### R8G8B8A8 {#R8G8B8A8}
```
public static final PixelFormat R8G8B8A8
```


Formato pixel a 32 bit, 8 bit per rosso, verde, blu e alpha.

### SHORT_GR {#SHORT-GR}
```
public static final PixelFormat SHORT_GR
```


Formato pixel a 32 bit, 16 bit verde, 16 bit rosso

### SHORT_RGB {#SHORT-RGB}
```
public static final PixelFormat SHORT_RGB
```


Formato pixel a 48 bit, 16 bit per rosso, verde e blu

### SHORT_RGBA {#SHORT-RGBA}
```
public static final PixelFormat SHORT_RGBA
```


Formato pixel a 64 bit, 16 bit per rosso, verde, blu e alpha

### UNKNOWN {#UNKNOWN}
```
public static final PixelFormat UNKNOWN
```


Formato pixel sconosciuto.

### X8B8G8R8 {#X8B8G8R8}
```
public static final PixelFormat X8B8G8R8
```


Formato pixel a 32 bit, 8 bit per blu, 8 bit per verde, 8 bit per rosso come A8B8G8R8, ma l'alpha verrà scartato

### X8R8G8B8 {#X8R8G8B8}
```
public static final PixelFormat X8R8G8B8
```


Formato pixel a 32 bit, 8 bit per rosso, 8 bit per verde, 8 bit per blu come A8R8G8B8, ma l'alpha verrà scartato

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

