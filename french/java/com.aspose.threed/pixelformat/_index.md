---
title: "PixelFormat"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le format de pixels utilisé dans l'unité de texture."
type: docs
weight: 290
url: /fr/java/com.aspose.threed/pixelformat/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PixelFormat extends Enum<PixelFormat>
```

Le format du pixel utilisé dans l'unité de texture.
## Champs

| Champ | Description |
| --- | --- |
| [A1R5G5B5](#A1R5G5B5) | Format de pixel 16 bits, 5 bits pour le bleu, le vert, le rouge et 1 pour l'alpha. |
| [A2B10G10R10](#A2B10G10R10) | Format de pixel 32 bits, 10 bits pour le bleu, le vert et le rouge, 2 bits pour l'alpha. |
| [A2R10G10B10](#A2R10G10B10) | Format de pixel 32 bits, 2 bits pour l'alpha, 10 bits pour le rouge, le vert et le bleu. |
| [A4L4](#A4L4) | Format de pixel 8 bits, 4 bits alpha, 4 bits luminance. |
| [A4R4G4B4](#A4R4G4B4) | Format de pixel 16 bits, 4 bits pour l'alpha, le rouge, le vert et le bleu. |
| [A8](#A8) | Format de pixel 8 bits, tous les bits alpha. |
| [A8B8G8R8](#A8B8G8R8) | Format de pixel 32 bits, 8 bits pour le bleu, le vert, le rouge et l'alpha. |
| [A8R8G8B8](#A8R8G8B8) | Format de pixel 32 bits, 8 bits pour l'alpha, le rouge, le vert et le bleu. |
| [B5G6R5](#B5G6R5) | Format de pixel 16 bits, 5 bits rouge, 6 bits vert, 5 bits bleu. |
| [B8](#B8) | Format de pixel 8 bits, tous les bits bleu. |
| [B8G8R8](#B8G8R8) | Format de pixel 24 bits, 8 bits pour le bleu, le vert et le rouge. |
| [B8G8R8A8](#B8G8R8A8) | Format de pixel 32 bits, 8 bits pour le bleu, le vert, le rouge et l'alpha. |
| [BYTE_LA](#BYTE-LA) | Format de pixel 2 octets, 1 octet luminance, 1 octet alpha |
| [DEPTH](#DEPTH) | Format de texture de profondeur. |
| [DXT1](#DXT1) | Format DDS (DirectDraw Surface) DXT1. |
| [DXT2](#DXT2) | Format DDS (DirectDraw Surface) DXT2. |
| [DXT3](#DXT3) | Format DDS (DirectDraw Surface) DXT3. |
| [DXT4](#DXT4) | Format DDS (DirectDraw Surface) DXT4. |
| [DXT5](#DXT5) | Format DDS (DirectDraw Surface) DXT5. |
| [FLOAT16_GR](#FLOAT16-GR) | Format de pixel flottant 32 bits, 2 canaux s10e5, vert 16 bits, rouge 16 bits |
| [FLOAT16_R](#FLOAT16-R) | Format de pixel 16 bits, 16 bits (float) pour le rouge |
| [FLOAT16_RGB](#FLOAT16-RGB) | Format de pixel 48 bits, 16 bits (float) pour le rouge, 16 bits (float) pour le vert, 16 bits (float) pour le bleu |
| [FLOAT16_RGBA](#FLOAT16-RGBA) | Format de pixel 64 bits, 16 bits (float) pour le rouge, 16 bits (float) pour le vert, 16 bits (float) pour le bleu, 16 bits (float) pour l'alpha |
| [FLOAT32_GR](#FLOAT32-GR) | Format de pixel flottant 64 bits, 2 canaux, vert 32 bits, rouge 32 bits |
| [FLOAT32_R](#FLOAT32-R) | Format de pixel 32 bits, 32 bits (float) pour le rouge |
| [FLOAT32_RGB](#FLOAT32-RGB) | Format de pixel 96 bits, 32 bits (float) pour le rouge, 32 bits (float) pour le vert, 32 bits (float) pour le bleu |
| [FLOAT32_RGBA](#FLOAT32-RGBA) | Format de pixel 128 bits, 32 bits (float) pour le rouge, 32 bits (float) pour le vert, 32 bits (float) pour le bleu, 32 bits (float) pour l'alpha |
| [G8](#G8) | Format de pixel 8 bits, tous les bits verts. |
| [L16](#L16) | Format de pixel 16 bits, tous les bits de luminance. |
| [L8](#L8) | Format de pixel 8 bits, tous les bits de luminance. |
| [R32G32B32A32_UINT](#R32G32B32A32-UINT) | Format de pixel 128 bits, 32 bits rouge (entier non signé), 32 bits bleu (entier non signé), 32 bits vert (entier non signé), 32 bits alpha (entier non signé). |
| [R32G32_UINT](#R32G32-UINT) | Format de pixel 64 bits, 32 bits rouge (entier non signé), 32 bits bleu (entier non signé). |
| [R32_UINT](#R32-UINT) | Format de pixel 32 bits, 32 bits rouge (entier non signé). |
| [R3G3B2](#R3G3B2) | Format de pixel 8 bits, 2 bits bleu, 3 bits vert, 3 bits rouge. |
| [R5G6B5](#R5G6B5) | Format de pixel 16 bits, 5 bits rouge, 6 bits vert, 5 bits bleu. |
| [R8](#R8) | Format de pixel 8 bits, tous les bits rouges. |
| [R8G8B8](#R8G8B8) | Format de pixel 24 bits, 8 bits pour le rouge, le vert et le bleu. |
| [R8G8B8A8](#R8G8B8A8) | Format de pixel 32 bits, 8 bits pour le rouge, le vert, le bleu et l'alpha. |
| [SHORT_GR](#SHORT-GR) | Format de pixel 32 bits, vert 16 bits, rouge 16 bits |
| [SHORT_RGB](#SHORT-RGB) | Format de pixel 48 bits, 16 bits pour le rouge, le vert et le bleu |
| [SHORT_RGBA](#SHORT-RGBA) | Format de pixel 64 bits, 16 bits pour le rouge, le vert, le bleu et l'alpha |
| [UNKNOWN](#UNKNOWN) | Format de pixel inconnu. |
| [X8B8G8R8](#X8B8G8R8) | Format de pixel 32 bits, 8 bits pour le bleu, 8 bits pour le vert, 8 bits pour le rouge comme A8B8G8R8, mais l'alpha sera ignoré |
| [X8R8G8B8](#X8R8G8B8) | Format de pixel 32 bits, 8 bits pour le rouge, 8 bits pour le vert, 8 bits pour le bleu comme A8R8G8B8, mais l'alpha sera ignoré |
## Méthodes

| Méthode | Description |
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


Format de pixel 16 bits, 5 bits pour le bleu, le vert, le rouge et 1 pour l'alpha.

### A2B10G10R10 {#A2B10G10R10}
```
public static final PixelFormat A2B10G10R10
```


Format de pixel 32 bits, 10 bits pour le bleu, le vert et le rouge, 2 bits pour l'alpha.

### A2R10G10B10 {#A2R10G10B10}
```
public static final PixelFormat A2R10G10B10
```


Format de pixel 32 bits, 2 bits pour l'alpha, 10 bits pour le rouge, le vert et le bleu.

### A4L4 {#A4L4}
```
public static final PixelFormat A4L4
```


Format de pixel 8 bits, 4 bits alpha, 4 bits luminance.

### A4R4G4B4 {#A4R4G4B4}
```
public static final PixelFormat A4R4G4B4
```


Format de pixel 16 bits, 4 bits pour l'alpha, le rouge, le vert et le bleu.

### A8 {#A8}
```
public static final PixelFormat A8
```


Format de pixel 8 bits, tous les bits alpha.

### A8B8G8R8 {#A8B8G8R8}
```
public static final PixelFormat A8B8G8R8
```


Format de pixel 32 bits, 8 bits pour le bleu, le vert, le rouge et l'alpha.

### A8R8G8B8 {#A8R8G8B8}
```
public static final PixelFormat A8R8G8B8
```


Format de pixel 32 bits, 8 bits pour l'alpha, le rouge, le vert et le bleu.

### B5G6R5 {#B5G6R5}
```
public static final PixelFormat B5G6R5
```


Format de pixel 16 bits, 5 bits rouge, 6 bits vert, 5 bits bleu.

### B8 {#B8}
```
public static final PixelFormat B8
```


Format de pixel 8 bits, tous les bits bleu.

### B8G8R8 {#B8G8R8}
```
public static final PixelFormat B8G8R8
```


Format de pixel 24 bits, 8 bits pour le bleu, le vert et le rouge.

### B8G8R8A8 {#B8G8R8A8}
```
public static final PixelFormat B8G8R8A8
```


Format de pixel 32 bits, 8 bits pour le bleu, le vert, le rouge et l'alpha.

### BYTE_LA {#BYTE-LA}
```
public static final PixelFormat BYTE_LA
```


Format de pixel 2 octets, 1 octet luminance, 1 octet alpha

### DEPTH {#DEPTH}
```
public static final PixelFormat DEPTH
```


Format de texture de profondeur.

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


Format de pixel flottant 32 bits, 2 canaux s10e5, vert 16 bits, rouge 16 bits

### FLOAT16_R {#FLOAT16-R}
```
public static final PixelFormat FLOAT16_R
```


Format de pixel 16 bits, 16 bits (float) pour le rouge

### FLOAT16_RGB {#FLOAT16-RGB}
```
public static final PixelFormat FLOAT16_RGB
```


Format de pixel 48 bits, 16 bits (float) pour le rouge, 16 bits (float) pour le vert, 16 bits (float) pour le bleu

### FLOAT16_RGBA {#FLOAT16-RGBA}
```
public static final PixelFormat FLOAT16_RGBA
```


Format de pixel 64 bits, 16 bits (float) pour le rouge, 16 bits (float) pour le vert, 16 bits (float) pour le bleu, 16 bits (float) pour l'alpha

### FLOAT32_GR {#FLOAT32-GR}
```
public static final PixelFormat FLOAT32_GR
```


Format de pixel flottant 64 bits, 2 canaux, vert 32 bits, rouge 32 bits

### FLOAT32_R {#FLOAT32-R}
```
public static final PixelFormat FLOAT32_R
```


Format de pixel 32 bits, 32 bits (float) pour le rouge

### FLOAT32_RGB {#FLOAT32-RGB}
```
public static final PixelFormat FLOAT32_RGB
```


Format de pixel 96 bits, 32 bits (float) pour le rouge, 32 bits (float) pour le vert, 32 bits (float) pour le bleu

### FLOAT32_RGBA {#FLOAT32-RGBA}
```
public static final PixelFormat FLOAT32_RGBA
```


Format de pixel 128 bits, 32 bits (float) pour le rouge, 32 bits (float) pour le vert, 32 bits (float) pour le bleu, 32 bits (float) pour l'alpha

### G8 {#G8}
```
public static final PixelFormat G8
```


Format de pixel 8 bits, tous les bits verts.

### L16 {#L16}
```
public static final PixelFormat L16
```


Format de pixel 16 bits, tous les bits de luminance.

### L8 {#L8}
```
public static final PixelFormat L8
```


Format de pixel 8 bits, tous les bits de luminance.

### R32G32B32A32_UINT {#R32G32B32A32-UINT}
```
public static final PixelFormat R32G32B32A32_UINT
```


Format de pixel 128 bits, 32 bits rouge (entier non signé), 32 bits bleu (entier non signé), 32 bits vert (entier non signé), 32 bits alpha (entier non signé).

### R32G32_UINT {#R32G32-UINT}
```
public static final PixelFormat R32G32_UINT
```


Format de pixel 64 bits, 32 bits rouge (entier non signé), 32 bits bleu (entier non signé).

### R32_UINT {#R32-UINT}
```
public static final PixelFormat R32_UINT
```


Format de pixel 32 bits, 32 bits rouge (entier non signé).

### R3G3B2 {#R3G3B2}
```
public static final PixelFormat R3G3B2
```


Format de pixel 8 bits, 2 bits bleu, 3 bits vert, 3 bits rouge.

### R5G6B5 {#R5G6B5}
```
public static final PixelFormat R5G6B5
```


Format de pixel 16 bits, 5 bits rouge, 6 bits vert, 5 bits bleu.

### R8 {#R8}
```
public static final PixelFormat R8
```


Format de pixel 8 bits, tous les bits rouges.

### R8G8B8 {#R8G8B8}
```
public static final PixelFormat R8G8B8
```


Format de pixel 24 bits, 8 bits pour le rouge, le vert et le bleu.

### R8G8B8A8 {#R8G8B8A8}
```
public static final PixelFormat R8G8B8A8
```


Format de pixel 32 bits, 8 bits pour le rouge, le vert, le bleu et l'alpha.

### SHORT_GR {#SHORT-GR}
```
public static final PixelFormat SHORT_GR
```


Format de pixel 32 bits, vert 16 bits, rouge 16 bits

### SHORT_RGB {#SHORT-RGB}
```
public static final PixelFormat SHORT_RGB
```


Format de pixel 48 bits, 16 bits pour le rouge, le vert et le bleu

### SHORT_RGBA {#SHORT-RGBA}
```
public static final PixelFormat SHORT_RGBA
```


Format de pixel 64 bits, 16 bits pour le rouge, le vert, le bleu et l'alpha

### UNKNOWN {#UNKNOWN}
```
public static final PixelFormat UNKNOWN
```


Format de pixel inconnu.

### X8B8G8R8 {#X8B8G8R8}
```
public static final PixelFormat X8B8G8R8
```


Format de pixel 32 bits, 8 bits pour le bleu, 8 bits pour le vert, 8 bits pour le rouge comme A8B8G8R8, mais l'alpha sera ignoré

### X8R8G8B8 {#X8R8G8B8}
```
public static final PixelFormat X8R8G8B8
```


Format de pixel 32 bits, 8 bits pour le rouge, 8 bits pour le vert, 8 bits pour le bleu comme A8R8G8B8, mais l'alpha sera ignoré

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

