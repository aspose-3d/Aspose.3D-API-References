---
title: "Aspose.ThreeD.Render"
second_title: "مرجع Aspose.3D for .NET API"
description: "جميع الفئات المتعلقة بالتصيير معرفة في هذه المساحة."
type: docs
weight: 80
url: /ar/net/aspose.threed.render/
---
جميع الفئات المتعلقة بالتصيير معرفة في هذه المساحة.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [DescriptorSetUpdater](./descriptorsetupdater/) | تسمح هذه الفئة بتحديث [`IDescriptorSet`](../aspose.threed.render/idescriptorset/) في عملية سلسلة. |
| [DriverException](./driverexception/) | الاستثناء الذي يثيره برامج تشغيل العرض الداخلية. |
| [EntityRenderer](./entityrenderer/) | قم بإنشاء فئة فرعية من هذه لتنفيذ العرض لأنواع مختلفة من الكيانات. |
| [EntityRendererKey](./entityrendererkey/) | المفتاح الخاص بعارض الكيانات المسجل |
| [GLSLSource](./glslsource/) | شفرة المصدر للظلّات في GLSL |
| [InitializationException](./initializationexception/) | استثناءات في تهيئة خط أنابيب العرض |
| [PixelMapping](./pixelmapping/) |  |
| [PostProcessing](./postprocessing/) | تأثيرات ما بعد المعالجة |
| [PushConstant](./pushconstant/) | أداة لتوفير البيانات إلى الظلّ عبر ثابت الدفع. |
| [Renderer](./renderer/) | السياق المتعلق بالعارض. |
| [RendererVariableManager](./renderervariablemanager/) | هذه الفئة تدير المتغيرات المستخدمة في العرض |
| [RenderFactory](./renderfactory/) | RenderFactory تنشئ جميع الموارد التي تم تمثيلها في خط أنابيب العرض. |
| [RenderParameters](./renderparameters/) | وصف معلمات هدف العرض |
| [RenderResource](./renderresource/) | الفئة المجردة لجميع موارد العرض جميع موارد العرض سيتم التخلص منها عندما يتم تحرير العارض. الفئات مثل [`Mesh`](../aspose.threed.entities/mesh/)/[`Texture`](../aspose.threed.shading/texture/) سيكون لها RenderResource مطابق |
| [RenderState](./renderstate/) | حالة العرض لبناء خط الأنابيب التغييرات التي تُجرى على حالة العرض لن تؤثر على مثيلات خط الأنابيب المُنشأة. |
| [ShaderException](./shaderexception/) | استثناءات متعلقة بالظلّ |
| [ShaderProgram](./shaderprogram/) | برنامج الظلّ |
| [ShaderSet](./shaderset/) | برامج الظلّ لكل نوع من المواد |
| [ShaderSource](./shadersource/) | شفرة المصدر للظلّ |
| [ShaderVariable](./shadervariable/) | متغيّر الظلّ |
| [SPIRVSource](./spirvsource/) | الظلّ المترجم بتنسيق SPIR-V. |
| [StencilState](./stencilstate/) | حالات القالب لكل وجه. |
| [TextureCodec](./texturecodec/) | فئة لإدارة المشفرات والمفككات للملمس. |
| [TextureData](./texturedata/) | هذه الفئة تحتوي على البيانات الخام وتعريف التنسيق للملمس. |
| [Viewport](./viewport/) | [`IRenderTarget`](../aspose.threed.render/irendertarget/) يحتوي على منفذ عرض واحد على الأقل لعرض المشهد. |
| [WindowHandle](./windowhandle/) | مقبض نافذة مغلق للمنصات المختلفة. |
## Structures

| الهيكل | الوصف |
| --- | --- |
| [CubeFaceData&lt;T&gt;](./cubefacedata-1/) | بيانات لكل وجه من نسيج خريطة المكعب. |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [IBuffer](./ibuffer/) | واجهة الأساس لجميع المخازن المدارة المستخدمة في العرض |
| [ICommandList](./icommandlist/) | يقوم بترميز تسلسل من الأوامر التي سيتم إرسالها إلى GPU للتصوير. |
| [IDescriptorSet](./idescriptorset/) | تصف مجموعات الوصف الموارد المختلفة التي يمكن استخدامها للربط بأنابيب العرض مثل المخازن، القوام |
| [IIndexBuffer](./iindexbuffer/) | المخزن الفهرسي يصف الهندسة المستخدمة في أنابيب العرض. |
| [IPipeline](./ipipeline/) | تسلسل العمليات المسبق الإعداد للرسم على جانب GPU. |
| [IRenderQueue](./irenderqueue/) | مُصمم الكيانات يستخدم هذه الطابور لإدارة مهام العرض. |
| [IRenderTarget](./irendertarget/) | واجهة الأساس لهدف العرض |
| [IRenderTexture](./irendertexture/) | واجهة قوام العرض |
| [IRenderWindow](./irenderwindow/) | IRenderWindow تمثل النافذة الأصلية التي أنشأها نظام التشغيل وتدعم العرض. |
| [ITexture1D](./itexture1d/) | قوام أحادي البعد |
| [ITexture2D](./itexture2d/) | قوام ثنائي البعد |
| [ITextureCodec](./itexturecodec/) | الترميز للأنسجة |
| [ITextureCubemap](./itexturecubemap/) | قوام خريطة المكعب |
| [ITextureDecoder](./itexturedecoder/) | يجب على مُفكك القوام الخارجي تنفيذ هذه الواجهة لفك الترميز. |
| [ITextureEncoder](./itextureencoder/) | يجب على مُشفّر القوام الخارجي تنفيذ هذه الواجهة للترميز. |
| [ITextureUnit](./itextureunit/) | [`ITextureUnit`](../aspose.threed.render/itextureunit/) يمثل قوامًا في الذاكرة يتم مشاركته بين GPU وCPU ويمكن أخذ عينات منه بواسطة الـ shader، حيث أن [`Texture`](../aspose.threed.shading/texture/) يمثل فقط مرجعًا إلى ملف خارجي. يمكن العثور على مزيد من التفاصيل https://en.wikipedia.org/wiki/Texture_mapping_unit |
| [IVertexBuffer](./ivertexbuffer/) | المخزن الرأسي يحتفظ ببيانات رؤوس المضلعات التي سيتم إرسالها إلى أنابيب العرض |
## التعداد

| التعداد | الوصف |
| --- | --- |
| [BlendFactor](./blendfactor/) | عامل الدمج يحدد حسابات البكسل. |
| [CompareFunction](./comparefunction/) | دالة المقارنة المستخدمة في اختبار العمق/القالب. |
| [CubeFace](./cubeface/) | كل وجه من قوام خريطة المكعب |
| [CullFaceMode](./cullfacemode/) | الوجه الذي يجب إقصاؤه |
| [DrawOperation](./drawoperation/) | أنواع الكائنات الأولية للعرض |
| [EntityRendererFeatures](./entityrendererfeatures/) | الميزات الإضافية التي سيقدمها مُصمم الكيانات |
| [FrontFace](./frontface/) | تعريف المضلعات الأمامية والخلفية |
| [IndexDataType](./indexdatatype/) | نوع البيانات للعناصر في [`IIndexBuffer`](../aspose.threed.render/iindexbuffer/) |
| [PixelFormat](./pixelformat/) | تنسيق البكسل المستخدم في وحدة النسيج. |
| [PixelMapMode](./pixelmapmode/) |  |
| [PolygonMode](./polygonmode/) | وضع تصيير المضلعات |
| [PresetShaders](./presetshaders/) | هذا يحدد المظلات الداخلية المسبقة المستخدمة بواسطة المُظهر. |
| [RenderQueueGroupId](./renderqueuegroupid/) | معرّف المجموعة في طابور العرض |
| [RenderStage](./renderstage/) | مرحلة العرض |
| [ShaderStage](./shaderstage/) | مرحلة المظلل |
| [StencilAction](./stencilaction/) | إجراءات اختبار القالب |
| [TextureType](./texturetype/) | نوع الـ [`ITextureUnit`](../aspose.threed.render/itextureunit/) |


