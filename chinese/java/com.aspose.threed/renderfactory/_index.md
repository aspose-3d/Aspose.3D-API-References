---
title: "RenderFactory"
second_title: "Aspose.3D for Java API 参考"
description: "RenderFactory 创建渲染管线中表示的所有资源。"
type: docs
weight: 148
url: /zh/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

RenderFactory 创建渲染管线中表示的所有资源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | 创建一个包含 1 个立方体纹理的渲染目标 |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | 为指定的着色器程序创建描述符集合。 |
| [createIndexBuffer()](#createIndexBuffer--) | 创建一个 [IIndexBuffer](../../com.aspose.threed/iindexbuffer) 实例以存储多边形的面信息。 |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | 创建一个预配置的图形管线，包含预配置的着色器/渲染状态/顶点声明和绘制操作。 |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | 创建一个渲染目标，包含 1 个渲染到纹理的目标 |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | 创建一个渲染到纹理的渲染目标。 |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | 创建一个渲染到本机窗口的渲染目标。 |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | 创建一个 [ShaderProgram](../../com.aspose.threed/shaderprogram) 对象 |
| [createTextureUnit()](#createTextureUnit--) | 创建一个可被着色器访问的 2D 纹理单元。 |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | 创建一个可被着色器访问的纹理单元。 |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | 在 GPU 端创建一个具有预分配大小的新统一缓冲区。 |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | 创建一个 [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) 实例以存储多边形的顶点信息。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderFactory() {#RenderFactory--}
```
public RenderFactory()
```


### createCubeRenderTexture(RenderParameters parameters, int width, int height) {#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createCubeRenderTexture(RenderParameters parameters, int width, int height)
```


创建一个包含 1 个立方体纹理的渲染目标

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | 用于创建渲染纹理的渲染参数 |
| 宽度 | int | 渲染纹理的宽度 |
| 高度 | int | 渲染纹理的高度 |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


为指定的着色器程序创建描述符集合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 着色器程序 |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


创建一个 [IIndexBuffer](../../com.aspose.threed/iindexbuffer) 实例以存储多边形的面信息。

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


创建一个预配置的图形管线，包含预配置的着色器/渲染状态/顶点声明和绘制操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 渲染中使用的着色器 |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | 渲染中使用的渲染状态 |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | 输入顶点数据的顶点声明 |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | 绘制操作 |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


创建一个渲染目标，包含 1 个渲染到纹理的目标

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | 用于创建渲染纹理的渲染参数 |
| 宽度 | int | 渲染纹理的宽度 |
| 高度 | int | 渲染纹理的高度 |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


创建一个渲染到纹理的渲染目标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | 用于创建渲染纹理的渲染参数 |
| 目标 | int | 颜色输出目标的数量 |
| 宽度 | int | 渲染纹理的宽度 |
| 高度 | int | 渲染纹理的高度 |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


创建一个渲染到本机窗口的渲染目标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | 用于创建渲染窗口的渲染参数 |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | 要渲染的窗口句柄 |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


创建一个 [ShaderProgram](../../com.aspose.threed/shaderprogram) 对象

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | 着色器的源代码 |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


创建一个可被着色器访问的 2D 纹理单元。

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


创建一个可被着色器访问的纹理单元。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | 纹理类型 |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


在 GPU 端创建一个具有预分配大小的新统一缓冲区。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 大小 | int | 统一缓冲区的大小 |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


创建一个 [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) 实例以存储多边形的顶点信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
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

