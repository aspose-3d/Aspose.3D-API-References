---
title: "क्लास RenderFactory"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Render.RenderFactory क्लास। RenderFactory रेंडरिंग पाइपलाइन में प्रतिनिधित्व किए गए सभी संसाधन बनाता है।"
type: docs
weight: 2280
url: /hi/net/aspose.threed.render/renderfactory/
---
## RenderFactory class

RenderFactory रेंडरिंग पाइपलाइन में प्रतिनिधित्व किए गए सभी संसाधनों को बनाता है।

```csharp
public abstract class RenderFactory
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| abstract [CreateCubeRenderTexture](../../aspose.threed.render/renderfactory/createcuberendertexture/)(RenderParameters, int, int) | 1 क्यूब टेक्सचर वाला एक रेंडर टार्गेट बनाएं |
| abstract [CreateDescriptorSet](../../aspose.threed.render/renderfactory/createdescriptorset/)(ShaderProgram) | निर्दिष्ट शेडर प्रोग्राम के लिए डिस्क्रिप्टर सेट बनाएं। |
| abstract [CreateIndexBuffer](../../aspose.threed.render/renderfactory/createindexbuffer/)() | बहुभुज के फेस जानकारी को संग्रहीत करने के लिए एक [`IIndexBuffer`](../iindexbuffer/) इंस्टेंस बनाएं। |
| abstract [CreatePipeline](../../aspose.threed.render/renderfactory/createpipeline/)(ShaderProgram, RenderState, VertexDeclaration, DrawOperation) | पूर्व-निर्धारित शेडर/रेंडर स्टेट/वर्टेक्स घोषणा और ड्रॉ ऑपरेशन्स के साथ एक पूर्व-कॉन्फ़िगर किया गया ग्राफ़िक्स पाइपलाइन बनाएं। |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture)(RenderParameters, int, int) | टेक्सचर पर रेंडर करने वाले 1 टार्गेट वाला एक रेंडर टार्गेट बनाएं |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture_1)(RenderParameters, int, int, int) | टेक्सचर पर रेंडर करने वाला एक रेंडर टार्गेट बनाएं |
| abstract [CreateRenderWindow](../../aspose.threed.render/renderfactory/createrenderwindow/)(RenderParameters, WindowHandle) | नेटिव विंडो पर रेंडर करने वाला एक रेंडर टार्गेट बनाएं। |
| abstract [CreateShaderProgram](../../aspose.threed.render/renderfactory/createshaderprogram/)(ShaderSource) | एक [`ShaderProgram`](../shaderprogram/) ऑब्जेक्ट बनाएं |
| [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit)() | शेडर द्वारा एक्सेस किया जा सकने वाला 2D टेक्सचर यूनिट बनाएं। |
| abstract [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit_1)(TextureType) | शेडर द्वारा एक्सेस किया जा सकने वाला टेक्सचर यूनिट बनाएं। |
| abstract [CreateUniformBuffer](../../aspose.threed.render/renderfactory/createuniformbuffer/)(int) | GPU पक्ष में पूर्व-आवंटित आकार के साथ एक नया यूनिफ़ॉर्म बफ़र बनाएं। |
| abstract [CreateVertexBuffer](../../aspose.threed.render/renderfactory/createvertexbuffer/)(VertexDeclaration) | बहुभुज के वर्टेक्स जानकारी को संग्रहीत करने के लिए एक [`IVertexBuffer`](../ivertexbuffer/) इंस्टेंस बनाएं। |

### देखें भी

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


