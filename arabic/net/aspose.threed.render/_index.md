---
title: "Aspose.ThreeD.Render"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
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
| [EntityRenderer](./entityrenderer/) | قم بإنشاء فئة فرعية من هذه لتطبيق العرض لأنواع مختلفة من الكيانات. |
| [EntityRendererKey](./entityrendererkey/) | المفتاح الخاص بعارض الكيان المسجل |
| [GLSLSource](./glslsource/) | الكود المصدري للظلال في GLSL |
| [InitializationException](./initializationexception/) | استثناءات في تهيئة خط أنابيب العرض |
| [PixelMapping](./pixelmapping/) |  |
| [PostProcessing](./postprocessing/) | تأثيرات ما بعد المعالجة |
| [PushConstant](./pushconstant/) | أداة لتوفير البيانات للظل عبر ثابت الدفع. |
| [Renderer](./renderer/) | السياق المتعلق بالعارض. |
| [RendererVariableManager](./renderervariablemanager/) | تدير هذه الفئة المتغيرات المستخدمة في العرض |
| [RenderFactory](./renderfactory/) | يقوم RenderFactory بإنشاء جميع الموارد التي تم تمثيلها في خط أنابيب العرض. |
| [RenderParameters](./renderparameters/) | وصف معلمات هدف العرض |
| [RenderResource](./renderresource/) | الفئة المجردة لجميع موارد العرض جميع موارد العرض سيتم التخلص منها عند تحرير العارض. الفئات مثل [`Mesh`](../aspose.threed.entities/mesh/)/[`Texture`](../aspose.threed.shading/texture/) سيكون لها مورد عرض مطابق |
| [RenderState](./renderstate/) | حالة العرض لبناء خط الأنابيب التغييرات التي تُجرى على حالة العرض لن تؤثر على مثيلات خط الأنابيب التي تم إنشاؤها. |
| [ShaderException](./shaderexception/) | استثناءات متعلقة بالظل |
| [ShaderProgram](./shaderprogram/) | برنامج الظل |
| [ShaderSet](./shaderset/) | برامج الظل لكل نوع من المواد |
| [ShaderSource](./shadersource/) | الكود المصدري للظل |
| [ShaderVariable](./shadervariable/) | متغير الظل |
| [SPIRVSource](./spirvsource/) | المُجسَّد المُترجم بصيغة SPIR-V. |
| [StencilState](./stencilstate/) | حالات القالب لكل وجه. |
| [TextureCodec](./texturecodec/) | فئة لإدارة المشفرات والمفككات للملمس. |
| [TextureData](./texturedata/) | تحتوي هذه الفئة على البيانات الأولية وتعريف الصيغة للملمس. |
| [Viewport](./viewport/) | يحتوي [`IRenderTarget`](../aspose.threed.render/irendertarget/) على الأقل على واجهة عرض واحدة لتصوير المشهد. |
| [WindowHandle](./windowhandle/) | مقبض نافذة مُغلق لمنصات مختلفة. |
## Structures

| بنية | الوصف |
| --- | --- |
| [CubeFaceData&lt;T&gt;](./cubefacedata-1/) | بيانات لكل وجه من نسيج خريطة المكعب. |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [IBuffer](./ibuffer/) | الواجهة الأساسية لجميع المخازن المُدارة المستخدمة في التصيير. |
| [ICommandList](./icommandlist/) | يقوم بترميز تسلسل من الأوامر التي سيتم إرسالها إلى وحدة معالجة الرسومات للتصوير. |
| [IDescriptorSet](./idescriptorset/) | مجموعة الوصف تصف الموارد المختلفة التي يمكن استخدامها للربط بأنابيب التصيير مثل المخازن والملمس. |
| [IIndexBuffer](./iindexbuffer/) | مخزن الفهرس يصف الهندسة المستخدمة في أنابيب التصيير. |
| [IPipeline](./ipipeline/) | تسلسل العمليات المسبق التحضير للرسم على جانب وحدة معالجة الرسومات. |
| [IRenderQueue](./irenderqueue/) | مُصوِّر الكيان يستخدم هذه الطابور لإدارة مهام التصيير. |
| [IRenderTarget](./irendertarget/) | الواجهة الأساسية لهدف التصيير. |
| [IRenderTexture](./irendertexture/) | واجهة نسيج التصيير. |
| [IRenderWindow](./irenderwindow/) | IRenderWindow يمثل النافذة الأصلية التي أنشأها نظام التشغيل وتدعم التصيير. |
| [ITexture1D](./itexture1d/) | ملمس أحادي الأبعاد. |
| [ITexture2D](./itexture2d/) | ملمس ثنائي الأبعاد. |
| [ITextureCodec](./itexturecodec/) | مُرمّز للملمس. |
| [ITextureCubemap](./itexturecubemap/) | ملمس خريطة المكعب. |
| [ITextureDecoder](./itexturedecoder/) | يجب على مفكك الملمس الخارجي تنفيذ هذه الواجهة لفك الترميز. |
| [ITextureEncoder](./itextureencoder/) | يجب على مشفر الملمس الخارجي تنفيذ هذه الواجهة للترميز. |
| [ITextureUnit](./itextureunit/) | [`ITextureUnit`](../aspose.threed.render/itextureunit/) يمثل نسيجًا في الذاكرة يتم مشاركته بين وحدة معالجة الرسومات ووحدة المعالجة المركزية ويمكن أخذ عينات منه بواسطة المُظلّل، حيث أن [`Texture`](../aspose.threed.shading/texture/) يمثل فقط مرجعًا إلى ملف خارجي. يمكن العثور على مزيد من التفاصيل https://en.wikipedia.org/wiki/Texture_mapping_unit |
| [IVertexBuffer](./ivertexbuffer/) | مخزن الرؤوس يحتفظ ببيانات رؤوس المضلع التي سيتم إرسالها إلى أنابيب التصيير. |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [BlendFactor](./blendfactor/) | عامل الدمج يحدد حسابات البكسل. |
| [CompareFunction](./comparefunction/) | دالة المقارنة المستخدمة في اختبار العمق/القالب. |
| [CubeFace](./cubeface/) | كل وجه من نسيج خريطة المكعب. |
| [CullFaceMode](./cullfacemode/) | الوجه الذي يجب إلغاءه. |
| [DrawOperation](./drawoperation/) | أنواع الكائنات الأولية للتصيير. |
| [EntityRendererFeatures](./entityrendererfeatures/) | الميزات الإضافية التي سيقدمها عارض الكيان. |
| [FrontFace](./frontface/) | تحديد المضلعات المواجهة للأمام والخلف. |
| [IndexDataType](./indexdatatype/) | نوع البيانات للعناصر في [`IIndexBuffer`](../aspose.threed.render/iindexbuffer/). |
| [PixelFormat](./pixelformat/) | تنسيق البكسل المستخدم في وحدة النسيج. |
| [PixelMapMode](./pixelmapmode/) |  |
| [PolygonMode](./polygonmode/) | وضع تمثيل المضلعات. |
| [PresetShaders](./presetshaders/) | هذا يحدد المظلات الداخلية المسبقة المستخدمة من قبل العارض. |
| [RenderQueueGroupId](./renderqueuegroupid/) | معرّف المجموعة في طابور العرض. |
| [RenderStage](./renderstage/) | مرحلة العرض. |
| [ShaderStage](./shaderstage/) | مرحلة المظلل. |
| [StencilAction](./stencilaction/) | إجراءات اختبار القالب. |
| [TextureType](./texturetype/) | نوع الـ [`ITextureUnit`](../aspose.threed.render/itextureunit/). |


