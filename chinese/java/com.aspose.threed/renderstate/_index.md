---
title: "RenderState"
second_title: "Aspose.3D for Java API 参考"
description: "用于构建管道的渲染状态。对渲染状态所做的更改不会影响已创建的管道实例。"
type: docs
weight: 151
url: /zh/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

用于构建管线的渲染状态，对渲染状态所做的更改不会影响已创建的管线实例。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RenderState()](#RenderState--) | 构造函数 [RenderState](../../com.aspose.threed/renderstate) |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) | 释放 [RenderState](../../com.aspose.threed/renderstate) 并释放所有内部资源。 |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | 将渲染状态与另一个实例进行比较 |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的对象。 |
| [getBlend()](#getBlend--) | 启用或禁用片段混合。 |
| [getBlendColor()](#getBlendColor--) | 获取在 [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) 中使用的混合颜色 |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | 启用或禁用剔除面 |
| [getCullFaceMode()](#getCullFaceMode--) | 获取将被剔除的面。 |
| [getDepthFunction()](#getDepthFunction--) | 获取深度测试中使用的比较函数 |
| [getDepthMask()](#getDepthMask--) | 启用或禁用深度写入。 |
| [getDepthTest()](#getDepthTest--) | 启用或禁用深度测试。 |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | 获取颜色的混合方式。 |
| [getFrontFace()](#getFrontFace--) | 获取正面的顺序。 |
| [getPolygonMode()](#getPolygonMode--) | 获取多边形的渲染模式。 |
| [getScissorTest()](#getScissorTest--) | 启用或禁用剪刀测试 |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | 获取颜色的混合方式。 |
| [getStencilBackFace()](#getStencilBackFace--) | 获取背面模板状态。 |
| [getStencilFrontFace()](#getStencilFrontFace--) | 获取正面模板状态。 |
| [getStencilMask()](#getStencilMask--) | 获取在测试完成时与参考值和存储的模板值进行 AND 运算的掩码。 |
| [getStencilReference()](#getStencilReference--) | 获取模板测试的参考值。 |
| [getStencilTest()](#getStencilTest--) | 启用或禁用模板测试。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | 启用或禁用片段混合。 |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | 设置在 [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) 中使用的混合颜色 |
| [setCullFace(boolean value)](#setCullFace-boolean-) | 启用或禁用剔除面 |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | 设置将被剔除的面。 |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | 设置深度测试中使用的比较函数 |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | 启用或禁用深度写入。 |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | 启用或禁用深度测试。 |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | 设置颜色的混合方式。 |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | 设置正面的顺序。 |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | 设置多边形的渲染模式。 |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | 启用或禁用剪刀测试 |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | 设置颜色的混合方式。 |
| [setStencilMask(int value)](#setStencilMask-int-) | 设置在测试完成时与参考值和存储的模板值进行 AND 运算的掩码。 |
| [setStencilReference(int value)](#setStencilReference-int-) | 设置模板测试的参考值。 |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | 启用或禁用模板测试。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


构造函数 [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


释放 [RenderState](../../com.aspose.threed/renderstate) 并释放所有内部资源。

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


将渲染状态与另一个实例进行比较

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | 另一个用于比较的渲染状态 |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
布尔
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


启用或禁用片段混合。

**Returns:**
boolean - 启用或禁用片段混合。
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


获取在 [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) 中使用的混合颜色

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


启用或禁用剔除面

**Returns:**
boolean - 启用或禁用剔除面
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


获取将被剔除的面。

**Returns:**
int - 将被剔除的面。
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


获取深度测试中使用的比较函数

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


启用或禁用深度写入。

**Returns:**
boolean - 启用或禁用深度写入。
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


启用或禁用深度测试。

**Returns:**
boolean - 启用或禁用深度测试。
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


获取颜色的混合方式。

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


获取正面的顺序。

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


获取多边形的渲染模式。

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


启用或禁用剪刀测试

**Returns:**
boolean - 启用或禁用剪裁测试
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


获取颜色的混合方式。

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


获取背面模板状态。

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


获取正面模板状态。

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


获取在测试完成时与参考值和存储的模板值进行 AND 运算的掩码。

**Returns:**
int - 在测试完成时与参考值和存储的模板值进行 AND 运算的掩码。
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


获取模板测试的参考值。

**Returns:**
int - 模板测试的参考值。
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


启用或禁用模板测试。

**Returns:**
boolean - 启用或禁用模板测试。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

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


启用或禁用片段混合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


设置在 [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) 中使用的混合颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | 新值 |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


启用或禁用剔除面

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


设置将被剔除的面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


设置深度测试中使用的比较函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | 新值 |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


启用或禁用深度写入。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


启用或禁用深度测试。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


设置颜色的混合方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | 新值 |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


设置正面的顺序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | 新值 |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


设置多边形的渲染模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | 新值 |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


启用或禁用剪刀测试

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


设置颜色的混合方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | 新值 |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


设置在测试完成时与参考值和存储的模板值进行 AND 运算的掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


设置模板测试的参考值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


启用或禁用模板测试。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

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

