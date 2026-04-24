---
title: RendererVariableManager
second_title: Aspose.3D for Java API 레퍼런스
description: 이 클래스는 렌더링에 사용되는 변수를 관리합니다.
type: docs
weight: 154
url: /ko/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

이 클래스는 렌더링에 사용되는 변수를 관리합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | 월드 좌표계에서 카메라 위치 |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | 그림자 매핑을 위한 깊이 바이어스, 기본값은 0.001입니다. |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | 광원 공간 변환을 위한 행렬 |
| [getMatrixProjection()](#getMatrixProjection--) | 투영 변환을 위한 행렬 |
| [getMatrixView()](#getMatrixView--) | 뷰 변환을 위한 행렬 |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | 뷰 및 투영 변환을 위한 행렬. |
| [getMatrixWorld()](#getMatrixWorld--) | 월드 변환을 위한 행렬 |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | 노멀을 객체 공간에서 월드 공간으로 변환하기 위한 행렬. |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | 월드 뷰 및 투영 변환을 위한 행렬 |
| [getShadowCaster()](#getShadowCaster--) | 월드 좌표계에서 그림자 투사체의 위치 |
| [getShadowmap()](#getShadowmap--) | 그림자 매핑에 사용되는 깊이 텍스처 |
| [getViewportSize()](#getViewportSize--) | 픽셀 단위로 측정된 뷰포트 크기 |
| [getWorldAmbient()](#getWorldAmbient--) | 뷰포트에 정의된 앰비언트 색상. |
| [getWorldTime()](#getWorldTime--) | 시간(초) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | 월드 좌표계에서 카메라 위치 |
| [setDepthBias(float value)](#setDepthBias-float-) | 그림자 매핑을 위한 깊이 바이어스, 기본값은 0.001입니다. |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | 광원 공간 변환을 위한 행렬 |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | 투영 변환을 위한 행렬 |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | 뷰 변환을 위한 행렬 |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | 월드 좌표계에서 그림자 투사체의 위치 |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | 그림자 매핑에 사용되는 깊이 텍스처 |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | 픽셀 단위로 측정된 뷰포트 크기 |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | 뷰포트에 정의된 앰비언트 색상. |
| [setWorldTime(float value)](#setWorldTime-float-) | 시간(초) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


월드 좌표계에서 카메라 위치

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Camera's position in world coordinate system
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepthBias() {#getDepthBias--}
```
public float getDepthBias()
```


그림자 매핑을 위한 깊이 바이어스, 기본값은 0.001입니다.

**Returns:**
float - 그림자 매핑을 위한 깊이 바이어스, 기본값은 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


광원 공간 변환을 위한 행렬

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


투영 변환을 위한 행렬

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


뷰 변환을 위한 행렬

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


뷰 및 투영 변환을 위한 행렬.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


월드 변환을 위한 행렬

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


노멀을 객체 공간에서 월드 공간으로 변환하기 위한 행렬.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


월드 뷰 및 투영 변환을 위한 행렬

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


월드 좌표계에서 그림자 투사체의 위치

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


그림자 매핑에 사용되는 깊이 텍스처

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


픽셀 단위로 측정된 뷰포트 크기

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


뷰포트에 정의된 앰비언트 색상.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


시간(초)

**Returns:**
float - 시간(초)
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




### setCameraPosition(FVector3 value) {#setCameraPosition-com.aspose.threed.FVector3-}
```
public void setCameraPosition(FVector3 value)
```


월드 좌표계에서 카메라 위치

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | 새 값 |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


그림자 매핑을 위한 깊이 바이어스, 기본값은 0.001입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


광원 공간 변환을 위한 행렬

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | 새 값 |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


투영 변환을 위한 행렬

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | 새 값 |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


뷰 변환을 위한 행렬

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | 새 값 |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


월드 좌표계에서 그림자 투사체의 위치

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | 새 값 |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


그림자 매핑에 사용되는 깊이 텍스처

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | 새 값 |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


픽셀 단위로 측정된 뷰포트 크기

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | 새 값 |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


뷰포트에 정의된 앰비언트 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | 새 값 |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


시간(초)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

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

