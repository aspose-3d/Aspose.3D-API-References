---
title: RenderState
second_title: Aspose.3D for Java API 레퍼런스
description: 파이프라인 구축을 위한 렌더 상태  렌더 상태에 대한 변경은 생성된 파이프라인 인스턴스에 영향을 주지 않습니다.
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
| [RenderState()](#RenderState--) | Constructor of [RenderState](../../com.aspose.threed/renderstate) |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [close()](#close--) | Dispose the [RenderState](../../com.aspose.threed/renderstate) and release all internal resources. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Compare the render state with another instance |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 객체와 같은지 여부를 나타내는 값을 반환합니다. |
| [getBlend()](#getBlend--) | Enable or disable the fragment blending. |
| [getBlendColor()](#getBlendColor--) | Gets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Enable or disable cull face |
| [getCullFaceMode()](#getCullFaceMode--) | Gets which face will be culled. |
| [getDepthFunction()](#getDepthFunction--) | Gets the compare function used in depth test |
| [getDepthMask()](#getDepthMask--) | Enable or disable the depth writing. |
| [getDepthTest()](#getDepthTest--) | Enable or disable the depth test. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Gets how the color is blended. |
| [getFrontFace()](#getFrontFace--) | Gets which order is front face. |
| [getPolygonMode()](#getPolygonMode--) | Gets the polygon's render mode. |
| [getScissorTest()](#getScissorTest--) | Enable or disable scissor test |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Gets how the color is blended. |
| [getStencilBackFace()](#getStencilBackFace--) | Gets the stencil state for back face. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Gets the stencil state for front face. |
| [getStencilMask()](#getStencilMask--) | Gets the mask that is ANDed with the both reference and stored stencil value when test is done. |
| [getStencilReference()](#getStencilReference--) | Gets the reference value for the stencil test. |
| [getStencilTest()](#getStencilTest--) | Enable or disable the stencil test. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Enable or disable the fragment blending. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Sets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Enable or disable cull face |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Sets which face will be culled. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Sets the compare function used in depth test |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Enable or disable the depth writing. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Enable or disable the depth test. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Sets how the color is blended. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Sets which order is front face. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | 다각형의 렌더 모드를 설정합니다. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Enable or disable scissor test |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Sets how the color is blended. |
| [setStencilMask(int value)](#setStencilMask-int-) | 테스트가 완료될 때 기준값과 저장된 스텐실 값 모두와 AND 연산되는 마스크를 설정합니다. |
| [setStencilReference(int value)](#setStencilReference-int-) | 스텐실 테스트의 기준값을 설정합니다. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Enable or disable the stencil test. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


Constructor of [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


Dispose the [RenderState](../../com.aspose.threed/renderstate) and release all internal resources.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Compare the render state with another instance

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


Enable or disable the fragment blending.

**Returns:**
boolean - 프래그먼트 블렌딩을 활성화하거나 비활성화합니다.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Gets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

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


Enable or disable cull face

**Returns:**
boolean - 컬 페이스를 활성화하거나 비활성화합니다.
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Gets which face will be culled.

**Returns:**
int - 컬링될 면을 지정합니다.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Gets the compare function used in depth test

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Enable or disable the depth writing.

**Returns:**
boolean - 깊이 쓰기를 활성화하거나 비활성화합니다.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Enable or disable the depth test.

**Returns:**
boolean - 깊이 테스트를 활성화하거나 비활성화합니다.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Gets how the color is blended.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Gets which order is front face.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Gets the polygon's render mode.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Enable or disable scissor test

**Returns:**
boolean - 가위 테스트를 활성화하거나 비활성화합니다.
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Gets how the color is blended.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Gets the stencil state for back face.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Gets the stencil state for front face.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Gets the mask that is ANDed with the both reference and stored stencil value when test is done.

**Returns:**
int - 테스트가 완료될 때 기준값과 저장된 스텐실 값 모두와 AND 연산되는 마스크입니다.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Gets the reference value for the stencil test.

**Returns:**
int - 스텐실 테스트의 기준값입니다.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Enable or disable the stencil test.

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


Enable or disable the fragment blending.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Sets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | 새 값 |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Enable or disable cull face

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Sets which face will be culled.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Sets the compare function used in depth test

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | 새 값 |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Enable or disable the depth writing.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Enable or disable the depth test.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Sets how the color is blended.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | 새 값 |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Sets which order is front face.

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


Enable or disable scissor test

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Sets how the color is blended.

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


Enable or disable the stencil test.

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

