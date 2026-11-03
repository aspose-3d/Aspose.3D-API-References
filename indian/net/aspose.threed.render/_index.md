---
title: "Aspose.ThreeD.Render"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "सभी रेंडरिंग संबंधित क्लासेस इस नामस्थान में परिभाषित हैं।"
type: docs
weight: 80
url: /hi/net/aspose.threed.render/
---
सभी रेंडरिंग संबंधित क्लासेस इस नामस्थान में परिभाषित हैं।

## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [DescriptorSetUpdater](./descriptorsetupdater/) | यह क्लास चेन ऑपरेशन में [`IDescriptorSet`](../aspose.threed.render/idescriptorset/) को अपडेट करने की अनुमति देती है। |
| [DriverException](./driverexception/) | आंतरिक रेंडरिंग ड्राइवरों द्वारा उठाई गई अपवाद। |
| [EntityRenderer](./entityrenderer/) | विभिन्न प्रकार की इकाइयों के लिए रेंडरिंग लागू करने हेतु इसे सबक्लास करें। |
| [EntityRendererKey](./entityrendererkey/) | रजिस्टर्ड एंटिटी रेंडरर की कुंजी |
| [GLSLSource](./glslsource/) | GLSL में शेडर का स्रोत कोड |
| [InitializationException](./initializationexception/) | रेंडर पाइपलाइन इनिशियलाइज़ेशन में अपवाद |
| [PixelMapping](./pixelmapping/) |  |
| [PostProcessing](./postprocessing/) | पोस्ट-प्रोसेसिंग इफ़ेक्ट्स |
| [PushConstant](./pushconstant/) | पुश कॉन्स्टेंट के माध्यम से शेडर को डेटा प्रदान करने के लिए एक उपयोगिता। |
| [Renderer](./renderer/) | रेंडरर के बारे में संदर्भ। |
| [RendererVariableManager](./renderervariablemanager/) | यह क्लास रेंडरिंग में उपयोग होने वाले वेरिएबल्स को प्रबंधित करती है। |
| [RenderFactory](./renderfactory/) | RenderFactory रेंडरिंग पाइपलाइन में प्रतिनिधित्व किए गए सभी संसाधनों को बनाता है। |
| [RenderParameters](./renderparameters/) | रेंडर टार्गेट के पैरामीटरों का वर्णन करें |
| [RenderResource](./renderresource/) | सभी रेंडर संसाधनों की एब्स्ट्रैक्ट क्लास। सभी रेंडर संसाधनों को रेंडरर रिलीज़ होने पर डिस्पोज़ किया जाएगा। [`Mesh`](../aspose.threed.entities/mesh/)/[`Texture`](../aspose.threed.shading/texture/) जैसी क्लासों का एक संबंधित RenderResource होगा। |
| [RenderState](./renderstate/) | पाइपलाइन बनाने के लिए रेंडर स्टेट। रेंडर स्टेट पर किए गए परिवर्तन बनाए गए पाइपलाइन इंस्टेंसेज़ को प्रभावित नहीं करेंगे। |
| [ShaderException](./shaderexception/) | शेडर संबंधित अपवाद |
| [ShaderProgram](./shaderprogram/) | शेडर प्रोग्राम |
| [ShaderSet](./shaderset/) | प्रत्येक प्रकार की सामग्री के लिए शेडर प्रोग्राम्स |
| [ShaderSource](./shadersource/) | शेडर का स्रोत कोड |
| [ShaderVariable](./shadervariable/) | शेडर वेरिएबल |
| [SPIRVSource](./spirvsource/) | SPIR-V प्रारूप में संकलित शेडर। |
| [StencilState](./stencilstate/) | प्रत्येक फेस के लिए स्टेंसिल स्थितियाँ। |
| [TextureCodec](./texturecodec/) | टेक्सचर के लिए एन्कोडर और डिकोडर को प्रबंधित करने वाली क्लास। |
| [TextureData](./texturedata/) | यह क्लास टेक्सचर का कच्चा डेटा और प्रारूप परिभाषा रखती है। |
| [Viewport](./viewport/) | एक [`IRenderTarget`](../aspose.threed.render/irendertarget/) में दृश्य को रेंडर करने के लिए कम से कम एक व्यूपोर्ट होता है। |
| [WindowHandle](./windowhandle/) | विभिन्न प्लेटफ़ॉर्म के लिए संलग्न विंडो हैंडल। |
## Structures

| संरचना | विवरण |
| --- | --- |
| [CubeFaceData&lt;T&gt;](./cubefacedata-1/) | क्यूब मैप टेक्सचर के प्रत्येक फेस के लिए डेटा। |
## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [IBuffer](./ibuffer/) | रेंडरिंग में उपयोग किए जाने वाले सभी प्रबंधित बफ़र्स का बेस इंटरफ़ेस। |
| [ICommandList](./icommandlist/) | रेंडर करने के लिए GPU को भेजे जाने वाले कमांड्स की श्रृंखला को एन्कोड करता है। |
| [IDescriptorSet](./idescriptorset/) | डिस्क्रिप्टर सेट विभिन्न संसाधनों का वर्णन करता है जिन्हें बफ़र्स, टेक्सचर आदि के रूप में रेंडर पाइपलाइन से बाइंड किया जा सकता है। |
| [IIndexBuffer](./iindexbuffer/) | इंडेक्स बफ़र रेंडरिंग पाइपलाइन में उपयोग की जाने वाली ज्यामिति का वर्णन करता है। |
| [IPipeline](./ipipeline/) | GPU पक्ष पर ड्रॉ करने के लिए पूर्व-निर्धारित ऑपरेशनों की श्रृंखला। |
| [IRenderQueue](./irenderqueue/) | एंटिटी रेंडरर इस कतार का उपयोग रेंडर कार्यों को प्रबंधित करने के लिए करता है। |
| [IRenderTarget](./irendertarget/) | रेंडर टार्गेट का बेस इंटरफ़ेस। |
| [IRenderTexture](./irendertexture/) | रेंडर टेक्सचर का इंटरफ़ेस। |
| [IRenderWindow](./irenderwindow/) | IRenderWindow वह मूल विंडो दर्शाता है जो ऑपरेटिंग सिस्टम द्वारा बनाई गई है और रेंडरिंग का समर्थन करती है। |
| [ITexture1D](./itexture1d/) | 1D टेक्सचर |
| [ITexture2D](./itexture2d/) | 2D टेक्सचर |
| [ITextureCodec](./itexturecodec/) | टेक्सचर के लिए कोडेक |
| [ITextureCubemap](./itexturecubemap/) | क्यूब मैप टेक्सचर |
| [ITextureDecoder](./itexturedecoder/) | बाहरी टेक्सचर डिकोडर को डिकोडिंग के लिए इस इंटरफ़ेस को लागू करना चाहिए। |
| [ITextureEncoder](./itextureencoder/) | बाहरी टेक्सचर एन्कोडर को एन्कोडिंग के लिए इस इंटरफ़ेस को लागू करना चाहिए। |
| [ITextureUnit](./itextureunit/) | [`ITextureUnit`](../aspose.threed.render/itextureunit/) मेमोरी में एक टेक्सचर दर्शाता है जो GPU और CPU के बीच साझा होता है और शेडर द्वारा सैंपल किया जा सकता है, जबकि [`Texture`](../aspose.threed.shading/texture/) केवल बाहरी फ़ाइल के संदर्भ को दर्शाता है। अधिक विवरण https://en.wikipedia.org/wiki/Texture_mapping_unit पर पाया जा सकता है। |
| [IVertexBuffer](./ivertexbuffer/) | वर्टेक्स बफ़र वह बहुभुज वर्टेक्स डेटा रखता है जो रेंडरिंग पाइपलाइन को भेजा जाएगा। |
## एन्यूमरेशन

| एन्यूमरेशन | विवरण |
| --- | --- |
| [BlendFactor](./blendfactor/) | ब्लेंड फैक्टर पिक्सेल अंकगणित को निर्दिष्ट करता है। |
| [CompareFunction](./comparefunction/) | गहराई/स्टेंसिल परीक्षण में उपयोग किया जाने वाला तुलना फ़ंक्शन। |
| [CubeFace](./cubeface/) | क्यूब मैप टेक्सचर का प्रत्येक चेहरा |
| [CullFaceMode](./cullfacemode/) | कौन सा चेहरा हटाना है |
| [DrawOperation](./drawoperation/) | रेंडर करने के लिए मूल प्रकार |
| [EntityRendererFeatures](./entityrendererfeatures/) | एंटिटी रेंडरर द्वारा प्रदान की जाने वाली अतिरिक्त सुविधाएँ |
| [FrontFace](./frontface/) | सामने और पीछे की ओर मुख वाले बहुभुज को परिभाषित करें |
| [IndexDataType](./indexdatatype/) | [`IIndexBuffer`](../aspose.threed.render/iindexbuffer/) में तत्वों का डेटा प्रकार |
| [PixelFormat](./pixelformat/) | टेक्सचर यूनिट में उपयोग किया गया पिक्सेल फ़ॉर्मेट। |
| [PixelMapMode](./pixelmapmode/) |  |
| [PolygonMode](./polygonmode/) | बहुभुज रास्टराइज़ेशन मोड |
| [PresetShaders](./presetshaders/) | यह रेंडरर द्वारा उपयोग किए जाने वाले पूर्वनिर्धारित आंतरिक शेडर को परिभाषित करता है। |
| [RenderQueueGroupId](./renderqueuegroupid/) | रेंडर कतार का समूह आईडी |
| [RenderStage](./renderstage/) | रेंडर चरण |
| [ShaderStage](./shaderstage/) | शेडर चरण |
| [StencilAction](./stencilaction/) | स्टेंसिल परीक्षण क्रियाएँ |
| [TextureType](./texturetype/) | [`ITextureUnit`](../aspose.threed.render/itextureunit/) का प्रकार |


