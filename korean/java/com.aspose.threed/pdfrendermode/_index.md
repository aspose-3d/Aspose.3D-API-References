---
title: PdfRenderMode
second_title: Aspose.3D for Java API 레퍼런스
description: 렌더 모드는 3D 아트워크가 렌더링되는 스타일을 지정합니다.
type: docs
weight: 289
url: /ko/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

렌더 모드는 3D 아트워크가 렌더링되는 스타일을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | 각 노드의 경계 상자 가장자리를 표시하며, 해당 노드의 로컬 좌표 공간 축에 맞춥니다. |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | 단일 색상으로 가장자리를 표시하지만, 뒤쪽을 향하거나 가려진 가장자리는 제거합니다. |
| [ILLUSTRATION](#ILLUSTRATION) | 표면과 함께 실루엣 가장자리를 표시하고, 가려진 선을 제거합니다. |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | 조명 및 텍스처가 적용된 표면과 추가적인 방출 항을 사용하여 실루엣 가장자리를 표시하고, 조명이 부족한 영역을 제거합니다. |
| [SHADED_VERTICES](#SHADED-VERTICES) | 정점만 표시하지만, 정점 색상을 사용하고 조명을 적용합니다. |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | 가장자리만 표시하지만, 두 정점 사이의 색상을 보간하고 조명을 적용합니다. |
| [SOLID](#SOLID) | 텍스처와 조명이 적용된 기하학적 형태를 표시합니다. |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | 조명 및 텍스처가 적용된 표면과 함께 실루엣 가장자리를 표시하고, 가려진 선을 제거합니다. |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | 텍스처와 조명이 적용된 기하학적 형태(삼각형)를 표시하고, 그 위에 단일 색상의 가장자리를 추가합니다. |
| [TRANSPARENT](#TRANSPARENT) | 텍스처와 조명이 적용된 기하학적 형태(삼각형)를 표시하며, 투명도를 추가합니다. |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | 각 노드의 경계 상자 면을 표시하고, 해당 노드의 로컬 좌표 공간 축에 맞추며, 투명도를 추가합니다. |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | 각 노드의 경계 상자 가장자리와 면을 표시하고, 해당 노드의 로컬 좌표 공간 축에 맞추며, 투명도를 추가합니다. |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | 텍스처와 조명이 적용된 기하학적 형태(삼각형)를 표시하고, 투명도를 추가하며, 그 위에 단일 색상의 불투명 가장자리를 추가합니다. |
| [VERTICES](#VERTICES) | 단일 색상으로 정점만 표시합니다. |
| [WIREFRAME](#WIREFRAME) | 단일 색상으로 가장자리만 표시합니다. |
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
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


각 노드의 경계 상자 가장자리를 표시하며, 해당 노드의 로컬 좌표 공간 축에 맞춥니다.

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


단일 색상으로 가장자리를 표시하지만, 뒤쪽을 향하거나 가려진 가장자리는 제거합니다.

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


표면과 함께 실루엣 가장자리를 표시하고, 가려진 선을 제거합니다.

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


조명 및 텍스처가 적용된 표면과 추가적인 방출 항을 사용하여 실루엣 가장자리를 표시하고, 조명이 부족한 영역을 제거합니다.

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


정점만 표시하지만, 정점 색상을 사용하고 조명을 적용합니다.

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


가장자리만 표시하지만, 두 정점 사이의 색상을 보간하고 조명을 적용합니다.

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


텍스처와 조명이 적용된 기하학적 형태를 표시합니다.

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


조명 및 텍스처가 적용된 표면과 함께 실루엣 가장자리를 표시하고, 가려진 선을 제거합니다.

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


텍스처와 조명이 적용된 기하학적 형태(삼각형)를 표시하고, 그 위에 단일 색상의 가장자리를 추가합니다.

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


텍스처와 조명이 적용된 기하학적 형태(삼각형)를 표시하며, 투명도를 추가합니다.

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


각 노드의 경계 상자 면을 표시하고, 해당 노드의 로컬 좌표 공간 축에 맞추며, 투명도를 추가합니다.

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


각 노드의 경계 상자 가장자리와 면을 표시하고, 해당 노드의 로컬 좌표 공간 축에 맞추며, 투명도를 추가합니다.

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


텍스처와 조명이 적용된 기하학적 형태(삼각형)를 표시하고, 투명도를 추가하며, 그 위에 단일 색상의 불투명 가장자리를 추가합니다.

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


단일 색상으로 정점만 표시합니다.

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


단일 색상으로 가장자리만 표시합니다.

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
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode)
### values() {#values--}
```
public static PdfRenderMode[] values()
```




**Returns:**
com.aspose.threed.PdfRenderMode[]
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

