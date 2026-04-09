---
title: Renderer
second_title: Aspose.3D for Java API-referentie
description: De context over de renderer.
type: docs
weight: 152
url: /nl/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

De context over de renderer.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clearCache()](#clearCache--) | Maak de cache handmatig leeg. |
| [close()](#close--) | Verwijder de [Renderer](../../com.aspose.threed/renderer) en alle gerelateerde bronnen |
| [createRenderer()](#createRenderer--) | Maakt een nieuwe [Renderer](../../com.aspose.threed/renderer) met het standaardprofiel. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | Voer een nabewerking uit op het opgegeven renderdoel |
| [getAssetDirectories()](#getAssetDirectories--) | Mappen die externe assets opslaan |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Haalt op of schaduwen ingeschakeld moeten worden. |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | Haalt de fallback entity renderer op wanneer de entiteit geen speciale renderer heeft gedefinieerd. |
| [getFrustum()](#getFrustum--) | Haalt de frustum op die werd gebruikt om de viewmatrix te leveren. |
| [getMaterial()](#getMaterial--) | Haalt het materiaal op dat werd gebruikt om materiaalinformatie te leveren die door shaders wordt gebruikt. |
| [getNode()](#getNode--) | Haalt de [getNode](../../com.aspose.threed/renderer\#getNode) instantie op die wordt gebruikt om de wereldtransformatie-matrix te leveren. |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | Haalt een ingebouwde post-processor op die door de renderer wordt ondersteund. |
| [getPostProcessings()](#getPostProcessings--) | Actieve post-processing keten |
| [getPresetShaders()](#getPresetShaders--) | Haalt de vooraf ingestelde shaderset op |
| [getRenderFactory()](#getRenderFactory--) | Haalt de fabriek op om render-gerelateerde objecten te bouwen. |
| [getRenderStage()](#getRenderStage--) | Haalt de huidige renderfase op. |
| [getRenderTarget()](#getRenderTarget--) | Specificeer het renderdoel waarop de volgende renderbewerkingen worden uitgevoerd. |
| [getShader()](#getShader--) | Haalt de shaderinstantie op die wordt gebruikt voor het renderen van de geometrie. |
| [getShaderSet()](#getShaderSet--) | Haalt de shaderset op die werd gebruikt om de scène te renderen |
| [getVariables()](#getVariables--) | Toegang tot de interne variabelen die worden gebruikt voor rendering |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | Registreer de entiteitrenderer voor de opgegeven entiteit |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | Render het opgegeven doel |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Stelt in of schaduwen moeten worden ingeschakeld. |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | Stelt de fallback entity renderer in wanneer de entiteit geen speciale renderer heeft gedefinieerd. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Stelt de frustum in die werd gebruikt om de viewmatrix te leveren. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Stelt het materiaal in dat werd gebruikt om materiaalinformatie te leveren die door shaders wordt gebruikt. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Stelt de [getNode](../../com.aspose.threed/renderer\#getNode) instantie in die wordt gebruikt om de wereldtransformatie-matrix te leveren. |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | Stelt de vooraf ingestelde shaderset in |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | Stelt de shaderinstantie in die wordt gebruikt voor het renderen van de geometrie. |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | Stelt de shaderset in die werd gebruikt om de scène te renderen |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


Maak de cache handmatig leeg. Aspose.3D zal sommige objecten zoals materialen/geometrieën cachen in interne types die compatibel zijn met de renderpijplijn. Dit moet handmatig worden aangeroepen wanneer de scène grote wijzigingen ondergaat.

### close() {#close--}
```
public void close()
```


Verwijder de [Renderer](../../com.aspose.threed/renderer) en alle gerelateerde bronnen

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


Maakt een nieuwe [Renderer](../../com.aspose.threed/renderer) met het standaardprofiel.

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


Voer een nabewerking uit op het opgegeven renderdoel

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Mappen die externe assets opslaan

**Returns:**
java.util.ArrayList<java.lang.String> - Mappen die externe assets opslaan
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


Haalt op of schaduwen ingeschakeld moeten worden.

**Returns:**
boolean - of schaduwen ingeschakeld moeten worden.
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


Haalt de fallback entity renderer op wanneer de entiteit geen speciale renderer heeft gedefinieerd.

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Haalt de frustum op die werd gebruikt om de viewmatrix te leveren.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


Haalt het materiaal op dat werd gebruikt om materiaalinformatie te leveren die door shaders wordt gebruikt.

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


Haalt de [getNode](../../com.aspose.threed/renderer\#getNode) instantie op die wordt gebruikt om de wereldtransformatie-matrix te leveren.

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


Haalt een ingebouwde post-processor op die door de renderer wordt ondersteund.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


Actieve post-processing keten

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - Actieve post-processing keten
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


Haalt de vooraf ingestelde shaderset op

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


Haalt de fabriek op om render-gerelateerde objecten te bouwen.

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


Haalt de huidige renderfase op.

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Specificeer het renderdoel waarop de volgende renderbewerkingen worden uitgevoerd.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


Haalt de shaderinstantie op die wordt gebruikt voor het renderen van de geometrie.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


Haalt de shaderset op die werd gebruikt om de scène te renderen

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


Toegang tot de interne variabelen die worden gebruikt voor rendering

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


Registreer de entiteitrenderer voor de opgegeven entiteit

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


Render het opgegeven doel

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Stelt in of schaduwen moeten worden ingeschakeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


Stelt de fallback entity renderer in wanneer de entiteit geen speciale renderer heeft gedefinieerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | Nieuwe waarde |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Stelt de frustum in die werd gebruikt om de viewmatrix te leveren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Nieuwe waarde |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


Stelt het materiaal in dat werd gebruikt om materiaalinformatie te leveren die door shaders wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | Nieuwe waarde |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Stelt de [getNode](../../com.aspose.threed/renderer\#getNode) instantie in die wordt gebruikt om de wereldtransformatie-matrix te leveren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nieuwe waarde |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


Stelt de vooraf ingestelde shaderset in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | Nieuwe waarde |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


Stelt de shaderinstantie in die wordt gebruikt voor het renderen van de geometrie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nieuwe waarde |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


Stelt de shaderset in die werd gebruikt om de scène te renderen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | Nieuwe waarde |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

