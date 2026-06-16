---
title: "RenderFactory"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory 创建渲染管线中表示的所有资源。  @hideconstructor


## 方法

### createRenderTexture{#createRenderTexture}

| 名称 | 描述 |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | 创建一个渲染目标，将渲染输出到纹理 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| parameters | RenderParameters | 用于创建渲染纹理的渲染参数 |
| targets | 数字 | 颜色输出目标的数量 |
| 宽度 | 数字 | 渲染纹理的宽度 |
| height | 数字 | 渲染纹理的高度 |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| 名称 | 描述 |
| --- | --- |
| createRenderTexture(parameters, width, height) | 创建一个包含 1 个目标的渲染目标，将渲染输出到纹理 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| parameters | RenderParameters | 用于创建渲染纹理的渲染参数 |
| 宽度 | 数字 | 渲染纹理的宽度 |
| height | 数字 | 渲染纹理的高度 |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| 名称 | 描述 |
| --- | --- |
| createDescriptorSet(shader) | 为指定的着色器程序创建描述符集。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shader | ShaderProgram | 着色器程序 |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| 名称 | 描述 |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | 创建一个包含 1 个立方体纹理的渲染目标 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| parameters | RenderParameters | 用于创建渲染纹理的渲染参数 |
| 宽度 | 数字 | 渲染纹理的宽度 |
| height | 数字 | 渲染纹理的高度 |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| 名称 | 描述 |
| --- | --- |
| createRenderWindow(parameters, handle) | 创建一个渲染目标，将渲染输出到本机窗口。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| parameters | RenderParameters | 用于创建渲染窗口的渲染参数 |
| handle | WindowHandle | 要渲染的窗口句柄 |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| 名称 | 描述 |
| --- | --- |
| createVertexBuffer(declaration) | 创建一个 com.aspose.threed.IVertexBuffer 实例来存储多边形的顶点信息。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 声明 | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| 名称 | 描述 |
| --- | --- |
| createIndexBuffer() | 创建一个 com.aspose.threed.IIndexBuffer 实例来存储多边形的面信息。 |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| 名称 | 描述 |
| --- | --- |
| createTextureUnit(textureType) | 创建一个可被着色器访问的纹理单元。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| 名称 | 描述 |
| --- | --- |
| createTextureUnit() | 创建一个可被着色器访问的 2D 纹理单元。 |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| 名称 | 描述 |
| --- | --- |
| createShaderProgram(shaderSource) | 创建一个 ShaderProgram 对象 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shaderSource | 着色器源 | 着色器的源代码 |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| 名称 | 描述 |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | 创建一个预配置的图形管线，包含预配置的着色器/渲染状态/顶点声明和绘制操作。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shader | ShaderProgram | 渲染中使用的着色器 |
| renderState | RenderState | 渲染中使用的渲染状态 |
| vertexDeclaration | VertexDeclaration | 输入顶点数据的顶点声明 |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| 名称 | 描述 |
| --- | --- |
| createUniformBuffer(size) | 在 GPU 端创建一个具有预分配大小的新统一缓冲区。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| size | 数字 | 统一缓冲区的大小 |

 **Result:**
IBuffer


---



