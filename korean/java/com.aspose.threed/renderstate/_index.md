---
title: "RenderState"
second_title: "Aspose.3D for Java API 레퍼런스"
description: "파이프라인 구축을 위한 렌더 상태  렌더 상태에 대한 변경은 생성된 파이프라인 인스턴스에 영향을 주지 않습니다."
type: docs
weight: 151
url: /ko/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

파이프라인 구축을 위한 렌더 상태. 렌더 상태에 대한 변경은 생성된 파이프라인 인스턴스에 영향을 주지 않습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RenderState()](#RenderState--) | 생성자 [RenderState](../../com.aspose.threed/renderstate) |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [close()](#close--) | [RenderState](../../com.aspose.threed/renderstate)를 해제하고 모든 내부 리소스를 해제합니다. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | 다른 인스턴스와 렌더 상태를 비교합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 객체와 같은지 여부를 나타내는 값을 반환합니다. |
| [getBlend()](#getBlend--) | 프래그먼트 블렌딩을 활성화하거나 비활성화합니다. |
| [getBlendColor()](#getBlendColor--) | [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)에서 사용되는 블렌드 색상을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | 컬 페이스를 활성화하거나 비활성화합니다. |
| [getCullFaceMode()](#getCullFaceMode--) | 컬링될 면을 가져옵니다. |
| [getDepthFunction()](#getDepthFunction--) | 깊이 테스트에서 사용되는 비교 함수를 가져옵니다. |
| [getDepthMask()](#getDepthMask--) | 깊이 쓰기를 활성화하거나 비활성화합니다. |
| [getDepthTest()](#getDepthTest--) | 깊이 테스트를 활성화하거나 비활성화합니다. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | 색상이 어떻게 블렌드되는지 가져옵니다. |
| [getFrontFace()](#getFrontFace--) | 앞면이 되는 순서를 가져옵니다. |
| [getPolygonMode()](#getPolygonMode--) | 폴리곤의 렌더 모드를 가져옵니다. |
| [getScissorTest()](#getScissorTest--) | 시저 테스트를 활성화하거나 비활성화합니다. |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | 색상이 어떻게 블렌드되는지 가져옵니다. |
| [getStencilBackFace()](#getStencilBackFace--) | 뒷면에 대한 스텐실 상태를 가져옵니다. |
| [getStencilFrontFace()](#getStencilFrontFace--) | 앞면에 대한 스텐실 상태를 가져옵니다. |
| [getStencilMask()](#getStencilMask--) | 테스트가 완료될 때 참조값과 저장된 스텐실 값 모두와 AND 연산되는 마스크를 가져옵니다. |
| [getStencilReference()](#getStencilReference--) | 스텐실 테스트에 대한 참조 값을 가져옵니다. |
| [getStencilTest()](#getStencilTest--) | 스텐실 테스트를 활성화하거나 비활성화합니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | 프래그먼트 블렌딩을 활성화하거나 비활성화합니다. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)에서 사용되는 블렌드 색상을 설정합니다. |
| [setCullFace(boolean value)](#setCullFace-boolean-) | 컬 페이스를 활성화하거나 비활성화합니다. |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | 컬링될 면을 설정합니다. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | 깊이 테스트에서 사용되는 비교 함수를 설정합니다. |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | 깊이 쓰기를 활성화하거나 비활성화합니다. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | 깊이 테스트를 활성화하거나 비활성화합니다. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | 색상이 어떻게 블렌드되는지 설정합니다. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | 앞면이 되는 순서를 설정합니다. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | 다각형의 렌더 모드를 설정합니다. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | 시저 테스트를 활성화하거나 비활성화합니다. |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | 색상이 어떻게 블렌드되는지 설정합니다. |
| [setStencilMask(int value)](#setStencilMask-int-) | 테스트가 완료될 때 기준값과 저장된 스텐실 값 모두와 AND 연산되는 마스크를 설정합니다. |
| [setStencilReference(int value)](#setStencilReference-int-) | 스텐실 테스트의 기준값을 설정합니다. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | 스텐실 테스트를 활성화하거나 비활성화합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


생성자 [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


[RenderState](../../com.aspose.threed/renderstate)를 해제하고 모든 내부 리소스를 해제합니다.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


다른 인스턴스와 렌더 상태를 비교합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | 비교할 다른 렌더 상태 |

**Returns:**
int
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
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


프래그먼트 블렌딩을 활성화하거나 비활성화합니다.

**Returns:**
boolean - 프래그먼트 블렌딩을 활성화하거나 비활성화합니다.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


[BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)에서 사용되는 블렌드 색상을 가져옵니다.

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCullFace() {#getCullFace--}
```
public boolean getCullFace()
```


컬 페이스를 활성화하거나 비활성화합니다.

**Returns:**
boolean - 컬 페이스를 활성화하거나 비활성화합니다.
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


컬링될 면을 가져옵니다.

**Returns:**
int - 컬링될 면을 지정합니다.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


깊이 테스트에서 사용되는 비교 함수를 가져옵니다.

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


깊이 쓰기를 활성화하거나 비활성화합니다.

**Returns:**
boolean - 깊이 쓰기를 활성화하거나 비활성화합니다.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


깊이 테스트를 활성화하거나 비활성화합니다.

**Returns:**
boolean - 깊이 테스트를 활성화하거나 비활성화합니다.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


색상이 어떻게 블렌드되는지 가져옵니다.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


앞면이 되는 순서를 가져옵니다.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


폴리곤의 렌더 모드를 가져옵니다.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


시저 테스트를 활성화하거나 비활성화합니다.

**Returns:**
boolean - 가위 테스트를 활성화하거나 비활성화합니다.
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


색상이 어떻게 블렌드되는지 가져옵니다.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


뒷면에 대한 스텐실 상태를 가져옵니다.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


앞면에 대한 스텐실 상태를 가져옵니다.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


테스트가 완료될 때 참조값과 저장된 스텐실 값 모두와 AND 연산되는 마스크를 가져옵니다.

**Returns:**
int - 테스트가 완료될 때 기준값과 저장된 스텐실 값 모두와 AND 연산되는 마스크입니다.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


스텐실 테스트에 대한 참조 값을 가져옵니다.

**Returns:**
int - 스텐실 테스트의 기준값입니다.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


스텐실 테스트를 활성화하거나 비활성화합니다.

**Returns:**
boolean - 스텐실 테스트를 활성화하거나 비활성화합니다.
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




### setBlend(boolean value) {#setBlend-boolean-}
```
public void setBlend(boolean value)
```


프래그먼트 블렌딩을 활성화하거나 비활성화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


[BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)에서 사용되는 블렌드 색상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | 새 값 |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


컬 페이스를 활성화하거나 비활성화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


컬링될 면을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


깊이 테스트에서 사용되는 비교 함수를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | 새 값 |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


깊이 쓰기를 활성화하거나 비활성화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


깊이 테스트를 활성화하거나 비활성화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


색상이 어떻게 블렌드되는지 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | 새 값 |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


앞면이 되는 순서를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | 새 값 |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


다각형의 렌더 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | 새 값 |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


시저 테스트를 활성화하거나 비활성화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


색상이 어떻게 블렌드되는지 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | 새 값 |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


테스트가 완료될 때 기준값과 저장된 스텐실 값 모두와 AND 연산되는 마스크를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


스텐실 테스트의 기준값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


스텐실 테스트를 활성화하거나 비활성화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

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

