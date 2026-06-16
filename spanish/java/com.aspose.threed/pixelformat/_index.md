---
title: PixelFormat
second_title: Referencia de API de Aspose.3D para Java
description: El formato de píxeles usado en la unidad de textura.
type: docs
weight: 290
url: /es/java/com.aspose.threed/pixelformat/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PixelFormat extends Enum<PixelFormat>
```

El formato del píxel usado en la unidad de textura
## Campos

| Campo | Descripción |
| --- | --- |
| [A1R5G5B5](#A1R5G5B5) | Formato de píxel de 16 bits, 5 bits para azul, verde, rojo y 1 para alfa. |
| [A2B10G10R10](#A2B10G10R10) | Formato de píxel de 32 bits, 10 bits para azul, verde y rojo, 2 bits para alfa. |
| [A2R10G10B10](#A2R10G10B10) | Formato de píxel de 32 bits, 2 bits para alfa, 10 bits para rojo, verde y azul. |
| [A4L4](#A4L4) | Formato de píxel de 8 bits, 4 bits alfa, 4 bits luminancia. |
| [A4R4G4B4](#A4R4G4B4) | Formato de píxel de 16 bits, 4 bits para alfa, rojo, verde y azul. |
| [A8](#A8) | Formato de píxel de 8 bits, todos los bits alfa. |
| [A8B8G8R8](#A8B8G8R8) | Formato de píxel de 32 bits, 8 bits para azul, verde, rojo y alfa. |
| [A8R8G8B8](#A8R8G8B8) | Formato de píxel de 32 bits, 8 bits para alfa, rojo, verde y azul. |
| [B5G6R5](#B5G6R5) | Formato de píxel de 16 bits, 5 bits rojo, 6 bits verde, 5 bits azul. |
| [B8](#B8) | Formato de píxel de 8 bits, todos los bits azul. |
| [B8G8R8](#B8G8R8) | Formato de píxel de 24 bits, 8 bits para azul, verde y rojo. |
| [B8G8R8A8](#B8G8R8A8) | Formato de píxel de 32 bits, 8 bits para azul, verde, rojo y alfa. |
| [BYTE_LA](#BYTE-LA) | Formato de píxel de 2 bytes, 1 byte de luminancia, 1 byte alfa |
| [DEPTH](#DEPTH) | Formato de textura de profundidad. |
| [DXT1](#DXT1) | Formato DDS (DirectDraw Surface) DXT1. |
| [DXT2](#DXT2) | Formato DDS (DirectDraw Surface) DXT2. |
| [DXT3](#DXT3) | Formato DDS (DirectDraw Surface) DXT3. |
| [DXT4](#DXT4) | Formato DDS (DirectDraw Surface) DXT4. |
| [DXT5](#DXT5) | Formato DDS (DirectDraw Surface) DXT5. |
| [FLOAT16_GR](#FLOAT16-GR) | Formato de píxel de punto flotante s10e5 de 32 bits, 2 canales, 16 bits verde, 16 bits rojo |
| [FLOAT16_R](#FLOAT16-R) | Formato de píxel de 16 bits, 16 bits (float) para rojo |
| [FLOAT16_RGB](#FLOAT16-RGB) | Formato de píxel de 48 bits, 16 bits (float) para rojo, 16 bits (float) para verde, 16 bits (float) para azul |
| [FLOAT16_RGBA](#FLOAT16-RGBA) | Formato de píxel de 64 bits, 16 bits (float) para rojo, 16 bits (float) para verde, 16 bits (float) para azul, 16 bits (float) para alfa |
| [FLOAT32_GR](#FLOAT32-GR) | Formato de píxel de punto flotante de 64 bits, 2 canales, 32 bits verde, 32 bits rojo |
| [FLOAT32_R](#FLOAT32-R) | Formato de píxel de 32 bits, 32 bits (float) para rojo |
| [FLOAT32_RGB](#FLOAT32-RGB) | Formato de píxel de 96 bits, 32 bits (float) para rojo, 32 bits (float) para verde, 32 bits (float) para azul |
| [FLOAT32_RGBA](#FLOAT32-RGBA) | Formato de píxel de 128 bits, 32 bits (float) para rojo, 32 bits (float) para verde, 32 bits (float) para azul, 32 bits (float) para alfa |
| [G8](#G8) | Formato de píxel de 8 bits, todos los bits verde. |
| [L16](#L16) | Formato de píxel de 16 bits, todos los bits luminancia. |
| [L8](#L8) | Formato de píxel de 8 bits, todos los bits luminancia. |
| [R32G32B32A32_UINT](#R32G32B32A32-UINT) | Formato de píxel de 128 bits, 32 bits rojo (entero sin signo), 32 bits azul (entero sin signo), 32 bits verde (entero sin signo), 32 bits alfa (entero sin signo). |
| [R32G32_UINT](#R32G32-UINT) | Formato de píxel de 64 bits, 32 bits rojo (entero sin signo), 32 bits azul (entero sin signo). |
| [R32_UINT](#R32-UINT) | Formato de píxel de 32 bits, 32 bits rojo (entero sin signo). |
| [R3G3B2](#R3G3B2) | Formato de píxel de 8 bits, 2 bits azul, 3 bits verde, 3 bits rojo. |
| [R5G6B5](#R5G6B5) | Formato de píxel de 16 bits, 5 bits rojo, 6 bits verde, 5 bits azul. |
| [R8](#R8) | Formato de píxel de 8 bits, todos los bits rojo. |
| [R8G8B8](#R8G8B8) | Formato de píxel de 24 bits, 8 bits para rojo, verde y azul. |
| [R8G8B8A8](#R8G8B8A8) | Formato de píxel de 32 bits, 8 bits para rojo, verde, azul y alfa. |
| [SHORT_GR](#SHORT-GR) | Formato de píxel de 32 bits, 16 bits verde, 16 bits rojo |
| [SHORT_RGB](#SHORT-RGB) | Formato de píxel de 48 bits, 16 bits para rojo, verde y azul |
| [SHORT_RGBA](#SHORT-RGBA) | Formato de píxel de 64 bits, 16 bits para rojo, verde, azul y alfa |
| [UNKNOWN](#UNKNOWN) | Formato de píxel desconocido. |
| [X8B8G8R8](#X8B8G8R8) | Formato de píxel de 32 bits, 8 bits para azul, 8 bits para verde, 8 bits para rojo como A8B8G8R8, pero el alfa se descartará |
| [X8R8G8B8](#X8R8G8B8) | Formato de píxel de 32 bits, 8 bits para rojo, 8 bits para verde, 8 bits para azul como A8R8G8B8, pero el alfa se descartará |
## Métodos

| Método | Descripción |
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


Formato de píxel de 16 bits, 5 bits para azul, verde, rojo y 1 para alfa.

### A2B10G10R10 {#A2B10G10R10}
```
public static final PixelFormat A2B10G10R10
```


Formato de píxel de 32 bits, 10 bits para azul, verde y rojo, 2 bits para alfa.

### A2R10G10B10 {#A2R10G10B10}
```
public static final PixelFormat A2R10G10B10
```


Formato de píxel de 32 bits, 2 bits para alfa, 10 bits para rojo, verde y azul.

### A4L4 {#A4L4}
```
public static final PixelFormat A4L4
```


Formato de píxel de 8 bits, 4 bits alfa, 4 bits luminancia.

### A4R4G4B4 {#A4R4G4B4}
```
public static final PixelFormat A4R4G4B4
```


Formato de píxel de 16 bits, 4 bits para alfa, rojo, verde y azul.

### A8 {#A8}
```
public static final PixelFormat A8
```


Formato de píxel de 8 bits, todos los bits alfa.

### A8B8G8R8 {#A8B8G8R8}
```
public static final PixelFormat A8B8G8R8
```


Formato de píxel de 32 bits, 8 bits para azul, verde, rojo y alfa.

### A8R8G8B8 {#A8R8G8B8}
```
public static final PixelFormat A8R8G8B8
```


Formato de píxel de 32 bits, 8 bits para alfa, rojo, verde y azul.

### B5G6R5 {#B5G6R5}
```
public static final PixelFormat B5G6R5
```


Formato de píxel de 16 bits, 5 bits rojo, 6 bits verde, 5 bits azul.

### B8 {#B8}
```
public static final PixelFormat B8
```


Formato de píxel de 8 bits, todos los bits azul.

### B8G8R8 {#B8G8R8}
```
public static final PixelFormat B8G8R8
```


Formato de píxel de 24 bits, 8 bits para azul, verde y rojo.

### B8G8R8A8 {#B8G8R8A8}
```
public static final PixelFormat B8G8R8A8
```


Formato de píxel de 32 bits, 8 bits para azul, verde, rojo y alfa.

### BYTE_LA {#BYTE-LA}
```
public static final PixelFormat BYTE_LA
```


Formato de píxel de 2 bytes, 1 byte de luminancia, 1 byte alfa

### DEPTH {#DEPTH}
```
public static final PixelFormat DEPTH
```


Formato de textura de profundidad.

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


Formato de píxel de punto flotante s10e5 de 32 bits, 2 canales, 16 bits verde, 16 bits rojo

### FLOAT16_R {#FLOAT16-R}
```
public static final PixelFormat FLOAT16_R
```


Formato de píxel de 16 bits, 16 bits (float) para rojo

### FLOAT16_RGB {#FLOAT16-RGB}
```
public static final PixelFormat FLOAT16_RGB
```


Formato de píxel de 48 bits, 16 bits (float) para rojo, 16 bits (float) para verde, 16 bits (float) para azul

### FLOAT16_RGBA {#FLOAT16-RGBA}
```
public static final PixelFormat FLOAT16_RGBA
```


Formato de píxel de 64 bits, 16 bits (float) para rojo, 16 bits (float) para verde, 16 bits (float) para azul, 16 bits (float) para alfa

### FLOAT32_GR {#FLOAT32-GR}
```
public static final PixelFormat FLOAT32_GR
```


Formato de píxel de punto flotante de 64 bits, 2 canales, 32 bits verde, 32 bits rojo

### FLOAT32_R {#FLOAT32-R}
```
public static final PixelFormat FLOAT32_R
```


Formato de píxel de 32 bits, 32 bits (float) para rojo

### FLOAT32_RGB {#FLOAT32-RGB}
```
public static final PixelFormat FLOAT32_RGB
```


Formato de píxel de 96 bits, 32 bits (float) para rojo, 32 bits (float) para verde, 32 bits (float) para azul

### FLOAT32_RGBA {#FLOAT32-RGBA}
```
public static final PixelFormat FLOAT32_RGBA
```


Formato de píxel de 128 bits, 32 bits (float) para rojo, 32 bits (float) para verde, 32 bits (float) para azul, 32 bits (float) para alfa

### G8 {#G8}
```
public static final PixelFormat G8
```


Formato de píxel de 8 bits, todos los bits verde.

### L16 {#L16}
```
public static final PixelFormat L16
```


Formato de píxel de 16 bits, todos los bits luminancia.

### L8 {#L8}
```
public static final PixelFormat L8
```


Formato de píxel de 8 bits, todos los bits luminancia.

### R32G32B32A32_UINT {#R32G32B32A32-UINT}
```
public static final PixelFormat R32G32B32A32_UINT
```


Formato de píxel de 128 bits, 32 bits rojo (entero sin signo), 32 bits azul (entero sin signo), 32 bits verde (entero sin signo), 32 bits alfa (entero sin signo).

### R32G32_UINT {#R32G32-UINT}
```
public static final PixelFormat R32G32_UINT
```


Formato de píxel de 64 bits, 32 bits rojo (entero sin signo), 32 bits azul (entero sin signo).

### R32_UINT {#R32-UINT}
```
public static final PixelFormat R32_UINT
```


Formato de píxel de 32 bits, 32 bits rojo (entero sin signo).

### R3G3B2 {#R3G3B2}
```
public static final PixelFormat R3G3B2
```


Formato de píxel de 8 bits, 2 bits azul, 3 bits verde, 3 bits rojo.

### R5G6B5 {#R5G6B5}
```
public static final PixelFormat R5G6B5
```


Formato de píxel de 16 bits, 5 bits rojo, 6 bits verde, 5 bits azul.

### R8 {#R8}
```
public static final PixelFormat R8
```


Formato de píxel de 8 bits, todos los bits rojo.

### R8G8B8 {#R8G8B8}
```
public static final PixelFormat R8G8B8
```


Formato de píxel de 24 bits, 8 bits para rojo, verde y azul.

### R8G8B8A8 {#R8G8B8A8}
```
public static final PixelFormat R8G8B8A8
```


Formato de píxel de 32 bits, 8 bits para rojo, verde, azul y alfa.

### SHORT_GR {#SHORT-GR}
```
public static final PixelFormat SHORT_GR
```


Formato de píxel de 32 bits, 16 bits verde, 16 bits rojo

### SHORT_RGB {#SHORT-RGB}
```
public static final PixelFormat SHORT_RGB
```


Formato de píxel de 48 bits, 16 bits para rojo, verde y azul

### SHORT_RGBA {#SHORT-RGBA}
```
public static final PixelFormat SHORT_RGBA
```


Formato de píxel de 64 bits, 16 bits para rojo, verde, azul y alfa

### UNKNOWN {#UNKNOWN}
```
public static final PixelFormat UNKNOWN
```


Formato de píxel desconocido.

### X8B8G8R8 {#X8B8G8R8}
```
public static final PixelFormat X8B8G8R8
```


Formato de píxel de 32 bits, 8 bits para azul, 8 bits para verde, 8 bits para rojo como A8B8G8R8, pero el alfa se descartará

### X8R8G8B8 {#X8R8G8B8}
```
public static final PixelFormat X8R8G8B8
```


Formato de píxel de 32 bits, 8 bits para rojo, 8 bits para verde, 8 bits para azul como A8R8G8B8, pero el alfa se descartará

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

