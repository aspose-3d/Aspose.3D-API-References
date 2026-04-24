---
title: WrapMode
second_title: Aspose.3D for Java API 레퍼런스
description: 텍스처 랩 모드.
type: docs
weight: 310
url: /ko/java/com.aspose.threed/wrapmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum WrapMode extends Enum<WrapMode>
```

텍스처 랩 모드.
## 필드

| 필드 | 설명 |
| --- | --- |
| [BORDER](#BORDER) | 범위 [0.0, 1.0] 밖에 있는 좌표는 지정된 테두리 색상으로 설정됩니다. |
| [CLAMP](#CLAMP) | 텍스처를 테두리의 마지막 픽셀에 고정합니다. |
| [MIRROR](#MIRROR) | 텍스처가 반복되지만 좌표의 정수 부분이 홀수일 때는 미러링됩니다. |
| [MIRROR_ONCE](#MIRROR-ONCE) | 텍스처가 한 번 미러링된 후 최대값에 고정됩니다. |
| [WRAP](#WRAP) | 모델 표면에 텍스처를 타일링하여 반복 패턴을 생성합니다. |
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
### BORDER {#BORDER}
```
public static final WrapMode BORDER
```


범위 [0.0, 1.0] 밖에 있는 좌표는 지정된 테두리 색상으로 설정됩니다.

### CLAMP {#CLAMP}
```
public static final WrapMode CLAMP
```


텍스처를 테두리의 마지막 픽셀에 고정합니다.

### MIRROR {#MIRROR}
```
public static final WrapMode MIRROR
```


텍스처가 반복되지만 좌표의 정수 부분이 홀수일 때는 미러링됩니다.

### MIRROR_ONCE {#MIRROR-ONCE}
```
public static final WrapMode MIRROR_ONCE
```


텍스처가 한 번 미러링된 후 최대값에 고정됩니다.

### WRAP {#WRAP}
```
public static final WrapMode WRAP
```


모델 표면에 텍스처를 타일링하여 반복 패턴을 생성합니다.

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
public static WrapMode valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode)
### values() {#values--}
```
public static WrapMode[] values()
```




**Returns:**
com.aspose.threed.WrapMode[]
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

