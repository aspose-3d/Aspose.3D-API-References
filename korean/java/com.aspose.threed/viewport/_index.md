---
title: Viewport
second_title: Aspose.3D for Java API 레퍼런스
description: A  최소 하나의 뷰포트를 포함하여 장면을 렌더링합니다.
type: docs
weight: 229
url: /ko/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

A [IRenderTarget](../../com.aspose.threed/irendertarget) 은(는) 장면을 렌더링하기 위해 최소 하나의 뷰포트를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | 렌더 타깃에서 뷰포트의 영역을 가져옵니다. |
| [getBackgroundColor()](#getBackgroundColor--) | 뷰포트의 배경 색상을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | 깊이 버퍼 비트가 설정된 상태에서 뷰포트를 클리어할 때 사용되는 깊이 값을 가져옵니다. |
| [getEnabled()](#getEnabled--) | 이 뷰포트를 활성화하거나 비활성화합니다. |
| [getFrustum()](#getFrustum--) | 이 [Viewport](../../com.aspose.threed/viewport)의 카메라를 가져옵니다. |
| [getRenderTarget()](#getRenderTarget--) | 이 뷰포트를 만든 렌더 타깃을 가져옵니다. |
| [getZOrder()](#getZOrder--) | 뷰포트의 Z-순서를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | 렌더 타깃에서 뷰포트의 영역을 설정합니다. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | 뷰포트의 배경 색을 설정합니다. |
| [setDepthClear(float value)](#setDepthClear-float-) | 깊이 버퍼 비트가 설정된 상태에서 뷰포트를 클리어할 때 사용되는 깊이 값을 설정합니다. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 이 뷰포트를 활성화하거나 비활성화합니다. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | 이 [Viewport](../../com.aspose.threed/viewport)의 카메라를 설정합니다. |
| [setZOrder(int value)](#setZOrder-int-) | 뷰포트의 Z-순서를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clone() {#clone--}
```
public Viewport clone()
```




**Returns:**
[Viewport](../../com.aspose.threed/viewport)
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
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


렌더 타깃에서 뷰포트의 영역을 가져옵니다.

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


뷰포트의 배경 색상을 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the background color of the viewport.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepthClear() {#getDepthClear--}
```
public float getDepthClear()
```


깊이 버퍼 비트가 설정된 상태에서 뷰포트를 클리어할 때 사용되는 깊이 값을 가져옵니다.

**Returns:**
float - 깊이 버퍼 비트가 설정된 상태에서 뷰포트를 클리어할 때 사용되는 깊이 값.
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


이 뷰포트를 활성화하거나 비활성화합니다.

**Returns:**
boolean - 이 뷰포트를 활성화하거나 비활성화합니다.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


이 [Viewport](../../com.aspose.threed/viewport)의 카메라를 가져옵니다.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


이 뷰포트를 만든 렌더 타깃을 가져옵니다.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


뷰포트의 Z-순서를 가져옵니다.

**Returns:**
int - 뷰포트의 Z-순서.
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




### setArea(RelativeRectangle value) {#setArea-com.aspose.threed.RelativeRectangle-}
```
public void setArea(RelativeRectangle value)
```


렌더 타깃에서 뷰포트의 영역을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | 새 값 |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


뷰포트의 배경 색을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


깊이 버퍼 비트가 설정된 상태에서 뷰포트를 클리어할 때 사용되는 깊이 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


이 뷰포트를 활성화하거나 비활성화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


이 [Viewport](../../com.aspose.threed/viewport)의 카메라를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | 새 값 |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


뷰포트의 Z-순서를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

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

