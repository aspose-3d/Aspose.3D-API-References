---
title: PixelFormat
second_title: Aspose.3D for Java API 레퍼런스
description: 텍스처 유닛에서 사용되는 픽셀 형식.
type: docs
weight: 290
url: /ko/java/com.aspose.threed/pixelformat/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PixelFormat extends Enum<PixelFormat>
```

텍스처 유닛에서 사용되는 픽셀 형식.
## 필드

| 필드 | 설명 |
| --- | --- |
| [A1R5G5B5](#A1R5G5B5) | 16비트 픽셀 형식, 파란색, 녹색, 빨간색 각각 5비트와 알파 1비트. |
| [A2B10G10R10](#A2B10G10R10) | 32비트 픽셀 형식, 파란색, 녹색, 빨간색 각각 10비트와 알파 2비트. |
| [A2R10G10B10](#A2R10G10B10) | 32비트 픽셀 형식, 알파 2비트와 빨간색, 녹색, 파란색 각각 10비트. |
| [A4L4](#A4L4) | 8비트 픽셀 형식, 알파 4비트와 휘도 4비트. |
| [A4R4G4B4](#A4R4G4B4) | 16비트 픽셀 형식, 알파, 빨간색, 녹색, 파란색 각각 4비트. |
| [A8](#A8) | 8비트 픽셀 형식, 모든 비트가 알파. |
| [A8B8G8R8](#A8B8G8R8) | 32비트 픽셀 형식, 파란색, 녹색, 빨간색 및 알파 각각 8비트. |
| [A8R8G8B8](#A8R8G8B8) | 32비트 픽셀 형식, 알파, 빨간색, 녹색, 파란색 각각 8비트. |
| [B5G6R5](#B5G6R5) | 16비트 픽셀 형식, 빨간색 5비트, 녹색 6비트, 파란색 5비트. |
| [B8](#B8) | 8비트 픽셀 형식, 모든 비트가 파란색. |
| [B8G8R8](#B8G8R8) | 24비트 픽셀 형식, 파란색, 녹색, 빨간색 각각 8비트. |
| [B8G8R8A8](#B8G8R8A8) | 32비트 픽셀 형식, 파란색, 녹색, 빨간색 및 알파 각각 8비트. |
| [BYTE_LA](#BYTE-LA) | 2바이트 픽셀 형식, 휘도 1바이트와 알파 1바이트. |
| [DEPTH](#DEPTH) | 깊이 텍스처 형식. |
| [DXT1](#DXT1) | DDS (DirectDraw Surface) DXT1 형식. |
| [DXT2](#DXT2) | DDS (DirectDraw Surface) DXT2 형식. |
| [DXT3](#DXT3) | DDS (DirectDraw Surface) DXT3 형식. |
| [DXT4](#DXT4) | DDS (DirectDraw Surface) DXT4 형식. |
| [DXT5](#DXT5) | DDS (DirectDraw Surface) DXT5 형식. |
| [FLOAT16_GR](#FLOAT16-GR) | 32비트, 2채널 s10e5 부동 소수점 픽셀 형식, 16비트 녹색, 16비트 빨강 |
| [FLOAT16_R](#FLOAT16-R) | 16비트 픽셀 형식, 빨강에 16비트 (부동 소수점) |
| [FLOAT16_RGB](#FLOAT16-RGB) | 48비트 픽셀 형식, 빨강에 16비트 (부동 소수점), 녹색에 16비트 (부동 소수점), 파랑에 16비트 (부동 소수점) |
| [FLOAT16_RGBA](#FLOAT16-RGBA) | 64비트 픽셀 형식, 빨강에 16비트 (부동 소수점), 녹색에 16비트 (부동 소수점), 파랑에 16비트 (부동 소수점), 알파에 16비트 (부동 소수점) |
| [FLOAT32_GR](#FLOAT32-GR) | 64비트, 2채널 부동 소수점 픽셀 형식, 32비트 녹색, 32비트 빨강 |
| [FLOAT32_R](#FLOAT32-R) | 32비트 픽셀 형식, 빨강에 32비트 (부동 소수점) |
| [FLOAT32_RGB](#FLOAT32-RGB) | 96비트 픽셀 형식, 빨강에 32비트 (부동 소수점), 녹색에 32비트 (부동 소수점), 파랑에 32비트 (부동 소수점) |
| [FLOAT32_RGBA](#FLOAT32-RGBA) | 128비트 픽셀 형식, 빨강에 32비트 (부동 소수점), 녹색에 32비트 (부동 소수점), 파랑에 32비트 (부동 소수점), 알파에 32비트 (부동 소수점) |
| [G8](#G8) | 8비트 픽셀 형식, 모든 비트가 녹색. |
| [L16](#L16) | 16비트 픽셀 형식, 모든 비트가 휘도. |
| [L8](#L8) | 8비트 픽셀 형식, 모든 비트가 휘도. |
| [R32G32B32A32_UINT](#R32G32B32A32-UINT) | 128비트 픽셀 형식, 32비트 빨강 (부호 없는 정수), 32비트 파랑 (부호 없는 정수), 32비트 녹색 (부호 없는 정수), 32비트 알파 (부호 없는 정수). |
| [R32G32_UINT](#R32G32-UINT) | 64비트 픽셀 형식, 32비트 빨강 (부호 없는 정수), 32비트 파랑 (부호 없는 정수). |
| [R32_UINT](#R32-UINT) | 32비트 픽셀 형식, 32비트 빨강 (부호 없는 정수). |
| [R3G3B2](#R3G3B2) | 8비트 픽셀 형식, 2비트 파랑, 3비트 녹색, 3비트 빨강. |
| [R5G6B5](#R5G6B5) | 16비트 픽셀 형식, 빨간색 5비트, 녹색 6비트, 파란색 5비트. |
| [R8](#R8) | 8비트 픽셀 형식, 모든 비트가 빨강. |
| [R8G8B8](#R8G8B8) | 24비트 픽셀 형식, 빨강, 녹색 및 파랑에 각각 8비트. |
| [R8G8B8A8](#R8G8B8A8) | 32비트 픽셀 형식, 빨강, 녹색, 파랑 및 알파에 각각 8비트. |
| [SHORT_GR](#SHORT-GR) | 32비트 픽셀 형식, 16비트 녹색, 16비트 빨강 |
| [SHORT_RGB](#SHORT-RGB) | 48비트 픽셀 형식, 빨강, 녹색 및 파랑에 각각 16비트 |
| [SHORT_RGBA](#SHORT-RGBA) | 64비트 픽셀 형식, 빨강, 녹색, 파랑 및 알파에 각각 16비트 |
| [UNKNOWN](#UNKNOWN) | 알 수 없는 픽셀 형식. |
| [X8B8G8R8](#X8B8G8R8) | 32비트 픽셀 형식, 파랑에 8비트, 녹색에 8비트, 빨강에 8비트 (A8B8G8R8와 같이), 하지만 알파는 버려집니다. |
| [X8R8G8B8](#X8R8G8B8) | 32비트 픽셀 형식, 빨강에 8비트, 녹색에 8비트, 파랑에 8비트 (A8R8G8B8와 같이), 하지만 알파는 버려집니다. |
## 메서드

| 메서드 | 설명 |
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


16비트 픽셀 형식, 파란색, 녹색, 빨간색 각각 5비트와 알파 1비트.

### A2B10G10R10 {#A2B10G10R10}
```
public static final PixelFormat A2B10G10R10
```


32비트 픽셀 형식, 파란색, 녹색, 빨간색 각각 10비트와 알파 2비트.

### A2R10G10B10 {#A2R10G10B10}
```
public static final PixelFormat A2R10G10B10
```


32비트 픽셀 형식, 알파 2비트와 빨간색, 녹색, 파란색 각각 10비트.

### A4L4 {#A4L4}
```
public static final PixelFormat A4L4
```


8비트 픽셀 형식, 알파 4비트와 휘도 4비트.

### A4R4G4B4 {#A4R4G4B4}
```
public static final PixelFormat A4R4G4B4
```


16비트 픽셀 형식, 알파, 빨간색, 녹색, 파란색 각각 4비트.

### A8 {#A8}
```
public static final PixelFormat A8
```


8비트 픽셀 형식, 모든 비트가 알파.

### A8B8G8R8 {#A8B8G8R8}
```
public static final PixelFormat A8B8G8R8
```


32비트 픽셀 형식, 파란색, 녹색, 빨간색 및 알파 각각 8비트.

### A8R8G8B8 {#A8R8G8B8}
```
public static final PixelFormat A8R8G8B8
```


32비트 픽셀 형식, 알파, 빨간색, 녹색, 파란색 각각 8비트.

### B5G6R5 {#B5G6R5}
```
public static final PixelFormat B5G6R5
```


16비트 픽셀 형식, 빨간색 5비트, 녹색 6비트, 파란색 5비트.

### B8 {#B8}
```
public static final PixelFormat B8
```


8비트 픽셀 형식, 모든 비트가 파란색.

### B8G8R8 {#B8G8R8}
```
public static final PixelFormat B8G8R8
```


24비트 픽셀 형식, 파란색, 녹색, 빨간색 각각 8비트.

### B8G8R8A8 {#B8G8R8A8}
```
public static final PixelFormat B8G8R8A8
```


32비트 픽셀 형식, 파란색, 녹색, 빨간색 및 알파 각각 8비트.

### BYTE_LA {#BYTE-LA}
```
public static final PixelFormat BYTE_LA
```


2바이트 픽셀 형식, 휘도 1바이트와 알파 1바이트.

### DEPTH {#DEPTH}
```
public static final PixelFormat DEPTH
```


깊이 텍스처 형식.

### DXT1 {#DXT1}
```
public static final PixelFormat DXT1
```


DDS (DirectDraw Surface) DXT1 형식.

### DXT2 {#DXT2}
```
public static final PixelFormat DXT2
```


DDS (DirectDraw Surface) DXT2 형식.

### DXT3 {#DXT3}
```
public static final PixelFormat DXT3
```


DDS (DirectDraw Surface) DXT3 형식.

### DXT4 {#DXT4}
```
public static final PixelFormat DXT4
```


DDS (DirectDraw Surface) DXT4 형식.

### DXT5 {#DXT5}
```
public static final PixelFormat DXT5
```


DDS (DirectDraw Surface) DXT5 형식.

### FLOAT16_GR {#FLOAT16-GR}
```
public static final PixelFormat FLOAT16_GR
```


32비트, 2채널 s10e5 부동 소수점 픽셀 형식, 16비트 녹색, 16비트 빨강

### FLOAT16_R {#FLOAT16-R}
```
public static final PixelFormat FLOAT16_R
```


16비트 픽셀 형식, 빨강에 16비트 (부동 소수점)

### FLOAT16_RGB {#FLOAT16-RGB}
```
public static final PixelFormat FLOAT16_RGB
```


48비트 픽셀 형식, 빨강에 16비트 (부동 소수점), 녹색에 16비트 (부동 소수점), 파랑에 16비트 (부동 소수점)

### FLOAT16_RGBA {#FLOAT16-RGBA}
```
public static final PixelFormat FLOAT16_RGBA
```


64비트 픽셀 형식, 빨강에 16비트 (부동 소수점), 녹색에 16비트 (부동 소수점), 파랑에 16비트 (부동 소수점), 알파에 16비트 (부동 소수점)

### FLOAT32_GR {#FLOAT32-GR}
```
public static final PixelFormat FLOAT32_GR
```


64비트, 2채널 부동 소수점 픽셀 형식, 32비트 녹색, 32비트 빨강

### FLOAT32_R {#FLOAT32-R}
```
public static final PixelFormat FLOAT32_R
```


32비트 픽셀 형식, 빨강에 32비트 (부동 소수점)

### FLOAT32_RGB {#FLOAT32-RGB}
```
public static final PixelFormat FLOAT32_RGB
```


96비트 픽셀 형식, 빨강에 32비트 (부동 소수점), 녹색에 32비트 (부동 소수점), 파랑에 32비트 (부동 소수점)

### FLOAT32_RGBA {#FLOAT32-RGBA}
```
public static final PixelFormat FLOAT32_RGBA
```


128비트 픽셀 형식, 빨강에 32비트 (부동 소수점), 녹색에 32비트 (부동 소수점), 파랑에 32비트 (부동 소수점), 알파에 32비트 (부동 소수점)

### G8 {#G8}
```
public static final PixelFormat G8
```


8비트 픽셀 형식, 모든 비트가 녹색.

### L16 {#L16}
```
public static final PixelFormat L16
```


16비트 픽셀 형식, 모든 비트가 휘도.

### L8 {#L8}
```
public static final PixelFormat L8
```


8비트 픽셀 형식, 모든 비트가 휘도.

### R32G32B32A32_UINT {#R32G32B32A32-UINT}
```
public static final PixelFormat R32G32B32A32_UINT
```


128비트 픽셀 형식, 32비트 빨강 (부호 없는 정수), 32비트 파랑 (부호 없는 정수), 32비트 녹색 (부호 없는 정수), 32비트 알파 (부호 없는 정수).

### R32G32_UINT {#R32G32-UINT}
```
public static final PixelFormat R32G32_UINT
```


64비트 픽셀 형식, 32비트 빨강 (부호 없는 정수), 32비트 파랑 (부호 없는 정수).

### R32_UINT {#R32-UINT}
```
public static final PixelFormat R32_UINT
```


32비트 픽셀 형식, 32비트 빨강 (부호 없는 정수).

### R3G3B2 {#R3G3B2}
```
public static final PixelFormat R3G3B2
```


8비트 픽셀 형식, 2비트 파랑, 3비트 녹색, 3비트 빨강.

### R5G6B5 {#R5G6B5}
```
public static final PixelFormat R5G6B5
```


16비트 픽셀 형식, 빨간색 5비트, 녹색 6비트, 파란색 5비트.

### R8 {#R8}
```
public static final PixelFormat R8
```


8비트 픽셀 형식, 모든 비트가 빨강.

### R8G8B8 {#R8G8B8}
```
public static final PixelFormat R8G8B8
```


24비트 픽셀 형식, 빨강, 녹색 및 파랑에 각각 8비트.

### R8G8B8A8 {#R8G8B8A8}
```
public static final PixelFormat R8G8B8A8
```


32비트 픽셀 형식, 빨강, 녹색, 파랑 및 알파에 각각 8비트.

### SHORT_GR {#SHORT-GR}
```
public static final PixelFormat SHORT_GR
```


32비트 픽셀 형식, 16비트 녹색, 16비트 빨강

### SHORT_RGB {#SHORT-RGB}
```
public static final PixelFormat SHORT_RGB
```


48비트 픽셀 형식, 빨강, 녹색 및 파랑에 각각 16비트

### SHORT_RGBA {#SHORT-RGBA}
```
public static final PixelFormat SHORT_RGBA
```


64비트 픽셀 형식, 빨강, 녹색, 파랑 및 알파에 각각 16비트

### UNKNOWN {#UNKNOWN}
```
public static final PixelFormat UNKNOWN
```


알 수 없는 픽셀 형식.

### X8B8G8R8 {#X8B8G8R8}
```
public static final PixelFormat X8B8G8R8
```


32비트 픽셀 형식, 파랑에 8비트, 녹색에 8비트, 빨강에 8비트 (A8B8G8R8와 같이), 하지만 알파는 버려집니다.

### X8R8G8B8 {#X8R8G8B8}
```
public static final PixelFormat X8R8G8B8
```


32비트 픽셀 형식, 빨강에 8비트, 녹색에 8비트, 파랑에 8비트 (A8R8G8B8와 같이), 하지만 알파는 버려집니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

