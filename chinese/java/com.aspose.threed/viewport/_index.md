---
title: "Viewport"
second_title: "Aspose.3D for Java API 参考"
description: "一个  包含至少一个用于渲染场景的视口。"
type: docs
weight: 229
url: /zh/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

一个 [IRenderTarget](../../com.aspose.threed/irendertarget) 包含至少一个用于渲染场景的视口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | 获取渲染目标中视口的面积。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取视口的背景颜色。 |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | 获取在深度缓冲位设置时清除视口使用的深度值。 |
| [getEnabled()](#getEnabled--) | 启用或禁用此视口。 |
| [getFrustum()](#getFrustum--) | 获取此 [Viewport](../../com.aspose.threed/viewport) 的相机。 |
| [getRenderTarget()](#getRenderTarget--) | 获取创建此视口的渲染目标。 |
| [getZOrder()](#getZOrder--) | 获取视口的 Z-order。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | 设置渲染目标中视口的区域。 |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | 设置视口的背景颜色。 |
| [setDepthClear(float value)](#setDepthClear-float-) | 设置在深度缓冲位被设置时清除视口所使用的深度值。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 启用或禁用此视口。 |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | 设置此 [Viewport](../../com.aspose.threed/viewport) 的相机。 |
| [setZOrder(int value)](#setZOrder-int-) | 设置视口的 Z-order。 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


获取渲染目标中视口的面积。

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


获取视口的背景颜色。

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


获取在深度缓冲位设置时清除视口使用的深度值。

**Returns:**
float - 在深度缓冲位被设置时清除视口所使用的深度值。
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


启用或禁用此视口。

**Returns:**
boolean - 启用或禁用此视口。
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


获取此 [Viewport](../../com.aspose.threed/viewport) 的相机。

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


获取创建此视口的渲染目标。

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


获取视口的 Z-order。

**Returns:**
int - 视口的 Z-order。
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


设置渲染目标中视口的区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | 新值 |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


设置视口的背景颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


设置在深度缓冲位被设置时清除视口所使用的深度值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


启用或禁用此视口。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


设置此 [Viewport](../../com.aspose.threed/viewport) 的相机。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | 新值 |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


设置视口的 Z-order。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

