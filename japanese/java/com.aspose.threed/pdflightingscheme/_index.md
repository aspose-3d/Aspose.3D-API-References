---
title: PdfLightingScheme
second_title: Aspose.3D for Java API リファレンス
description: LightingScheme は 3D アートワークに適用するライティングを指定します。
type: docs
weight: 288
url: /ja/java/com.aspose.threed/pdflightingscheme/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfLightingScheme extends Enum<PdfLightingScheme>
```

LightingScheme は 3D アートワークに適用するライティングを指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ARTWORK](#ARTWORK) | シーンで定義されたライトを使用します |
| [BLUE](#BLUE) | 青の無限光が3つ、アンビエント項なし |
| [CAD](#CAD) | 灰色の無限光が3つとカメラに取り付けられた光が1つ、アンビエント項なし |
| [CUBE](#CUBE) | 主要軸に沿った灰色の無限光が6つ、アンビエント項なし |
| [DAY](#DAY) | 薄灰色の無限光が3つ、アンビエント項なし |
| [HARD](#HARD) | 灰色の無限光が3つ、中程度のアンビエント項 |
| [HEADLAMP](#HEADLAMP) | カメラに取り付けられた単一の無限光、低いアンビエント項 |
| [NIGHT](#NIGHT) | 黄色、アクア、青の無限光がそれぞれ1つ、アンビエント項なし |
| [NONE](#NONE) | ライトは使用されていません。 |
| [PRIMARY](#PRIMARY) | 赤、緑、青の無限光がそれぞれ1つ、アンビエント項なし |
| [RED](#RED) | 赤の無限光が3つ、アンビエント項なし |
| [WHITE](#WHITE) | 3つの青灰色の無限光、環境光項なし |
## Methods

| Method | 説明 |
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


シーンで定義されたライトを使用します

### BLUE {#BLUE}
```
public static final PdfLightingScheme BLUE
```


青の無限光が3つ、アンビエント項なし

### CAD {#CAD}
```
public static final PdfLightingScheme CAD
```


灰色の無限光が3つとカメラに取り付けられた光が1つ、アンビエント項なし

### CUBE {#CUBE}
```
public static final PdfLightingScheme CUBE
```


主要軸に沿った灰色の無限光が6つ、アンビエント項なし

### DAY {#DAY}
```
public static final PdfLightingScheme DAY
```


薄灰色の無限光が3つ、アンビエント項なし

### HARD {#HARD}
```
public static final PdfLightingScheme HARD
```


灰色の無限光が3つ、中程度のアンビエント項

### HEADLAMP {#HEADLAMP}
```
public static final PdfLightingScheme HEADLAMP
```


カメラに取り付けられた単一の無限光、低いアンビエント項

### NIGHT {#NIGHT}
```
public static final PdfLightingScheme NIGHT
```


黄色、アクア、青の無限光がそれぞれ1つ、アンビエント項なし

### NONE {#NONE}
```
public static final PdfLightingScheme NONE
```


ライトは使用されていません。

### PRIMARY {#PRIMARY}
```
public static final PdfLightingScheme PRIMARY
```


赤、緑、青の無限光がそれぞれ1つ、アンビエント項なし

### RED {#RED}
```
public static final PdfLightingScheme RED
```


赤の無限光が3つ、アンビエント項なし

### WHITE {#WHITE}
```
public static final PdfLightingScheme WHITE
```


3つの青灰色の無限光、環境光項なし

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
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
| Parameter | Type | 説明 |
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
| Parameter | Type | 説明 |
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
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

