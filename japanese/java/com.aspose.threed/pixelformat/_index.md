---
title: "ピクセルフォーマット"
second_title: "Aspose.3D for Java API リファレンス"
description: "テクスチャユニットで使用されるピクセルフォーマットです。"
type: docs
weight: 290
url: /ja/java/com.aspose.threed/pixelformat/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PixelFormat extends Enum<PixelFormat>
```

テクスチャユニットで使用されるピクセル形式。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [A1R5G5B5](#A1R5G5B5) | 16ビットピクセルフォーマット、青、緑、赤に5ビット、アルファに1ビット。 |
| [A2B10G10R10](#A2B10G10R10) | 32ビットピクセルフォーマット、青、緑、赤に10ビット、アルファに2ビット。 |
| [A2R10G10B10](#A2R10G10B10) | 32ビットピクセルフォーマット、アルファに2ビット、赤、緑、青に10ビット。 |
| [A4L4](#A4L4) | 8ビットピクセルフォーマット、アルファに4ビット、輝度に4ビット。 |
| [A4R4G4B4](#A4R4G4B4) | 16ビットピクセルフォーマット、アルファ、赤、緑、青にそれぞれ4ビット。 |
| [A8](#A8) | 8ビットピクセルフォーマット、全ビットがアルファ。 |
| [A8B8G8R8](#A8B8G8R8) | 32ビットピクセルフォーマット、青、緑、赤、アルファにそれぞれ8ビット。 |
| [A8R8G8B8](#A8R8G8B8) | 32ビットピクセルフォーマット、アルファ、赤、緑、青にそれぞれ8ビット。 |
| [B5G6R5](#B5G6R5) | 16ビットピクセルフォーマット、赤に5ビット、緑に6ビット、青に5ビット。 |
| [B8](#B8) | 8ビットピクセルフォーマット、全ビットが青。 |
| [B8G8R8](#B8G8R8) | 24ビットピクセルフォーマット、青、緑、赤にそれぞれ8ビット。 |
| [B8G8R8A8](#B8G8R8A8) | 32ビットピクセルフォーマット、青、緑、赤、アルファにそれぞれ8ビット。 |
| [BYTE_LA](#BYTE-LA) | 2バイトピクセルフォーマット、1バイトが輝度、1バイトがアルファ |
| [DEPTH](#DEPTH) | 深度テクスチャフォーマットです。 |
| [DXT1](#DXT1) | DDS（DirectDraw Surface）DXT1 フォーマット。 |
| [DXT2](#DXT2) | DDS（DirectDraw Surface）DXT2 フォーマット。 |
| [DXT3](#DXT3) | DDS（DirectDraw Surface）DXT3 フォーマット。 |
| [DXT4](#DXT4) | DDS（DirectDraw Surface）DXT4 フォーマット。 |
| [DXT5](#DXT5) | DDS（DirectDraw Surface）DXT5 フォーマット。 |
| [FLOAT16_GR](#FLOAT16-GR) | 32ビット、2チャンネル s10e5 浮動小数点ピクセル形式、16ビット緑、16ビット赤 |
| [FLOAT16_R](#FLOAT16-R) | 16ビットピクセル形式、赤に16ビット（float） |
| [FLOAT16_RGB](#FLOAT16-RGB) | 48ビットピクセル形式、赤に16ビット（float）、緑に16ビット（float）、青に16ビット（float） |
| [FLOAT16_RGBA](#FLOAT16-RGBA) | 64ビットピクセル形式、赤に16ビット（float）、緑に16ビット（float）、青に16ビット（float）、アルファに16ビット（float） |
| [FLOAT32_GR](#FLOAT32-GR) | 64ビット、2チャンネル浮動小数点ピクセル形式、32ビット緑、32ビット赤 |
| [FLOAT32_R](#FLOAT32-R) | 32ビットピクセル形式、赤に32ビット（float） |
| [FLOAT32_RGB](#FLOAT32-RGB) | 96ビットピクセル形式、赤に32ビット（float）、緑に32ビット（float）、青に32ビット（float） |
| [FLOAT32_RGBA](#FLOAT32-RGBA) | 128ビットピクセル形式、赤に32ビット（float）、緑に32ビット（float）、青に32ビット（float）、アルファに32ビット（float） |
| [G8](#G8) | 8ビットピクセル形式、すべてのビットが緑。 |
| [L16](#L16) | 16ビットピクセル形式、すべてのビットが輝度。 |
| [L8](#L8) | 8ビットピクセル形式、すべてのビットが輝度。 |
| [R32G32B32A32_UINT](#R32G32B32A32-UINT) | 128ビットピクセル形式、32ビット赤（unsigned int）、32ビット青（unsigned int）、32ビット緑（unsigned int）、32ビットアルファ（unsigned int）。 |
| [R32G32_UINT](#R32G32-UINT) | 64ビットピクセル形式、32ビット赤（unsigned int）、32ビット青（unsigned int）。 |
| [R32_UINT](#R32-UINT) | 32ビットピクセル形式、32ビット赤（unsigned int）。 |
| [R3G3B2](#R3G3B2) | 8ビットピクセル形式、2ビット青、3ビット緑、3ビット赤。 |
| [R5G6B5](#R5G6B5) | 16ビットピクセルフォーマット、赤に5ビット、緑に6ビット、青に5ビット。 |
| [R8](#R8) | 8ビットピクセル形式、すべてのビットが赤。 |
| [R8G8B8](#R8G8B8) | 24ビットピクセル形式、赤・緑・青にそれぞれ8ビット。 |
| [R8G8B8A8](#R8G8B8A8) | 32ビットピクセル形式、赤・緑・青・アルファにそれぞれ8ビット。 |
| [SHORT_GR](#SHORT-GR) | 32ビットピクセル形式、16ビット緑、16ビット赤 |
| [SHORT_RGB](#SHORT-RGB) | 48ビットピクセル形式、赤・緑・青にそれぞれ16ビット |
| [SHORT_RGBA](#SHORT-RGBA) | 64ビットピクセル形式、赤・緑・青・アルファにそれぞれ16ビット |
| [UNKNOWN](#UNKNOWN) | 不明なピクセル形式。 |
| [X8B8G8R8](#X8B8G8R8) | 32ビットピクセル形式、青に8ビット、緑に8ビット、赤に8ビット（A8B8G8R8 のように）、ただしアルファは破棄されます |
| [X8R8G8B8](#X8R8G8B8) | 32ビットピクセル形式、赤に8ビット、緑に8ビット、青に8ビット（A8R8G8B8 のように）、ただしアルファは破棄されます |
## メソッド

| メソッド | 説明 |
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


16ビットピクセルフォーマット、青、緑、赤に5ビット、アルファに1ビット。

### A2B10G10R10 {#A2B10G10R10}
```
public static final PixelFormat A2B10G10R10
```


32ビットピクセルフォーマット、青、緑、赤に10ビット、アルファに2ビット。

### A2R10G10B10 {#A2R10G10B10}
```
public static final PixelFormat A2R10G10B10
```


32ビットピクセルフォーマット、アルファに2ビット、赤、緑、青に10ビット。

### A4L4 {#A4L4}
```
public static final PixelFormat A4L4
```


8ビットピクセルフォーマット、アルファに4ビット、輝度に4ビット。

### A4R4G4B4 {#A4R4G4B4}
```
public static final PixelFormat A4R4G4B4
```


16ビットピクセルフォーマット、アルファ、赤、緑、青にそれぞれ4ビット。

### A8 {#A8}
```
public static final PixelFormat A8
```


8ビットピクセルフォーマット、全ビットがアルファ。

### A8B8G8R8 {#A8B8G8R8}
```
public static final PixelFormat A8B8G8R8
```


32ビットピクセルフォーマット、青、緑、赤、アルファにそれぞれ8ビット。

### A8R8G8B8 {#A8R8G8B8}
```
public static final PixelFormat A8R8G8B8
```


32ビットピクセルフォーマット、アルファ、赤、緑、青にそれぞれ8ビット。

### B5G6R5 {#B5G6R5}
```
public static final PixelFormat B5G6R5
```


16ビットピクセルフォーマット、赤に5ビット、緑に6ビット、青に5ビット。

### B8 {#B8}
```
public static final PixelFormat B8
```


8ビットピクセルフォーマット、全ビットが青。

### B8G8R8 {#B8G8R8}
```
public static final PixelFormat B8G8R8
```


24ビットピクセルフォーマット、青、緑、赤にそれぞれ8ビット。

### B8G8R8A8 {#B8G8R8A8}
```
public static final PixelFormat B8G8R8A8
```


32ビットピクセルフォーマット、青、緑、赤、アルファにそれぞれ8ビット。

### BYTE_LA {#BYTE-LA}
```
public static final PixelFormat BYTE_LA
```


2バイトピクセルフォーマット、1バイトが輝度、1バイトがアルファ

### DEPTH {#DEPTH}
```
public static final PixelFormat DEPTH
```


深度テクスチャフォーマットです。

### DXT1 {#DXT1}
```
public static final PixelFormat DXT1
```


DDS（DirectDraw Surface）DXT1 フォーマット。

### DXT2 {#DXT2}
```
public static final PixelFormat DXT2
```


DDS（DirectDraw Surface）DXT2 フォーマット。

### DXT3 {#DXT3}
```
public static final PixelFormat DXT3
```


DDS（DirectDraw Surface）DXT3 フォーマット。

### DXT4 {#DXT4}
```
public static final PixelFormat DXT4
```


DDS（DirectDraw Surface）DXT4 フォーマット。

### DXT5 {#DXT5}
```
public static final PixelFormat DXT5
```


DDS（DirectDraw Surface）DXT5 フォーマット。

### FLOAT16_GR {#FLOAT16-GR}
```
public static final PixelFormat FLOAT16_GR
```


32ビット、2チャンネル s10e5 浮動小数点ピクセル形式、16ビット緑、16ビット赤

### FLOAT16_R {#FLOAT16-R}
```
public static final PixelFormat FLOAT16_R
```


16ビットピクセル形式、赤に16ビット（float）

### FLOAT16_RGB {#FLOAT16-RGB}
```
public static final PixelFormat FLOAT16_RGB
```


48ビットピクセル形式、赤に16ビット（float）、緑に16ビット（float）、青に16ビット（float）

### FLOAT16_RGBA {#FLOAT16-RGBA}
```
public static final PixelFormat FLOAT16_RGBA
```


64ビットピクセル形式、赤に16ビット（float）、緑に16ビット（float）、青に16ビット（float）、アルファに16ビット（float）

### FLOAT32_GR {#FLOAT32-GR}
```
public static final PixelFormat FLOAT32_GR
```


64ビット、2チャンネル浮動小数点ピクセル形式、32ビット緑、32ビット赤

### FLOAT32_R {#FLOAT32-R}
```
public static final PixelFormat FLOAT32_R
```


32ビットピクセル形式、赤に32ビット（float）

### FLOAT32_RGB {#FLOAT32-RGB}
```
public static final PixelFormat FLOAT32_RGB
```


96ビットピクセル形式、赤に32ビット（float）、緑に32ビット（float）、青に32ビット（float）

### FLOAT32_RGBA {#FLOAT32-RGBA}
```
public static final PixelFormat FLOAT32_RGBA
```


128ビットピクセル形式、赤に32ビット（float）、緑に32ビット（float）、青に32ビット（float）、アルファに32ビット（float）

### G8 {#G8}
```
public static final PixelFormat G8
```


8ビットピクセル形式、すべてのビットが緑。

### L16 {#L16}
```
public static final PixelFormat L16
```


16ビットピクセル形式、すべてのビットが輝度。

### L8 {#L8}
```
public static final PixelFormat L8
```


8ビットピクセル形式、すべてのビットが輝度。

### R32G32B32A32_UINT {#R32G32B32A32-UINT}
```
public static final PixelFormat R32G32B32A32_UINT
```


128ビットピクセル形式、32ビット赤（unsigned int）、32ビット青（unsigned int）、32ビット緑（unsigned int）、32ビットアルファ（unsigned int）。

### R32G32_UINT {#R32G32-UINT}
```
public static final PixelFormat R32G32_UINT
```


64ビットピクセル形式、32ビット赤（unsigned int）、32ビット青（unsigned int）。

### R32_UINT {#R32-UINT}
```
public static final PixelFormat R32_UINT
```


32ビットピクセル形式、32ビット赤（unsigned int）。

### R3G3B2 {#R3G3B2}
```
public static final PixelFormat R3G3B2
```


8ビットピクセル形式、2ビット青、3ビット緑、3ビット赤。

### R5G6B5 {#R5G6B5}
```
public static final PixelFormat R5G6B5
```


16ビットピクセルフォーマット、赤に5ビット、緑に6ビット、青に5ビット。

### R8 {#R8}
```
public static final PixelFormat R8
```


8ビットピクセル形式、すべてのビットが赤。

### R8G8B8 {#R8G8B8}
```
public static final PixelFormat R8G8B8
```


24ビットピクセル形式、赤・緑・青にそれぞれ8ビット。

### R8G8B8A8 {#R8G8B8A8}
```
public static final PixelFormat R8G8B8A8
```


32ビットピクセル形式、赤・緑・青・アルファにそれぞれ8ビット。

### SHORT_GR {#SHORT-GR}
```
public static final PixelFormat SHORT_GR
```


32ビットピクセル形式、16ビット緑、16ビット赤

### SHORT_RGB {#SHORT-RGB}
```
public static final PixelFormat SHORT_RGB
```


48ビットピクセル形式、赤・緑・青にそれぞれ16ビット

### SHORT_RGBA {#SHORT-RGBA}
```
public static final PixelFormat SHORT_RGBA
```


64ビットピクセル形式、赤・緑・青・アルファにそれぞれ16ビット

### UNKNOWN {#UNKNOWN}
```
public static final PixelFormat UNKNOWN
```


不明なピクセル形式。

### X8B8G8R8 {#X8B8G8R8}
```
public static final PixelFormat X8B8G8R8
```


32ビットピクセル形式、青に8ビット、緑に8ビット、赤に8ビット（A8B8G8R8 のように）、ただしアルファは破棄されます

### X8R8G8B8 {#X8R8G8B8}
```
public static final PixelFormat X8R8G8B8
```


32ビットピクセル形式、赤に8ビット、緑に8ビット、青に8ビット（A8R8G8B8 のように）、ただしアルファは破棄されます

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

