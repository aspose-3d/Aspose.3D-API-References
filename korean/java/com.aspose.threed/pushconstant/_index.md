---
title: PushConstant
second_title: Aspose.3D for Java API 레퍼런스
description: 푸시 상수를 통해 셰이더에 데이터를 제공하는 유틸리티입니다.
type: docs
weight: 141
url: /ko/java/com.aspose.threed/pushconstant/
---

**Inheritance:**
java.lang.Object
```
public class PushConstant
```

푸시 상수를 통해 셰이더에 데이터를 제공하는 유틸리티입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PushConstant()](#PushConstant--) | [PushConstant](../../com.aspose.threed/pushconstant)의 생성자 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [commit(int stage, ICommandList commandList)](#commit-int-com.aspose.threed.ICommandList-) | 준비된 데이터를 그래픽 파이프라인에 커밋합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(FMatrix4 mat)](#write-com.aspose.threed.FMatrix4-) | 행렬을 상수에 기록합니다 |
| [write(FVector3 vec)](#write-com.aspose.threed.FVector3-) | 3요소 벡터를 상수에 기록합니다 |
| [write(FVector4 vec)](#write-com.aspose.threed.FVector4-) | 4요소 벡터를 상수에 기록합니다 |
| [write(float f)](#write-float-) | float 값을 상수에 기록합니다 |
| [write(float x, float y, float z, float w)](#write-float-float-float-float-) | 4요소 벡터를 상수에 기록합니다 |
| [write(int n)](#write-int-) | int 값을 상수에 기록합니다 |
### PushConstant() {#PushConstant--}
```
public PushConstant()
```


[PushConstant](../../com.aspose.threed/pushconstant)의 생성자

### commit(int stage, ICommandList commandList) {#commit-int-com.aspose.threed.ICommandList-}
```
public PushConstant commit(int stage, ICommandList commandList)
```


준비된 데이터를 그래픽 파이프라인에 커밋합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 단계 | int |  |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
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
### hashCode() {#hashCode--}
```
public native int hashCode()
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

### write(FMatrix4 mat) {#write-com.aspose.threed.FMatrix4-}
```
public PushConstant write(FMatrix4 mat)
```


행렬을 상수에 기록합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | 기록할 행렬 |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector3 vec) {#write-com.aspose.threed.FVector3-}
```
public PushConstant write(FVector3 vec)
```


3요소 벡터를 상수에 기록합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector4 vec) {#write-com.aspose.threed.FVector4-}
```
public PushConstant write(FVector4 vec)
```


4요소 벡터를 상수에 기록합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float f) {#write-float-}
```
public PushConstant write(float f)
```


float 값을 상수에 기록합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| f | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float x, float y, float z, float w) {#write-float-float-float-float-}
```
public PushConstant write(float x, float y, float z, float w)
```


4요소 벡터를 상수에 기록합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| z | float |  |
| w | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(int n) {#write-int-}
```
public PushConstant write(int n)
```


int 값을 상수에 기록합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| n | int |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
