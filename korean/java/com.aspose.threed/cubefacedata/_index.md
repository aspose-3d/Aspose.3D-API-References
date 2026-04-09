---
title: CubeFaceData
second_title: Aspose.3D for Java API 레퍼런스
description: 큐브 맵 텍스처의 각 면에 대한 데이터.
type: docs
weight: 36
url: /ko/java/com.aspose.threed/cubefacedata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class CubeFaceData<T> implements Struct<CubeFaceData<T>>, Serializable
```

큐브 맵 텍스처의 각 면에 대한 데이터.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CubeFaceData()](#CubeFaceData--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(CubeFaceData<T> src)](#copyFrom-com.aspose.threed.CubeFaceData-T--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [get(CubeFace face)](#get-com.aspose.threed.CubeFace-) | 지정된 면에 대한 데이터를 가져옵니다. |
| [getBack()](#getBack--) | +Z(Back) 면에 대한 데이터를 가져옵니다. |
| [getBottom()](#getBottom--) | -Y(Bottom) 면에 대한 데이터를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getFront()](#getFront--) | -Z(Front) 면에 대한 데이터를 가져옵니다. |
| [getLeft()](#getLeft--) | +X(Left) 면에 대한 데이터를 가져옵니다. |
| [getNegativeX()](#getNegativeX--) | +X(Left) 면에 대한 데이터를 가져옵니다. |
| [getNegativeY()](#getNegativeY--) | -Y(Bottom) 면에 대한 데이터를 가져옵니다. |
| [getNegativeZ()](#getNegativeZ--) | -Z(Front) 면에 대한 데이터를 가져옵니다. |
| [getPositiveX()](#getPositiveX--) | +X(Right) 면에 대한 데이터를 가져옵니다. |
| [getPositiveY()](#getPositiveY--) | +Y(Top) 면에 대한 데이터를 가져옵니다. |
| [getPositiveZ()](#getPositiveZ--) | +Z(Back) 면에 대한 데이터를 가져옵니다. |
| [getRight()](#getRight--) | +X(Right) 면에 대한 데이터를 가져옵니다. |
| [getTop()](#getTop--) | +Y(Top) 면에 대한 데이터를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(CubeFace face, T value)](#set-com.aspose.threed.CubeFace-T-) | Sets the data for specified face |
| [setBack(T value)](#setBack-T-) | Sets the data for +Z(Back) face |
| [setBottom(T value)](#setBottom-T-) | Sets the data for -Y(Bottom) face |
| [setFront(T value)](#setFront-T-) | Sets the data for -Z(Front) face |
| [setLeft(T value)](#setLeft-T-) | Sets the data for +X(Left) face |
| [setNegativeX(T value)](#setNegativeX-T-) | Sets the data for +X(Left) face |
| [setNegativeY(T value)](#setNegativeY-T-) | Sets the data for -Y(Bottom) face |
| [setNegativeZ(T value)](#setNegativeZ-T-) | Sets the data for -Z(Front) face |
| [setPositiveX(T value)](#setPositiveX-T-) | Sets the data for +X(Right) face |
| [setPositiveY(T value)](#setPositiveY-T-) | Sets the data for +Y(Top) face |
| [setPositiveZ(T value)](#setPositiveZ-T-) | Sets the data for +Z(Back) face |
| [setRight(T value)](#setRight-T-) | Sets the data for +X(Right) face |
| [setTop(T value)](#setTop-T-) | Sets the data for +Y(Top) face |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CubeFaceData() {#CubeFaceData--}
```
public CubeFaceData()
```


### clone() {#clone--}
```
public CubeFaceData<T> clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[CubeFaceData](../../com.aspose.threed/cubefacedata)
### copyFrom(CubeFaceData<T> src) {#copyFrom-com.aspose.threed.CubeFaceData-T--}
```
public void copyFrom(CubeFaceData<T> src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [CubeFaceData](../../com.aspose.threed/cubefacedata) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### get(CubeFace face) {#get-com.aspose.threed.CubeFace-}
```
public T get(CubeFace face)
```


지정된 면에 대한 데이터를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
T - the data for specified face
### getBack() {#getBack--}
```
public T getBack()
```


+Z(Back) 면에 대한 데이터를 가져옵니다.

**Returns:**
T - the data for +Z(Back) face
### getBottom() {#getBottom--}
```
public T getBottom()
```


-Y(Bottom) 면에 대한 데이터를 가져옵니다.

**Returns:**
T - the data for -Y(Bottom) face
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFront() {#getFront--}
```
public T getFront()
```


-Z(Front) 면에 대한 데이터를 가져옵니다.

**Returns:**
T - the data for -Z(Front) face
### getLeft() {#getLeft--}
```
public T getLeft()
```


+X(Left) 면에 대한 데이터를 가져옵니다.

**Returns:**
T - the data for +X(Left) face
### getNegativeX() {#getNegativeX--}
```
public T getNegativeX()
```


+X(Left) 면에 대한 데이터를 가져옵니다.

**Returns:**
T - the data for +X(Left) face
### getNegativeY() {#getNegativeY--}
```
public T getNegativeY()
```


-Y(Bottom) 면에 대한 데이터를 가져옵니다.

**Returns:**
T - the data for -Y(Bottom) face
### getNegativeZ() {#getNegativeZ--}
```
public T getNegativeZ()
```


-Z(Front) 면에 대한 데이터를 가져옵니다.

**Returns:**
T - the data for -Z(Front) face
### getPositiveX() {#getPositiveX--}
```
public T getPositiveX()
```


+X(Right) 면에 대한 데이터를 가져옵니다.

**Returns:**
T - the data for +X(Right) face
### getPositiveY() {#getPositiveY--}
```
public T getPositiveY()
```


+Y(Top) 면에 대한 데이터를 가져옵니다.

**Returns:**
T - the data for +Y(Top) face
### getPositiveZ() {#getPositiveZ--}
```
public T getPositiveZ()
```


+Z(Back) 면에 대한 데이터를 가져옵니다.

**Returns:**
T - the data for +Z(Back) face
### getRight() {#getRight--}
```
public T getRight()
```


+X(Right) 면에 대한 데이터를 가져옵니다.

**Returns:**
T - the data for +X(Right) face
### getTop() {#getTop--}
```
public T getTop()
```


+Y(Top) 면에 대한 데이터를 가져옵니다.

**Returns:**
T - the data for +Y(Top) face
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(CubeFace face, T value) {#set-com.aspose.threed.CubeFace-T-}
```
public void set(CubeFace face, T value)
```


Sets the data for specified face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| 값 | T | 새 값 |

### setBack(T value) {#setBack-T-}
```
public void setBack(T value)
```


Sets the data for +Z(Back) face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 새 값 |

### setBottom(T value) {#setBottom-T-}
```
public void setBottom(T value)
```


Sets the data for -Y(Bottom) face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 새 값 |

### setFront(T value) {#setFront-T-}
```
public void setFront(T value)
```


Sets the data for -Z(Front) face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 새 값 |

### setLeft(T value) {#setLeft-T-}
```
public void setLeft(T value)
```


Sets the data for +X(Left) face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 새 값 |

### setNegativeX(T value) {#setNegativeX-T-}
```
public void setNegativeX(T value)
```


Sets the data for +X(Left) face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 새 값 |

### setNegativeY(T value) {#setNegativeY-T-}
```
public void setNegativeY(T value)
```


Sets the data for -Y(Bottom) face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 새 값 |

### setNegativeZ(T value) {#setNegativeZ-T-}
```
public void setNegativeZ(T value)
```


Sets the data for -Z(Front) face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 새 값 |

### setPositiveX(T value) {#setPositiveX-T-}
```
public void setPositiveX(T value)
```


Sets the data for +X(Right) face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 새 값 |

### setPositiveY(T value) {#setPositiveY-T-}
```
public void setPositiveY(T value)
```


Sets the data for +Y(Top) face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 새 값 |

### setPositiveZ(T value) {#setPositiveZ-T-}
```
public void setPositiveZ(T value)
```


Sets the data for +Z(Back) face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 새 값 |

### setRight(T value) {#setRight-T-}
```
public void setRight(T value)
```


Sets the data for +X(Right) face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 새 값 |

### setTop(T value) {#setTop-T-}
```
public void setTop(T value)
```


Sets the data for +Y(Top) face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 새 값 |

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

