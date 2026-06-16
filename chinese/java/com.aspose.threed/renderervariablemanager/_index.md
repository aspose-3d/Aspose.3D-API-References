---
title: "RendererVariableManager"
second_title: "Aspose.3D for Java API 参考"
description: "此类管理渲染中使用的变量"
type: docs
weight: 154
url: /zh/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

此类管理渲染中使用的变量
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | 相机在世界坐标系中的位置 |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | 阴影映射的深度偏差，默认值为 0.001 |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | 光空间变换矩阵 |
| [getMatrixProjection()](#getMatrixProjection--) | 投影变换矩阵 |
| [getMatrixView()](#getMatrixView--) | 视图变换矩阵 |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | 视图和投影变换矩阵。 |
| [getMatrixWorld()](#getMatrixWorld--) | 世界变换矩阵 |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | 用于将法线从对象空间转换到世界空间的矩阵。 |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | 用于世界视图和投影变换的矩阵 |
| [getShadowCaster()](#getShadowCaster--) | 阴影投射体在世界坐标系中的位置 |
| [getShadowmap()](#getShadowmap--) | 用于阴影映射的深度纹理 |
| [getViewportSize()](#getViewportSize--) | 视口的大小，以像素为单位 |
| [getWorldAmbient()](#getWorldAmbient--) | 视口中定义的环境光颜色。 |
| [getWorldTime()](#getWorldTime--) | 时间（秒） |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | 相机在世界坐标系中的位置 |
| [setDepthBias(float value)](#setDepthBias-float-) | 阴影映射的深度偏差，默认值为 0.001 |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | 光空间变换矩阵 |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | 投影变换矩阵 |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | 视图变换矩阵 |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | 阴影投射体在世界坐标系中的位置 |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | 用于阴影映射的深度纹理 |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | 视口的大小，以像素为单位 |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | 视口中定义的环境光颜色。 |
| [setWorldTime(float value)](#setWorldTime-float-) | 时间（秒） |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


相机在世界坐标系中的位置

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


阴影映射的深度偏差，默认值为 0.001

**Returns:**
float - 阴影映射的深度偏差，默认值为 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


光空间变换矩阵

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


投影变换矩阵

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


视图变换矩阵

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


视图和投影变换矩阵。

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


世界变换矩阵

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


用于将法线从对象空间转换到世界空间的矩阵。

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


用于世界视图和投影变换的矩阵

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


阴影投射体在世界坐标系中的位置

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


用于阴影映射的深度纹理

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


视口的大小，以像素为单位

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


视口中定义的环境光颜色。

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


时间（秒）

**Returns:**
float - 时间（秒）
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


相机在世界坐标系中的位置

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | 新值 |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


阴影映射的深度偏差，默认值为 0.001

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


光空间变换矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | 新值 |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


投影变换矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | 新值 |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


视图变换矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | 新值 |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


阴影投射体在世界坐标系中的位置

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | 新值 |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


用于阴影映射的深度纹理

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | 新值 |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


视口的大小，以像素为单位

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | 新值 |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


视口中定义的环境光颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | 新值 |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


时间（秒）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

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

