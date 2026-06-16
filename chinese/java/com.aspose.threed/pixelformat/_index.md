---
title: "像素格式"
second_title: "Aspose.3D for Java API 参考"
description: "纹理单元中使用的像素格式。"
type: docs
weight: 290
url: /zh/java/com.aspose.threed/pixelformat/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PixelFormat extends Enum<PixelFormat>
```

纹理单元中使用的像素格式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [A1R5G5B5](#A1R5G5B5) | 16 位像素格式，蓝、绿、红各 5 位，Alpha 为 1 位。 |
| [A2B10G10R10](#A2B10G10R10) | 32 位像素格式，蓝、绿、红各 10 位，Alpha 为 2 位。 |
| [A2R10G10B10](#A2R10G10B10) | 32 位像素格式，Alpha 为 2 位，红、绿、蓝各 10 位。 |
| [A4L4](#A4L4) | 8 位像素格式，Alpha 为 4 位，亮度为 4 位。 |
| [A4R4G4B4](#A4R4G4B4) | 16 位像素格式，Alpha、红、绿、蓝各 4 位。 |
| [A8](#A8) | 8 位像素格式，全部位为 Alpha。 |
| [A8B8G8R8](#A8B8G8R8) | 32 位像素格式，蓝、绿、红、Alpha 各 8 位。 |
| [A8R8G8B8](#A8R8G8B8) | 32 位像素格式，Alpha、红、绿、蓝各 8 位。 |
| [B5G6R5](#B5G6R5) | 16 位像素格式，红 5 位，绿 6 位，蓝 5 位。 |
| [B8](#B8) | 8 位像素格式，全部位为蓝色。 |
| [B8G8R8](#B8G8R8) | 24 位像素格式，蓝、绿、红各 8 位。 |
| [B8G8R8A8](#B8G8R8A8) | 32 位像素格式，蓝、绿、红、Alpha 各 8 位。 |
| [BYTE_LA](#BYTE-LA) | 2 字节像素格式，1 字节亮度，1 字节 Alpha |
| [DEPTH](#DEPTH) | 深度纹理格式。 |
| [DXT1](#DXT1) | DDS（DirectDraw Surface）DXT1 格式。 |
| [DXT2](#DXT2) | DDS（DirectDraw Surface）DXT2 格式。 |
| [DXT3](#DXT3) | DDS（DirectDraw Surface）DXT3 格式。 |
| [DXT4](#DXT4) | DDS（DirectDraw Surface）DXT4 格式。 |
| [DXT5](#DXT5) | DDS（DirectDraw Surface）DXT5 格式。 |
| [FLOAT16_GR](#FLOAT16-GR) | 32 位，2 通道 s10e5 浮点像素格式，16 位绿色，16 位红色 |
| [FLOAT16_R](#FLOAT16-R) | 16 位像素格式，16 位（float）用于红色 |
| [FLOAT16_RGB](#FLOAT16-RGB) | 48 位像素格式，16 位（float）用于红色，16 位（float）用于绿色，16 位（float）用于蓝色 |
| [FLOAT16_RGBA](#FLOAT16-RGBA) | 64 位像素格式，16 位（float）用于红色，16 位（float）用于绿色，16 位（float）用于蓝色，16 位（float）用于透明度 |
| [FLOAT32_GR](#FLOAT32-GR) | 64 位，2 通道浮点像素格式，32 位绿色，32 位红色 |
| [FLOAT32_R](#FLOAT32-R) | 32 位像素格式，32 位（float）用于红色 |
| [FLOAT32_RGB](#FLOAT32-RGB) | 96 位像素格式，32 位（float）用于红色，32 位（float）用于绿色，32 位（float）用于蓝色 |
| [FLOAT32_RGBA](#FLOAT32-RGBA) | 128 位像素格式，32 位（float）用于红色，32 位（float）用于绿色，32 位（float）用于蓝色，32 位（float）用于透明度 |
| [G8](#G8) | 8 位像素格式，全部位为绿色。 |
| [L16](#L16) | 16 位像素格式，全部位为亮度。 |
| [L8](#L8) | 8 位像素格式，全部位为亮度。 |
| [R32G32B32A32_UINT](#R32G32B32A32-UINT) | 128 位像素格式，32 位红色（unsigned int），32 位蓝色（unsigned int），32 位绿色（unsigned int），32 位透明度（unsigned int）。 |
| [R32G32_UINT](#R32G32-UINT) | 64 位像素格式，32 位红色（unsigned int），32 位蓝色（unsigned int）。 |
| [R32_UINT](#R32-UINT) | 32 位像素格式，32 位红色（unsigned int）。 |
| [R3G3B2](#R3G3B2) | 8 位像素格式，2 位蓝色，3 位绿色，3 位红色。 |
| [R5G6B5](#R5G6B5) | 16 位像素格式，红 5 位，绿 6 位，蓝 5 位。 |
| [R8](#R8) | 8 位像素格式，全部位为红色。 |
| [R8G8B8](#R8G8B8) | 24 位像素格式，8 位用于红色、绿色和蓝色。 |
| [R8G8B8A8](#R8G8B8A8) | 32 位像素格式，8 位用于红色、绿色、蓝色和透明度。 |
| [SHORT_GR](#SHORT-GR) | 32 位像素格式，16 位绿色，16 位红色 |
| [SHORT_RGB](#SHORT-RGB) | 48 位像素格式，16 位用于红色、绿色和蓝色 |
| [SHORT_RGBA](#SHORT-RGBA) | 64 位像素格式，16 位用于红色、绿色、蓝色和透明度 |
| [UNKNOWN](#UNKNOWN) | 未知像素格式。 |
| [X8B8G8R8](#X8B8G8R8) | 32 位像素格式，8 位用于蓝色，8 位用于绿色，8 位用于红色，如 A8B8G8R8，但透明度将被丢弃 |
| [X8R8G8B8](#X8R8G8B8) | 32 位像素格式，8 位用于红色，8 位用于绿色，8 位用于蓝色，如 A8R8G8B8，但透明度将被丢弃 |
## 方法

| 方法 | 描述 |
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


16 位像素格式，蓝、绿、红各 5 位，Alpha 为 1 位。

### A2B10G10R10 {#A2B10G10R10}
```
public static final PixelFormat A2B10G10R10
```


32 位像素格式，蓝、绿、红各 10 位，Alpha 为 2 位。

### A2R10G10B10 {#A2R10G10B10}
```
public static final PixelFormat A2R10G10B10
```


32 位像素格式，Alpha 为 2 位，红、绿、蓝各 10 位。

### A4L4 {#A4L4}
```
public static final PixelFormat A4L4
```


8 位像素格式，Alpha 为 4 位，亮度为 4 位。

### A4R4G4B4 {#A4R4G4B4}
```
public static final PixelFormat A4R4G4B4
```


16 位像素格式，Alpha、红、绿、蓝各 4 位。

### A8 {#A8}
```
public static final PixelFormat A8
```


8 位像素格式，全部位为 Alpha。

### A8B8G8R8 {#A8B8G8R8}
```
public static final PixelFormat A8B8G8R8
```


32 位像素格式，蓝、绿、红、Alpha 各 8 位。

### A8R8G8B8 {#A8R8G8B8}
```
public static final PixelFormat A8R8G8B8
```


32 位像素格式，Alpha、红、绿、蓝各 8 位。

### B5G6R5 {#B5G6R5}
```
public static final PixelFormat B5G6R5
```


16 位像素格式，红 5 位，绿 6 位，蓝 5 位。

### B8 {#B8}
```
public static final PixelFormat B8
```


8 位像素格式，全部位为蓝色。

### B8G8R8 {#B8G8R8}
```
public static final PixelFormat B8G8R8
```


24 位像素格式，蓝、绿、红各 8 位。

### B8G8R8A8 {#B8G8R8A8}
```
public static final PixelFormat B8G8R8A8
```


32 位像素格式，蓝、绿、红、Alpha 各 8 位。

### BYTE_LA {#BYTE-LA}
```
public static final PixelFormat BYTE_LA
```


2 字节像素格式，1 字节亮度，1 字节 Alpha

### DEPTH {#DEPTH}
```
public static final PixelFormat DEPTH
```


深度纹理格式。

### DXT1 {#DXT1}
```
public static final PixelFormat DXT1
```


DDS（DirectDraw Surface）DXT1 格式。

### DXT2 {#DXT2}
```
public static final PixelFormat DXT2
```


DDS（DirectDraw Surface）DXT2 格式。

### DXT3 {#DXT3}
```
public static final PixelFormat DXT3
```


DDS（DirectDraw Surface）DXT3 格式。

### DXT4 {#DXT4}
```
public static final PixelFormat DXT4
```


DDS（DirectDraw Surface）DXT4 格式。

### DXT5 {#DXT5}
```
public static final PixelFormat DXT5
```


DDS（DirectDraw Surface）DXT5 格式。

### FLOAT16_GR {#FLOAT16-GR}
```
public static final PixelFormat FLOAT16_GR
```


32 位，2 通道 s10e5 浮点像素格式，16 位绿色，16 位红色

### FLOAT16_R {#FLOAT16-R}
```
public static final PixelFormat FLOAT16_R
```


16 位像素格式，16 位（float）用于红色

### FLOAT16_RGB {#FLOAT16-RGB}
```
public static final PixelFormat FLOAT16_RGB
```


48 位像素格式，16 位（float）用于红色，16 位（float）用于绿色，16 位（float）用于蓝色

### FLOAT16_RGBA {#FLOAT16-RGBA}
```
public static final PixelFormat FLOAT16_RGBA
```


64 位像素格式，16 位（float）用于红色，16 位（float）用于绿色，16 位（float）用于蓝色，16 位（float）用于透明度

### FLOAT32_GR {#FLOAT32-GR}
```
public static final PixelFormat FLOAT32_GR
```


64 位，2 通道浮点像素格式，32 位绿色，32 位红色

### FLOAT32_R {#FLOAT32-R}
```
public static final PixelFormat FLOAT32_R
```


32 位像素格式，32 位（float）用于红色

### FLOAT32_RGB {#FLOAT32-RGB}
```
public static final PixelFormat FLOAT32_RGB
```


96 位像素格式，32 位（float）用于红色，32 位（float）用于绿色，32 位（float）用于蓝色

### FLOAT32_RGBA {#FLOAT32-RGBA}
```
public static final PixelFormat FLOAT32_RGBA
```


128 位像素格式，32 位（float）用于红色，32 位（float）用于绿色，32 位（float）用于蓝色，32 位（float）用于透明度

### G8 {#G8}
```
public static final PixelFormat G8
```


8 位像素格式，全部位为绿色。

### L16 {#L16}
```
public static final PixelFormat L16
```


16 位像素格式，全部位为亮度。

### L8 {#L8}
```
public static final PixelFormat L8
```


8 位像素格式，全部位为亮度。

### R32G32B32A32_UINT {#R32G32B32A32-UINT}
```
public static final PixelFormat R32G32B32A32_UINT
```


128 位像素格式，32 位红色（unsigned int），32 位蓝色（unsigned int），32 位绿色（unsigned int），32 位透明度（unsigned int）。

### R32G32_UINT {#R32G32-UINT}
```
public static final PixelFormat R32G32_UINT
```


64 位像素格式，32 位红色（unsigned int），32 位蓝色（unsigned int）。

### R32_UINT {#R32-UINT}
```
public static final PixelFormat R32_UINT
```


32 位像素格式，32 位红色（unsigned int）。

### R3G3B2 {#R3G3B2}
```
public static final PixelFormat R3G3B2
```


8 位像素格式，2 位蓝色，3 位绿色，3 位红色。

### R5G6B5 {#R5G6B5}
```
public static final PixelFormat R5G6B5
```


16 位像素格式，红 5 位，绿 6 位，蓝 5 位。

### R8 {#R8}
```
public static final PixelFormat R8
```


8 位像素格式，全部位为红色。

### R8G8B8 {#R8G8B8}
```
public static final PixelFormat R8G8B8
```


24 位像素格式，8 位用于红色、绿色和蓝色。

### R8G8B8A8 {#R8G8B8A8}
```
public static final PixelFormat R8G8B8A8
```


32 位像素格式，8 位用于红色、绿色、蓝色和透明度。

### SHORT_GR {#SHORT-GR}
```
public static final PixelFormat SHORT_GR
```


32 位像素格式，16 位绿色，16 位红色

### SHORT_RGB {#SHORT-RGB}
```
public static final PixelFormat SHORT_RGB
```


48 位像素格式，16 位用于红色、绿色和蓝色

### SHORT_RGBA {#SHORT-RGBA}
```
public static final PixelFormat SHORT_RGBA
```


64 位像素格式，16 位用于红色、绿色、蓝色和透明度

### UNKNOWN {#UNKNOWN}
```
public static final PixelFormat UNKNOWN
```


未知像素格式。

### X8B8G8R8 {#X8B8G8R8}
```
public static final PixelFormat X8B8G8R8
```


32 位像素格式，8 位用于蓝色，8 位用于绿色，8 位用于红色，如 A8B8G8R8，但透明度将被丢弃

### X8R8G8B8 {#X8R8G8B8}
```
public static final PixelFormat X8R8G8B8
```


32 位像素格式，8 位用于红色，8 位用于绿色，8 位用于蓝色，如 A8R8G8B8，但透明度将被丢弃

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

