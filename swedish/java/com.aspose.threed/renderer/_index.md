---
title: Renderer
second_title: Aspose.3D for Java API-referens
description: Kontexten för renderaren.
type: docs
weight: 152
url: /sv/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

Kontexten för renderaren.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clearCache()](#clearCache--) | Rensa cachen manuellt. |
| [close()](#close--) | Frigör [Renderer](../../com.aspose.threed/renderer) och alla relaterade resurser |
| [createRenderer()](#createRenderer--) | Skapar en ny [Renderer](../../com.aspose.threed/renderer) med standardprofil. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | Utför en efterbehandling på angivet renderingsmål |
| [getAssetDirectories()](#getAssetDirectories--) | Kataloger som lagrar externa resurser |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Hämtar om skuggor ska aktiveras. |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | Hämtar reserv‑entity‑renderaren när enheten inte har någon speciell renderare definierad. |
| [getFrustum()](#getFrustum--) | Hämtar frustum som användes för att tillhandahålla vy‑matrisen. |
| [getMaterial()](#getMaterial--) | Hämtar materialet som användes för att tillhandahålla materialinformation som shaders använder. |
| [getNode()](#getNode--) | Hämtar [getNode](../../com.aspose.threed/renderer\#getNode)-instansen som används för att tillhandahålla världens transformationsmatris. |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | Hämtar en inbyggd post‑processor som stöds av renderaren. |
| [getPostProcessings()](#getPostProcessings--) | Aktiv post‑processkedja |
| [getPresetShaders()](#getPresetShaders--) | Hämtar den förinställda shader‑uppsättningen |
| [getRenderFactory()](#getRenderFactory--) | Hämtar fabriken för att bygga renderingsrelaterade objekt. |
| [getRenderStage()](#getRenderStage--) | Hämtar den aktuella renderingsstadiet. |
| [getRenderTarget()](#getRenderTarget--) | Ange renderingsmålet som de följande renderingsoperationerna kommer att utföras på. |
| [getShader()](#getShader--) | Hämtar shader‑instansen som används för att rendera geometrin. |
| [getShaderSet()](#getShaderSet--) | Hämtar shader‑uppsättningen som användes för att rendera scenen |
| [getVariables()](#getVariables--) | Åtkomst till de interna variablerna som används för rendering |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | Registrera entity‑renderaren för angiven entity |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | Rendera det angivna målet |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Ställer in om skuggor ska aktiveras. |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | Ställer in reserv‑entity‑renderaren när enheten inte har någon speciell renderare definierad. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Ställer in frustum som användes för att tillhandahålla vy‑matrisen. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Ställer in materialet som användes för att tillhandahålla materialinformation som shaders använder. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Ställer in [getNode](../../com.aspose.threed/renderer\#getNode)-instansen som används för att tillhandahålla världens transformationsmatris. |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | Ställer in den förinställda shader‑uppsättningen |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | Ställer in shader‑instansen som används för att rendera geometrin. |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | Ställer in shader‑uppsättningen som användes för att rendera scenen |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


Rensa cachen manuellt. Aspose.3D kommer att cacha vissa objekt som material/geometrier i interna typer som är kompatibla med renderings‑pipeline. Detta bör anropas manuellt när scenen har större förändringar.

### close() {#close--}
```
public void close()
```


Frigör [Renderer](../../com.aspose.threed/renderer) och alla relaterade resurser

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


Skapar en ny [Renderer](../../com.aspose.threed/renderer) med standardprofil.

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


Utför en efterbehandling på angivet renderingsmål

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Kataloger som lagrar externa resurser

**Returns:**
java.util.ArrayList<java.lang.String> – Kataloger som lagrar externa resurser
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


Hämtar om skuggor ska aktiveras.

**Returns:**
boolean - whether to enable shadows.
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


Hämtar reserv‑entity‑renderaren när enheten inte har någon speciell renderare definierad.

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Hämtar frustum som användes för att tillhandahålla vy‑matrisen.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


Hämtar materialet som användes för att tillhandahålla materialinformation som shaders använder.

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


Hämtar [getNode](../../com.aspose.threed/renderer\#getNode)-instansen som används för att tillhandahålla världens transformationsmatris.

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


Hämtar en inbyggd post‑processor som stöds av renderaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


Aktiv post‑processkedja

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - Active post-processing chain
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


Hämtar den förinställda shader‑uppsättningen

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


Hämtar fabriken för att bygga renderingsrelaterade objekt.

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


Hämtar den aktuella renderingsstadiet.

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Ange renderingsmålet som de följande renderingsoperationerna kommer att utföras på.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


Hämtar shader‑instansen som används för att rendera geometrin.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


Hämtar shader‑uppsättningen som användes för att rendera scenen

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


Åtkomst till de interna variablerna som används för rendering

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


Registrera entity‑renderaren för angiven entity

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


Rendera det angivna målet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Ställer in om skuggor ska aktiveras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


Ställer in reserv‑entity‑renderaren när enheten inte har någon speciell renderare definierad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | Nytt värde |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Ställer in frustum som användes för att tillhandahålla vy‑matrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Nytt värde |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


Ställer in materialet som användes för att tillhandahålla materialinformation som shaders använder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | Nytt värde |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Ställer in [getNode](../../com.aspose.threed/renderer\#getNode)-instansen som används för att tillhandahålla världens transformationsmatris.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nytt värde |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


Ställer in den förinställda shader‑uppsättningen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | Nytt värde |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


Ställer in shader‑instansen som används för att rendera geometrin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nytt värde |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


Ställer in shader‑uppsättningen som användes för att rendera scenen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | Nytt värde |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

