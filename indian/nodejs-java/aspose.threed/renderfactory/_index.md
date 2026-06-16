---
title: "RenderFactory"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory रेंडरिंग पाइपलाइन में प्रतिनिधित्व किए गए सभी संसाधनों को बनाता है।  @hideconstructor


## विधियाँ

### createRenderTexture{#createRenderTexture}

| नाम | विवरण |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | एक रेंडर टार्गेट बनाएं जो टेक्सचर पर रेंडर करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| parameters | RenderParameters | रेंडर टेक्सचर बनाने के लिए रेंडर पैरामीटर |
| targets | Number | कितने रंग आउटपुट टार्गेट्स |
| चौड़ाई | Number | रेंडर टेक्सचर की चौड़ाई |
| height | Number | रेंडर टेक्सचर की ऊँचाई |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| नाम | विवरण |
| --- | --- |
| createRenderTexture(parameters, width, height) | एक रेंडर टार्गेट बनाएं जिसमें 1 टार्गेट हो जो टेक्सचर पर रेंडर करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| parameters | RenderParameters | रेंडर टेक्सचर बनाने के लिए रेंडर पैरामीटर |
| चौड़ाई | Number | रेंडर टेक्सचर की चौड़ाई |
| height | Number | रेंडर टेक्सचर की ऊँचाई |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| नाम | विवरण |
| --- | --- |
| createDescriptorSet(shader) | निर्दिष्ट शेडर प्रोग्राम के लिए डिस्क्रिप्टर सेट बनाएं। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| shader | ShaderProgram | शेडर प्रोग्राम |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| नाम | विवरण |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | एक रेंडर टार्गेट बनाएं जिसमें 1 क्यूब टेक्सचर हो |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| parameters | RenderParameters | रेंडर टेक्सचर बनाने के लिए रेंडर पैरामीटर |
| चौड़ाई | Number | रेंडर टेक्सचर की चौड़ाई |
| height | Number | रेंडर टेक्सचर की ऊँचाई |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| नाम | विवरण |
| --- | --- |
| createRenderWindow(parameters, handle) | एक रेंडर टार्गेट बनाएं जो नेटिव विंडो पर रेंडर करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| parameters | RenderParameters | रेंडर विंडो बनाने के लिए रेंडर पैरामीटर |
| handle | WindowHandle | रेंडर करने वाली विंडो का हैंडल |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| नाम | विवरण |
| --- | --- |
| createVertexBuffer(declaration) | एक com.aspose.threed.IVertexBuffer इंस्टेंस बनाएं ताकि बहुभुज की वर्टेक्स जानकारी संग्रहीत की जा सके। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| नाम | विवरण |
| --- | --- |
| createIndexBuffer() | एक com.aspose.threed.IIndexBuffer इंस्टेंस बनाएं ताकि बहुभुज के फेस की जानकारी संग्रहीत की जा सके। |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| नाम | विवरण |
| --- | --- |
| createTextureUnit(textureType) | एक टेक्सचर यूनिट बनाएं जिसे शेडर द्वारा एक्सेस किया जा सके। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| नाम | विवरण |
| --- | --- |
| createTextureUnit() | एक 2D टेक्सचर यूनिट बनाएं जिसे शेडर द्वारा एक्सेस किया जा सके। |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| नाम | विवरण |
| --- | --- |
| createShaderProgram(shaderSource) | एक ShaderProgram ऑब्जेक्ट बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| shaderSource | ShaderSource | शेडर का स्रोत कोड |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| नाम | विवरण |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | एक पूर्वनिर्धारित ग्राफिक्स पाइपलाइन बनाएं जिसमें पूर्वनिर्धारित शेडर/रेंडर स्टेट/वर्टेक्स डिक्लेरेशन और ड्रॉ ऑपरेशन्स हों। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| shader | ShaderProgram | रेंडरिंग में उपयोग किया गया शेडर |
| renderState | RenderState | रेंडरिंग में उपयोग किया गया रेंडर स्टेट |
| vertexDeclaration | VertexDeclaration | इनपुट वर्टेक्स डेटा की वर्टेक्स डिक्लेरेशन |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| नाम | विवरण |
| --- | --- |
| createUniformBuffer(size) | GPU पक्ष में पूर्व-आवंटित आकार के साथ एक नया यूनिफॉर्म बफ़र बनाएं। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| आकार | Number | यूनिफॉर्म बफ़र का आकार |

 **Result:**
IBuffer


---



