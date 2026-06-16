---
title: "Aspose.ThreeD.Render"
second_title: "Aspose.3D for .NET API 参考"
description: "所有渲染相关的类都定义在此命名空间中"
type: docs
weight: 80
url: /zh/net/aspose.threed.render/
---
所有渲染相关的类都定义在此命名空间中

## 类

| 类 | 描述 |
| --- | --- |
| [DescriptorSetUpdater](./descriptorsetupdater/) | 此类允许在链式操作中更新 [`IDescriptorSet`](../aspose.threed.render/idescriptorset/)。 |
| [DriverException](./driverexception/) | 内部渲染驱动程序引发的异常。 |
| [EntityRenderer](./entityrenderer/) | 子类化此类以实现对不同种类实体的渲染。 |
| [EntityRendererKey](./entityrendererkey/) | 已注册实体渲染器的键 |
| [GLSLSource](./glslsource/) | GLSL 中着色器的源代码 |
| [InitializationException](./initializationexception/) | 渲染管线初始化中的异常 |
| [PixelMapping](./pixelmapping/) |  |
| [PostProcessing](./postprocessing/) | 后处理效果 |
| [PushConstant](./pushconstant/) | 通过推送常量向着色器提供数据的实用工具。 |
| [Renderer](./renderer/) | 关于渲染器的上下文。 |
| [RendererVariableManager](./renderervariablemanager/) | 此类管理渲染中使用的变量 |
| [RenderFactory](./renderfactory/) | RenderFactory 创建渲染管线中表示的所有资源。 |
| [RenderParameters](./renderparameters/) | 描述渲染目标的参数 |
| [RenderResource](./renderresource/) | 所有渲染资源的抽象类。所有渲染资源将在渲染器释放时被处置。类似 [`Mesh`](../aspose.threed.entities/mesh/)/[`Texture`](../aspose.threed.shading/texture/) 的类将拥有相应的 RenderResource。 |
| [RenderState](./renderstate/) | 用于构建管线的渲染状态。对渲染状态所做的更改不会影响已创建的管线实例。 |
| [ShaderException](./shaderexception/) | 着色器相关异常 |
| [ShaderProgram](./shaderprogram/) | 着色器程序 |
| [ShaderSet](./shaderset/) | 每种材料的着色器程序 |
| [ShaderSource](./shadersource/) | 着色器的源代码 |
| [ShaderVariable](./shadervariable/) | 着色器变量 |
| [SPIRVSource](./spirvsource/) | SPIR-V 格式的已编译着色器。 |
| [StencilState](./stencilstate/) | 每个面的模板状态。 |
| [TextureCodec](./texturecodec/) | 用于管理纹理的编码器和解码器的类。 |
| [TextureData](./texturedata/) | 此类包含纹理的原始数据和格式定义。 |
| [Viewport](./viewport/) | [`IRenderTarget`](../aspose.threed.render/irendertarget/) 包含至少一个用于渲染场景的视口。 |
| [WindowHandle](./windowhandle/) | 针对不同平台的封装窗口句柄。 |
## Structures

| 结构 | 描述 |
| --- | --- |
| [CubeFaceData&lt;T&gt;](./cubefacedata-1/) | 立方体贴图纹理每个面的数据。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IBuffer](./ibuffer/) | 用于渲染的所有受管理缓冲区的基础接口 |
| [ICommandList](./icommandlist/) | 对将发送到 GPU 进行渲染的命令序列进行编码。 |
| [IDescriptorSet](./idescriptorset/) | 描述符集合描述了可用于绑定到渲染管线的不同资源，如缓冲区、纹理。 |
| [IIndexBuffer](./iindexbuffer/) | 索引缓冲区描述了渲染管线中使用的几何体。 |
| [IPipeline](./ipipeline/) | 在 GPU 端绘制的预先烘焙操作序列。 |
| [IRenderQueue](./irenderqueue/) | 实体渲染器使用此队列来管理渲染任务。 |
| [IRenderTarget](./irendertarget/) | 渲染目标的基础接口 |
| [IRenderTexture](./irendertexture/) | 渲染纹理的接口 |
| [IRenderWindow](./irenderwindow/) | IRenderWindow 表示操作系统创建的支持渲染的本机窗口。 |
| [ITexture1D](./itexture1d/) | 1D 纹理 |
| [ITexture2D](./itexture2d/) | 2D 纹理 |
| [ITextureCodec](./itexturecodec/) | 纹理编解码器 |
| [ITextureCubemap](./itexturecubemap/) | 立方体贴图纹理 |
| [ITextureDecoder](./itexturedecoder/) | 外部纹理解码器应实现此接口以进行解码。 |
| [ITextureEncoder](./itextureencoder/) | 外部纹理编码器应实现此接口以进行编码。 |
| [ITextureUnit](./itextureunit/) | [`ITextureUnit`](../aspose.threed.render/itextureunit/) 表示内存中的一种纹理，该纹理在 GPU 和 CPU 之间共享，并且可以被着色器采样，而 [`Texture`](../aspose.threed.shading/texture/) 仅表示对外部文件的引用。更多细节可查阅 https://en.wikipedia.org/wiki/Texture_mapping_unit |
| [IVertexBuffer](./ivertexbuffer/) | 顶点缓冲区保存将发送到渲染管线的多边形顶点数据。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [BlendFactor](./blendfactor/) | 混合因子指定像素算术运算。 |
| [CompareFunction](./comparefunction/) | 深度/模板测试中使用的比较函数。 |
| [CubeFace](./cubeface/) | 立方体贴图纹理的每个面 |
| [CullFaceMode](./cullfacemode/) | 要剔除的面 |
| [DrawOperation](./drawoperation/) | 要渲染的图元类型 |
| [EntityRendererFeatures](./entityrendererfeatures/) | 实体渲染器将提供的额外功能 |
| [FrontFace](./frontface/) | 定义正面和背面多边形 |
| [IndexDataType](./indexdatatype/) | [`IIndexBuffer`](../aspose.threed.render/iindexbuffer/) 中元素的数据类型 |
| [PixelFormat](./pixelformat/) | 纹理单元中使用的像素格式。 |
| [PixelMapMode](./pixelmapmode/) |  |
| [PolygonMode](./polygonmode/) | 多边形光栅化模式 |
| [PresetShaders](./presetshaders/) | 这定义了渲染器使用的预设内部着色器。 |
| [RenderQueueGroupId](./renderqueuegroupid/) | 渲染队列的组 ID |
| [RenderStage](./renderstage/) | 渲染阶段 |
| [ShaderStage](./shaderstage/) | 着色器阶段 |
| [StencilAction](./stencilaction/) | 模板测试操作 |
| [TextureType](./texturetype/) | [`ITextureUnit`](../aspose.threed.render/itextureunit/) 的类型 |


