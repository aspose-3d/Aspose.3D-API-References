---
title: RenderFactory
second_title: Aspose.3D for Java API Reference
description: RenderFactory रेंडरिंग पाइपलाइन में प्रतिनिधित्व किए गए सभी रिसोर्सेज़ बनाता है।
type: docs
weight: 148
url: /hi/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

RenderFactory रेंडरिंग पाइपलाइन में प्रतिनिधित्व किए गए सभी रिसोर्सेज़ बनाता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | 1 क्यूब टेक्सचर वाला रेंडर टार्गेट बनाएं |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | निर्दिष्ट शेडर प्रोग्राम के लिए डिस्क्रिप्टर सेट बनाएं। |
| [createIndexBuffer()](#createIndexBuffer--) | पॉलीगॉन के फेस जानकारी को संग्रहीत करने के लिए एक [IIndexBuffer](../../com.aspose.threed/iindexbuffer) इंस्टेंस बनाएं। |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | पूर्व-कॉन्फ़िगर किए गए शेडर/रेंडर स्टेट/वर्टेक्स डिक्लेरेशन और ड्रॉ ऑपरेशन्स के साथ एक प्री-कॉन्फ़िगर्ड ग्राफ़िक्स पाइपलाइन बनाएं। |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | 1 टार्गेट वाला रेंडर टार्गेट बनाएं जो टेक्सचर पर रेंडर करता है |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | एक रेंडर टार्गेट बनाएं जो टेक्सचर पर रेंडर करता है |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | एक रेंडर टार्गेट बनाएं जो नेटिव विंडो पर रेंडर करता है। |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | एक [ShaderProgram](../../com.aspose.threed/shaderprogram) ऑब्जेक्ट बनाएं |
| [createTextureUnit()](#createTextureUnit--) | एक 2D टेक्सचर यूनिट बनाएं जिसे शेडर द्वारा एक्सेस किया जा सके। |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | एक टेक्सचर यूनिट बनाएं जिसे शेडर द्वारा एक्सेस किया जा सके। |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | GPU पक्ष में पूर्व-आवंटित आकार के साथ एक नया यूनिफॉर्म बफ़र बनाएं। |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | पॉलीगॉन के वर्टेक्स जानकारी को संग्रहीत करने के लिए एक [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) इंस्टेंस बनाएं। |
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


1 क्यूब टेक्सचर वाला रेंडर टार्गेट बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | रेंडर टेक्सचर बनाने के लिए रेंडर पैरामीटर |
| चौड़ाई | int | रेंडर टेक्सचर की चौड़ाई |
| ऊँचाई | int | रेंडर टेक्सचर की ऊँचाई |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


निर्दिष्ट शेडर प्रोग्राम के लिए डिस्क्रिप्टर सेट बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | शेडर प्रोग्राम। |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


पॉलीगॉन के फेस जानकारी को संग्रहीत करने के लिए एक [IIndexBuffer](../../com.aspose.threed/iindexbuffer) इंस्टेंस बनाएं।

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


पूर्व-कॉन्फ़िगर किए गए शेडर/रेंडर स्टेट/वर्टेक्स डिक्लेरेशन और ड्रॉ ऑपरेशन्स के साथ एक प्री-कॉन्फ़िगर्ड ग्राफ़िक्स पाइपलाइन बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | रेंडरिंग में उपयोग किया गया शेडर |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | रेंडरिंग में उपयोग किया गया रेंडर स्टेट |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | इनपुट वर्टेक्स डेटा की वर्टेक्स डिक्लेरेशन |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | Draw operation |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


1 टार्गेट वाला रेंडर टार्गेट बनाएं जो टेक्सचर पर रेंडर करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | रेंडर टेक्सचर बनाने के लिए रेंडर पैरामीटर |
| चौड़ाई | int | रेंडर टेक्सचर की चौड़ाई |
| ऊँचाई | int | रेंडर टेक्सचर की ऊँचाई |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


एक रेंडर टार्गेट बनाएं जो टेक्सचर पर रेंडर करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | रेंडर टेक्सचर बनाने के लिए रेंडर पैरामीटर |
| targets | int | How many color output targets |
| चौड़ाई | int | रेंडर टेक्सचर की चौड़ाई |
| ऊँचाई | int | रेंडर टेक्सचर की ऊँचाई |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


एक रेंडर टार्गेट बनाएं जो नेटिव विंडो पर रेंडर करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Render parameters to create the render window |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | The handle of the window to render |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


एक [ShaderProgram](../../com.aspose.threed/shaderprogram) ऑब्जेक्ट बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | The source code of the shader |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


एक 2D टेक्सचर यूनिट बनाएं जिसे शेडर द्वारा एक्सेस किया जा सके।

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


एक टेक्सचर यूनिट बनाएं जिसे शेडर द्वारा एक्सेस किया जा सके।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | Type of the texture |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


GPU पक्ष में पूर्व-आवंटित आकार के साथ एक नया यूनिफॉर्म बफ़र बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| आकार | int | The size of the uniform buffer |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


पॉलीगॉन के वर्टेक्स जानकारी को संग्रहीत करने के लिए एक [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) इंस्टेंस बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

