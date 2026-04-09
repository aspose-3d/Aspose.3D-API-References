---
title: Renderer
second_title: Aspose.3D for Java API Reference
description: रेंडरर के बारे में कॉन्टेक्स्ट।
type: docs
weight: 152
url: /hi/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

रेंडरर के बारे में कॉन्टेक्स्ट।
## Methods

| Method | विवरण |
| --- | --- |
| [clearCache()](#clearCache--) | मैन्युअली कैश को साफ़ करें। |
| [close()](#close--) | डिस्पोज करें [Renderer](../../com.aspose.threed/renderer) और सभी संबंधित संसाधन। |
| [createRenderer()](#createRenderer--) | डिफ़ॉल्ट प्रोफ़ाइल के साथ एक नया [Renderer](../../com.aspose.threed/renderer) बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | निर्दिष्ट रेंडर टार्गेट पर पोस्ट प्रोसेसिंग निष्पादित करें। |
| [getAssetDirectories()](#getAssetDirectories--) | बाहरी एसेट्स को संग्रहीत करने वाली डायरेक्टरीज़। |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | छायाओं को सक्षम करने की स्थिति प्राप्त करता है। |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | जब इकाई के लिए कोई विशेष रेंडरर परिभाषित नहीं है, तो फॉलबैक एंटिटी रेंडरर प्राप्त करता है। |
| [getFrustum()](#getFrustum--) | व्यू मैट्रिक्स प्रदान करने के लिए उपयोग किए जाने वाले फ्रस्टम को प्राप्त करता है। |
| [getMaterial()](#getMaterial--) | शेडर द्वारा उपयोग की जाने वाली सामग्री जानकारी प्रदान करने वाले मैटेरियल को प्राप्त करता है। |
| [getNode()](#getNode--) | वर्ल्ड ट्रांसफ़ॉर्म मैट्रिक्स प्रदान करने के लिए उपयोग किए जाने वाले [getNode](../../com.aspose.threed/renderer\#getNode) इंस्टेंस को प्राप्त करता है। |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | रेंडरर द्वारा समर्थित बिल्ट-इन पोस्ट-प्रोसेसर को प्राप्त करता है। |
| [getPostProcessings()](#getPostProcessings--) | सक्रिय पोस्ट-प्रोसेसिंग चेन |
| [getPresetShaders()](#getPresetShaders--) | प्रीसेट शेडर सेट को प्राप्त करता है |
| [getRenderFactory()](#getRenderFactory--) | रेंडर-संबंधित ऑब्जेक्ट्स बनाने के लिए फ़ैक्ट्री को प्राप्त करता है। |
| [getRenderStage()](#getRenderStage--) | वर्तमान रेंडर स्टेज को प्राप्त करता है। |
| [getRenderTarget()](#getRenderTarget--) | रेंडर लक्ष्य निर्दिष्ट करें जिस पर निम्नलिखित रेंडर ऑपरेशन्स किए जाएंगे। |
| [getShader()](#getShader--) | ज्यामिति को रेंडर करने के लिए उपयोग किए जाने वाले शेडर इंस्टेंस को प्राप्त करता है। |
| [getShaderSet()](#getShaderSet--) | सीन को रेंडर करने के लिए उपयोग किए जाने वाले शेडर सेट को प्राप्त करता है। |
| [getVariables()](#getVariables--) | रेंडरिंग के लिए उपयोग किए जाने वाले आंतरिक वेरिएबल्स तक पहुँच |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | निर्दिष्ट इकाई के लिए एंटिटी रेंडरर को रजिस्टर करें |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | निर्दिष्ट लक्ष्य को रेंडर करें |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | छायाओं को सक्षम करने की सेटिंग। |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | जब इकाई के लिए कोई विशेष रेंडरर परिभाषित नहीं है, तो फॉलबैक एंटिटी रेंडरर सेट करता है। |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | व्यू मैट्रिक्स प्रदान करने के लिए उपयोग किए जाने वाले फ्रस्टम को सेट करता है। |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | शेडर द्वारा उपयोग की जाने वाली सामग्री जानकारी प्रदान करने वाले मैटेरियल को सेट करता है। |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | वर्ल्ड ट्रांसफ़ॉर्म मैट्रिक्स प्रदान करने के लिए उपयोग किए जाने वाले [getNode](../../com.aspose.threed/renderer\#getNode) इंस्टेंस को सेट करता है। |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | प्रीसेट शेडर सेट को सेट करता है |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | ज्यामिति को रेंडर करने के लिए उपयोग किए जाने वाले शेडर इंस्टेंस को सेट करता है। |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | सीन को रेंडर करने के लिए उपयोग किए जाने वाले शेडर सेट को सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


कैश को मैन्युअल रूप से साफ़ करें। Aspose.3D कुछ ऑब्जेक्ट्स जैसे मैटेरियल/ज्यामिति को रेंडर पाइपलाइन के साथ संगत आंतरिक प्रकारों में कैश करता है। यह तब मैन्युअल रूप से कॉल किया जाना चाहिए जब सीन में बड़े परिवर्तन हों।

### close() {#close--}
```
public void close()
```


डिस्पोज करें [Renderer](../../com.aspose.threed/renderer) और सभी संबंधित संसाधन।

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


डिफ़ॉल्ट प्रोफ़ाइल के साथ एक नया [Renderer](../../com.aspose.threed/renderer) बनाता है।

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
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
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


निर्दिष्ट रेंडर टार्गेट पर पोस्ट प्रोसेसिंग निष्पादित करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


बाहरी एसेट्स को संग्रहीत करने वाली डायरेक्टरीज़।

**Returns:**
java.util.ArrayList<java.lang.String> - बाहरी एसेट्स संग्रहीत करने वाले डायरेक्टरीज़
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableShadows() {#getEnableShadows--}
```
public boolean getEnableShadows()
```


छायाओं को सक्षम करने की स्थिति प्राप्त करता है।

**Returns:**
boolean - छायाओं को सक्षम करने के बारे में।
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


जब इकाई के लिए कोई विशेष रेंडरर परिभाषित नहीं है, तो फॉलबैक एंटिटी रेंडरर प्राप्त करता है।

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


व्यू मैट्रिक्स प्रदान करने के लिए उपयोग किए जाने वाले फ्रस्टम को प्राप्त करता है।

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


शेडर द्वारा उपयोग की जाने वाली सामग्री जानकारी प्रदान करने वाले मैटेरियल को प्राप्त करता है।

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


वर्ल्ड ट्रांसफ़ॉर्म मैट्रिक्स प्रदान करने के लिए उपयोग किए जाने वाले [getNode](../../com.aspose.threed/renderer\#getNode) इंस्टेंस को प्राप्त करता है।

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


रेंडरर द्वारा समर्थित बिल्ट-इन पोस्ट-प्रोसेसर को प्राप्त करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


सक्रिय पोस्ट-प्रोसेसिंग चेन

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - सक्रिय पोस्ट-प्रोसेसिंग श्रृंखला
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


प्रीसेट शेडर सेट को प्राप्त करता है

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


रेंडर-संबंधित ऑब्जेक्ट्स बनाने के लिए फ़ैक्ट्री को प्राप्त करता है।

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


वर्तमान रेंडर स्टेज को प्राप्त करता है।

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


रेंडर लक्ष्य निर्दिष्ट करें जिस पर निम्नलिखित रेंडर ऑपरेशन्स किए जाएंगे।

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


ज्यामिति को रेंडर करने के लिए उपयोग किए जाने वाले शेडर इंस्टेंस को प्राप्त करता है।

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


सीन को रेंडर करने के लिए उपयोग किए जाने वाले शेडर सेट को प्राप्त करता है।

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


रेंडरिंग के लिए उपयोग किए जाने वाले आंतरिक वेरिएबल्स तक पहुँच

**Returns:**
[RendererVariableManager](../../com.aspose.threed/renderervariablemanager) - Access to the internal variables used for rendering
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




### registerEntityRenderer(EntityRenderer renderer) {#registerEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void registerEntityRenderer(EntityRenderer renderer)
```


निर्दिष्ट इकाई के लिए एंटिटी रेंडरर को रजिस्टर करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


निर्दिष्ट लक्ष्य को रेंडर करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


छायाओं को सक्षम करने की सेटिंग।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


जब इकाई के लिए कोई विशेष रेंडरर परिभाषित नहीं है, तो फॉलबैक एंटिटी रेंडरर सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | नया मान |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


व्यू मैट्रिक्स प्रदान करने के लिए उपयोग किए जाने वाले फ्रस्टम को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | नया मान |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


शेडर द्वारा उपयोग की जाने वाली सामग्री जानकारी प्रदान करने वाले मैटेरियल को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | नया मान |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


वर्ल्ड ट्रांसफ़ॉर्म मैट्रिक्स प्रदान करने के लिए उपयोग किए जाने वाले [getNode](../../com.aspose.threed/renderer\#getNode) इंस्टेंस को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | नया मान |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


प्रीसेट शेडर सेट को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | नया मान |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


ज्यामिति को रेंडर करने के लिए उपयोग किए जाने वाले शेडर इंस्टेंस को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | नया मान |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


सीन को रेंडर करने के लिए उपयोग किए जाने वाले शेडर सेट को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | नया मान |

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

