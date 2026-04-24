---
title: PdfLightingScheme
second_title: Aspose.3D for Java API 레퍼런스
description: LightingScheme은 3D 아트워크에 적용할 조명을 지정합니다.
type: docs
weight: 288
url: /ko/java/com.aspose.threed/pdflightingscheme/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfLightingScheme extends Enum<PdfLightingScheme>
```

LightingScheme은 3D 아트워크에 적용할 조명을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [ARTWORK](#ARTWORK) | 씬에 정의된 조명을 사용합니다 |
| [BLUE](#BLUE) | 파란색 무한 광원 3개, 주변광 없음 |
| [CAD](#CAD) | 회색 무한 광원 3개와 카메라에 부착된 광원 1개, 주변광 없음 |
| [CUBE](#CUBE) | 주축에 정렬된 회색 무한 광원 6개, 주변광 없음 |
| [DAY](#DAY) | 연회색 무한 광원 3개, 주변광 없음 |
| [HARD](#HARD) | 회색 무한 광원 3개, 중간 정도의 주변광 |
| [HEADLAMP](#HEADLAMP) | 카메라에 부착된 단일 무한 광원, 낮은 주변광 |
| [NIGHT](#NIGHT) | 노란색, 청록색, 파란색 무한 광원 각각 1개씩, 주변광 없음 |
| [NONE](#NONE) | 조명이 사용되지 않습니다. |
| [PRIMARY](#PRIMARY) | 빨간색, 초록색, 파란색 무한 광원 각각 1개씩, 주변광 없음 |
| [RED](#RED) | 빨간색 무한 광원 3개, 주변광 없음 |
| [WHITE](#WHITE) | 세 개의 파란‑회색 무한 조명, 주변광 없음 |
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
### ARTWORK {#ARTWORK}
```
public static final PdfLightingScheme ARTWORK
```


씬에 정의된 조명을 사용합니다

### BLUE {#BLUE}
```
public static final PdfLightingScheme BLUE
```


파란색 무한 광원 3개, 주변광 없음

### CAD {#CAD}
```
public static final PdfLightingScheme CAD
```


회색 무한 광원 3개와 카메라에 부착된 광원 1개, 주변광 없음

### CUBE {#CUBE}
```
public static final PdfLightingScheme CUBE
```


주축에 정렬된 회색 무한 광원 6개, 주변광 없음

### DAY {#DAY}
```
public static final PdfLightingScheme DAY
```


연회색 무한 광원 3개, 주변광 없음

### HARD {#HARD}
```
public static final PdfLightingScheme HARD
```


회색 무한 광원 3개, 중간 정도의 주변광

### HEADLAMP {#HEADLAMP}
```
public static final PdfLightingScheme HEADLAMP
```


카메라에 부착된 단일 무한 광원, 낮은 주변광

### NIGHT {#NIGHT}
```
public static final PdfLightingScheme NIGHT
```


노란색, 청록색, 파란색 무한 광원 각각 1개씩, 주변광 없음

### NONE {#NONE}
```
public static final PdfLightingScheme NONE
```


조명이 사용되지 않습니다.

### PRIMARY {#PRIMARY}
```
public static final PdfLightingScheme PRIMARY
```


빨간색, 초록색, 파란색 무한 광원 각각 1개씩, 주변광 없음

### RED {#RED}
```
public static final PdfLightingScheme RED
```


빨간색 무한 광원 3개, 주변광 없음

### WHITE {#WHITE}
```
public static final PdfLightingScheme WHITE
```


세 개의 파란‑회색 무한 조명, 주변광 없음

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
public static PdfLightingScheme valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[PdfLightingScheme](../../com.aspose.threed/pdflightingscheme)
### values() {#values--}
```
public static PdfLightingScheme[] values()
```




**Returns:**
com.aspose.threed.PdfLightingScheme[]
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

