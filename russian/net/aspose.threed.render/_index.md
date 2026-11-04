---
title: "Aspose.ThreeD.Render"
second_title: "Справочник API Aspose.3D для .NET"
description: "Все классы, связанные с рендерингом, определены в этом пространстве имён"
type: docs
weight: 80
url: /ru/net/aspose.threed.render/
---
Все классы, связанные с рендерингом, определены в этом пространстве имён

## Классы

| Класс | Описание |
| --- | --- |
| [DescriptorSetUpdater](./descriptorsetupdater/) | Этот класс позволяет обновлять [`IDescriptorSet`](../aspose.threed.render/idescriptorset/) в цепочечной операции. |
| [DriverException](./driverexception/) | Исключение, вызываемое внутренними драйверами рендеринга. |
| [EntityRenderer](./entityrenderer/) | Создайте подкласс, чтобы реализовать рендеринг для разных типов сущностей. |
| [EntityRendererKey](./entityrendererkey/) | Ключ зарегистрированного рендерера сущностей |
| [GLSLSource](./glslsource/) | Исходный код шейдеров на GLSL |
| [InitializationException](./initializationexception/) | Исключения при инициализации конвейера рендеринга |
| [PixelMapping](./pixelmapping/) |  |
| [PostProcessing](./postprocessing/) | Эффекты постобработки |
| [PushConstant](./pushconstant/) | Утилита для передачи данных в шейдер через push‑константу. |
| [Renderer](./renderer/) | Контекст рендерера. |
| [RendererVariableManager](./renderervariablemanager/) | Этот класс управляет переменными, используемыми в рендеринге |
| [RenderFactory](./renderfactory/) | RenderFactory создает все ресурсы, представленные в конвейере рендеринга. |
| [RenderParameters](./renderparameters/) | Опишите параметры целевого рендеринга |
| [RenderResource](./renderresource/) | Абстрактный класс всех ресурсов рендеринга. Все ресурсы рендеринга будут освобождены при выпуске рендерера. Классы, такие как [`Mesh`](../aspose.threed.entities/mesh/)/[`Texture`](../aspose.threed.shading/texture/), будут иметь соответствующий RenderResource |
| [RenderState](./renderstate/) | Состояние рендеринга для построения конвейера. Изменения, внесённые в состояние рендеринга, не повлияют на созданные экземпляры конвейера. |
| [ShaderException](./shaderexception/) | Исключения, связанные с шейдерами |
| [ShaderProgram](./shaderprogram/) | Шейдерная программа |
| [ShaderSet](./shaderset/) | Шейдерные программы для каждого типа материалов |
| [ShaderSource](./shadersource/) | Исходный код шейдера |
| [ShaderVariable](./shadervariable/) | Переменная шейдера |
| [SPIRVSource](./spirvsource/) | Скомпилированный шейдер в формате SPIR-V. |
| [StencilState](./stencilstate/) | Состояния трафарета для каждой грани. |
| [TextureCodec](./texturecodec/) | Класс для управления кодировщиками и декодировщиками текстур. |
| [TextureData](./texturedata/) | Этот класс содержит необработанные данные и определение формата текстуры. |
| [Viewport](./viewport/) | Объект [`IRenderTarget`](../aspose.threed.render/irendertarget/) содержит как минимум один видовой порт для рендеринга сцены. |
| [WindowHandle](./windowhandle/) | Инкапсулированный дескриптор окна для разных платформ. |
## Structures

| Структура | Описание |
| --- | --- |
| [CubeFaceData&lt;T&gt;](./cubefacedata-1/) | Данные для каждой грани кубической карты текстур. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IBuffer](./ibuffer/) | Базовый интерфейс всех управляемых буферов, используемых в рендеринге |
| [ICommandList](./icommandlist/) | Кодирует последовательность команд, которые будут отправлены на GPU для рендеринга. |
| [IDescriptorSet](./idescriptorset/) | Наборы дескрипторов описывают различные ресурсы, которые можно привязать к конвейеру рендеринга, такие как буферы и текстуры |
| [IIndexBuffer](./iindexbuffer/) | Индексный буфер описывает геометрию, используемую в конвейере рендеринга. |
| [IPipeline](./ipipeline/) | Предварительно подготовленная последовательность операций для отрисовки на стороне GPU. |
| [IRenderQueue](./irenderqueue/) | Рендерер сущностей использует эту очередь для управления задачами рендеринга. |
| [IRenderTarget](./irendertarget/) | Базовый интерфейс целевого рендеринга |
| [IRenderTexture](./irendertexture/) | Интерфейс рендер-текстуры |
| [IRenderWindow](./irenderwindow/) | IRenderWindow представляет нативное окно, созданное операционной системой и поддерживающее рендеринг. |
| [ITexture1D](./itexture1d/) | 1D текстура |
| [ITexture2D](./itexture2d/) | 2D текстура |
| [ITextureCodec](./itexturecodec/) | Кодек для текстур |
| [ITextureCubemap](./itexturecubemap/) | Текстура кубической карты |
| [ITextureDecoder](./itexturedecoder/) | Внешний декодер текстур должен реализовать этот интерфейс для декодирования. |
| [ITextureEncoder](./itextureencoder/) | Внешний кодировщик текстур должен реализовать этот интерфейс для кодирования. |
| [ITextureUnit](./itextureunit/) | [`ITextureUnit`](../aspose.threed.render/itextureunit/) представляет текстуру в памяти, общую между GPU и CPU и может быть использована в шейдере, тогда как [`Texture`](../aspose.threed.shading/texture/) представляет лишь ссылку на внешний файл. Подробнее можно узнать https://en.wikipedia.org/wiki/Texture_mapping_unit |
| [IVertexBuffer](./ivertexbuffer/) | Вершинный буфер хранит данные вершин полигонов, которые будут отправлены в конвейер рендеринга |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [BlendFactor](./blendfactor/) | Коэффициент смешивания определяет арифметику пикселей. |
| [CompareFunction](./comparefunction/) | Функция сравнения, используемая при тестировании глубины/трафарета. |
| [CubeFace](./cubeface/) | Каждая грань кубической карты текстур |
| [CullFaceMode](./cullfacemode/) | Какая грань отбрасывать |
| [DrawOperation](./drawoperation/) | Типы примитивов для рендеринга |
| [EntityRendererFeatures](./entityrendererfeatures/) | Дополнительные возможности, которые предоставит рендерер сущностей |
| [FrontFace](./frontface/) | Определить полигоны, ориентированные наружу и внутрь |
| [IndexDataType](./indexdatatype/) | Тип данных элементов в [`IIndexBuffer`](../aspose.threed.render/iindexbuffer/) |
| [PixelFormat](./pixelformat/) | Формат пикселя, используемый в текстурном юните. |
| [PixelMapMode](./pixelmapmode/) |  |
| [PolygonMode](./polygonmode/) | Режим растеризации полигонов |
| [PresetShaders](./presetshaders/) | Это определяет предустановленные внутренние шейдеры, используемые рендерером. |
| [RenderQueueGroupId](./renderqueuegroupid/) | Идентификатор группы в очереди рендеринга |
| [RenderStage](./renderstage/) | Этап рендеринга |
| [ShaderStage](./shaderstage/) | Этап шейдера |
| [StencilAction](./stencilaction/) | Действия теста трафарета |
| [TextureType](./texturetype/) | Тип [`ITextureUnit`](../aspose.threed.render/itextureunit/) |


