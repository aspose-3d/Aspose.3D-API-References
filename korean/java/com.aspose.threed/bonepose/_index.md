---
title: BonePose
second_title: Aspose.3D for Java API 레퍼런스
description: 뼈 노드에 대한 변환 행렬을 포함합니다
type: docs
weight: 21
url: /ko/java/com.aspose.threed/bonepose/
---

**Inheritance:**
java.lang.Object
```
public class BonePose
```

[BonePose](../../com.aspose.threed/bonepose)은 뼈 노드에 대한 변환 행렬을 포함합니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [BonePose()](#BonePose--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | 현재 포즈에서 노드의 변환 행렬을 가져옵니다. |
| [getNode()](#getNode--) | 스킨된 스켈레톤 노드를 가리키는 씬 노드를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isLocal()](#isLocal--) | 행렬이 로컬 좌표계에 정의되어 있는지 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLocal(boolean value)](#setLocal-boolean-) | 행렬이 로컬 좌표계에 정의되어 있는지 설정합니다. |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | 현재 포즈에서 노드의 변환 행렬을 설정합니다. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | 스킨된 스켈레톤 노드를 가리키는 씬 노드를 설정합니다 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BonePose() {#BonePose--}
```
public BonePose()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
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
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


현재 포즈에서 노드의 변환 행렬을 가져옵니다.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node in current pose.
### getNode() {#getNode--}
```
public Node getNode()
```


스킨된 스켈레톤 노드를 가리키는 씬 노드를 가져옵니다.

**Returns:**
[Node](../../com.aspose.threed/node) - the scene node, points to a skinned skeleton node
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLocal() {#isLocal--}
```
public boolean isLocal()
```


행렬이 로컬 좌표계에 정의되어 있는지 가져옵니다.

**Returns:**
boolean - 행렬이 로컬 좌표계에 정의되어 있는지 여부.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLocal(boolean value) {#setLocal-boolean-}
```
public void setLocal(boolean value)
```


행렬이 로컬 좌표계에 정의되어 있는지 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


현재 포즈에서 노드의 변환 행렬을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | 새 값 |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


스킨된 스켈레톤 노드를 가리키는 씬 노드를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 새 값 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

