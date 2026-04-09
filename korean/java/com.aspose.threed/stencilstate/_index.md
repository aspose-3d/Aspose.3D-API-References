---
title: StencilState
second_title: Aspose.3D for Java API 레퍼런스
description: 각 면에 대한 스텐실 상태.
type: docs
weight: 175
url: /ko/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

각 면에 대한 스텐실 상태.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 객체와 같은지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | 스텐실 테스트에 사용되는 비교 함수를 가져옵니다. |
| [getDepthFailAction()](#getDepthFailAction--) | 스텐실 테스트는 통과했지만 깊이 테스트가 실패했을 때의 스텐실 동작을 가져옵니다. |
| [getFailAction()](#getFailAction--) | 스텐실 테스트가 실패했을 때의 스텐실 동작을 가져옵니다. |
| [getPassAction()](#getPassAction--) | 스텐실 테스트와 깊이 테스트가 모두 통과했을 때의 스텐실 동작을 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | 스텐실 테스트에 사용되는 비교 함수를 설정합니다. |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | 스텐실 테스트는 통과했지만 깊이 테스트가 실패했을 때의 스텐실 동작을 설정합니다. |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | 스텐실 테스트가 실패했을 때의 스텐실 동작을 설정합니다. |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | 스텐실 테스트와 깊이 테스트가 모두 통과했을 때의 스텐실 동작을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 객체와 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompare() {#getCompare--}
```
public CompareFunction getCompare()
```


스텐실 테스트에 사용되는 비교 함수를 가져옵니다.

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


스텐실 테스트는 통과했지만 깊이 테스트가 실패했을 때의 스텐실 동작을 가져옵니다.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


스텐실 테스트가 실패했을 때의 스텐실 동작을 가져옵니다.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


스텐실 테스트와 깊이 테스트가 모두 통과했을 때의 스텐실 동작을 가져옵니다.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

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




### setCompare(CompareFunction value) {#setCompare-com.aspose.threed.CompareFunction-}
```
public void setCompare(CompareFunction value)
```


스텐실 테스트에 사용되는 비교 함수를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | 새 값 |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


스텐실 테스트는 통과했지만 깊이 테스트가 실패했을 때의 스텐실 동작을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | 새 값 |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


스텐실 테스트가 실패했을 때의 스텐실 동작을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | 새 값 |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


스텐실 테스트와 깊이 테스트가 모두 통과했을 때의 스텐실 동작을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | 새 값 |

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

