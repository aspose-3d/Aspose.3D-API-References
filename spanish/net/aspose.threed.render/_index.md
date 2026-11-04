---
title: "Aspose.ThreeD.Render"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Todas las clases relacionadas con el renderizado se definen en este espacio de nombres"
type: docs
weight: 80
url: /es/net/aspose.threed.render/
---
Todas las clases relacionadas con el renderizado se definen en este espacio de nombres

## Clases

| Clase | Descripción |
| --- | --- |
| [DescriptorSetUpdater](./descriptorsetupdater/) | Esta clase permite actualizar el [`IDescriptorSet`](../aspose.threed.render/idescriptorset/) en una operación en cadena. |
| [DriverException](./driverexception/) | La excepción generada por los controladores internos de renderizado. |
| [EntityRenderer](./entityrenderer/) | Cree una subclase de esta para implementar el renderizado de diferentes tipos de entidades. |
| [EntityRendererKey](./entityrendererkey/) | La clave del renderizador de entidad registrado |
| [GLSLSource](./glslsource/) | El código fuente de los shaders en GLSL |
| [InitializationException](./initializationexception/) | Excepciones en la inicialización del pipeline de renderizado |
| [PixelMapping](./pixelmapping/) |  |
| [PostProcessing](./postprocessing/) | Los efectos de postprocesamiento |
| [PushConstant](./pushconstant/) | Una utilidad para proporcionar datos al shader mediante una constante push. |
| [Renderer](./renderer/) | El contexto sobre el renderizador. |
| [RendererVariableManager](./renderervariablemanager/) | Esta clase gestiona variables usadas en el renderizado |
| [RenderFactory](./renderfactory/) | RenderFactory crea todos los recursos que se representan en el pipeline de renderizado. |
| [RenderParameters](./renderparameters/) | Describe los parámetros del objetivo de renderizado |
| [RenderResource](./renderresource/) | La clase abstracta de todos los recursos de renderizado. Todos los recursos de renderizado se liberarán cuando se libere el renderizador. Clases como [`Mesh`](../aspose.threed.entities/mesh/)/[`Texture`](../aspose.threed.shading/texture/) tendrán un RenderResource correspondiente. |
| [RenderState](./renderstate/) | Estado de renderizado para construir el pipeline. Los cambios realizados en el estado de renderizado no afectarán a las instancias del pipeline creadas. |
| [ShaderException](./shaderexception/) | Excepciones relacionadas con shaders |
| [ShaderProgram](./shaderprogram/) | El programa de shader |
| [ShaderSet](./shaderset/) | Programas de shader para cada tipo de material |
| [ShaderSource](./shadersource/) | El código fuente del shader |
| [ShaderVariable](./shadervariable/) | Variable de shader |
| [SPIRVSource](./spirvsource/) | El shader compilado en formato SPIR-V. |
| [StencilState](./stencilstate/) | Estados de stencil por cara. |
| [TextureCodec](./texturecodec/) | Clase para gestionar codificadores y decodificadores de texturas. |
| [TextureData](./texturedata/) | Esta clase contiene los datos sin procesar y la definición de formato de una textura. |
| [Viewport](./viewport/) | Un [`IRenderTarget`](../aspose.threed.render/irendertarget/) contiene al menos un viewport para renderizar la escena. |
| [WindowHandle](./windowhandle/) | Manejador de ventana encapsulado para diferentes plataformas. |
## Structures

| Estructura | Descripción |
| --- | --- |
| [CubeFaceData&lt;T&gt;](./cubefacedata-1/) | Datos de cada cara de la textura de mapa cúbico. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IBuffer](./ibuffer/) | La interfaz base de todos los buffers gestionados utilizados en el renderizado |
| [ICommandList](./icommandlist/) | Codifica una secuencia de comandos que se enviarán a la GPU para renderizar. |
| [IDescriptorSet](./idescriptorset/) | Los conjuntos de descriptores describen diferentes recursos que pueden usarse para enlazar al pipeline de renderizado, como buffers, texturas |
| [IIndexBuffer](./iindexbuffer/) | El buffer de índices describe la geometría utilizada en el pipeline de renderizado. |
| [IPipeline](./ipipeline/) | La secuencia predefinida de operaciones para dibujar en el lado de la GPU. |
| [IRenderQueue](./irenderqueue/) | El renderizador de entidades usa esta cola para gestionar tareas de renderizado. |
| [IRenderTarget](./irendertarget/) | La interfaz base del objetivo de renderizado |
| [IRenderTexture](./irendertexture/) | La interfaz de la textura de renderizado |
| [IRenderWindow](./irenderwindow/) | IRenderWindow representa la ventana nativa creada por el sistema operativo que soporta el renderizado. |
| [ITexture1D](./itexture1d/) | Textura 1D |
| [ITexture2D](./itexture2d/) | Textura 2D |
| [ITextureCodec](./itexturecodec/) | Códec para texturas |
| [ITextureCubemap](./itexturecubemap/) | Textura de mapa cúbico |
| [ITextureDecoder](./itexturedecoder/) | El decodificador de texturas externo debe implementar esta interfaz para decodificar. |
| [ITextureEncoder](./itextureencoder/) | El codificador de texturas externo debe implementar esta interfaz para codificar. |
| [ITextureUnit](./itextureunit/) | [`ITextureUnit`](../aspose.threed.render/itextureunit/) representa una textura en la memoria que se comparte entre la GPU y la CPU y puede ser muestreada por el shader, donde el [`Texture`](../aspose.threed.shading/texture/) solo representa una referencia a un archivo externo. Se pueden encontrar más detalles en https://en.wikipedia.org/wiki/Texture_mapping_unit |
| [IVertexBuffer](./ivertexbuffer/) | El buffer de vértices contiene los datos de los vértices del polígono que se enviarán al pipeline de renderizado |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [BlendFactor](./blendfactor/) | El factor de mezcla especifica la aritmética de píxeles. |
| [CompareFunction](./comparefunction/) | La función de comparación utilizada en las pruebas de profundidad/stencil. |
| [CubeFace](./cubeface/) | Cada cara de la textura del mapa cúbico |
| [CullFaceMode](./cullfacemode/) | Qué cara descartar |
| [DrawOperation](./drawoperation/) | Los tipos de primitivas a renderizar |
| [EntityRendererFeatures](./entityrendererfeatures/) | Las características extra que proporcionará el renderizador de entidades |
| [FrontFace](./frontface/) | Definir polígonos frontales y traseros |
| [IndexDataType](./indexdatatype/) | El tipo de datos de los elementos en [`IIndexBuffer`](../aspose.threed.render/iindexbuffer/) |
| [PixelFormat](./pixelformat/) | El formato del píxel usado en la unidad de textura. |
| [PixelMapMode](./pixelmapmode/) |  |
| [PolygonMode](./polygonmode/) | El modo de rasterizado de polígonos |
| [PresetShaders](./presetshaders/) | Esto define los shaders internos preestablecidos usados por el renderizador. |
| [RenderQueueGroupId](./renderqueuegroupid/) | El ID de grupo de la cola de renderizado |
| [RenderStage](./renderstage/) | La etapa de renderizado |
| [ShaderStage](./shaderstage/) | Etapa del shader |
| [StencilAction](./stencilaction/) | Las acciones de la prueba de stencil |
| [TextureType](./texturetype/) | El tipo de [`ITextureUnit`](../aspose.threed.render/itextureunit/) |


