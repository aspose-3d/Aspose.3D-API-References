---
title: ApertureMode
second_title: Aspose.3D for Java API 레퍼런스
description: 카메라 조리개 모드.
type: docs
weight: 264
url: /ko/java/com.aspose.threed/aperturemode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ApertureMode extends Enum<ApertureMode>
```

카메라 조리개 모드. 조리개 모드는 어떤 값이 카메라 조리개를 제어하는지를 결정합니다. 조리개 모드가 HorizAndVert, Horizontal, 또는 Vertical인 경우 시야각이 사용됩니다. 조리개 모드가 FocalLength인 경우 초점 거리가 사용됩니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [FOCAL_LENGTH](#FOCAL-LENGTH) | 초점 거리를 직접 사용합니다. |
| [HORIZONTAL](#HORIZONTAL) | 수평 각도만 설정합니다. |
| [HORIZ_AND_VERT](#HORIZ-AND-VERT) | 수평 및 수직 설정 모두에 대한 각도 값을 설정합니다. |
| [VERTICAL](#VERTICAL) | 수직 각도만 설정합니다. |
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
### FOCAL_LENGTH {#FOCAL-LENGTH}
```
public static final ApertureMode FOCAL_LENGTH
```


초점 거리를 직접 사용합니다.

### HORIZONTAL {#HORIZONTAL}
```
public static final ApertureMode HORIZONTAL
```


수평 각도만 설정합니다.

### HORIZ_AND_VERT {#HORIZ-AND-VERT}
```
public static final ApertureMode HORIZ_AND_VERT
```


수평 및 수직 설정 모두에 대한 각도 값을 설정합니다.

### VERTICAL {#VERTICAL}
```
public static final ApertureMode VERTICAL
```


수직 각도만 설정합니다.

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
public static ApertureMode valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode)
### values() {#values--}
```
public static ApertureMode[] values()
```




**Returns:**
com.aspose.threed.ApertureMode[]
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

