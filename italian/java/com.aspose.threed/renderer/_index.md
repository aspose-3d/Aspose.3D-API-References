---
title: Renderer
second_title: Aspose.3D for Java API Reference
description: Il contesto relativo al renderer.
type: docs
weight: 152
url: /it/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

Il contesto relativo al renderer.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clearCache()](#clearCache--) | Cancella manualmente la cache. |
| [close()](#close--) | Rilascia il [Renderer](../../com.aspose.threed/renderer) e tutte le risorse correlate |
| [createRenderer()](#createRenderer--) | Crea un nuovo [Renderer](../../com.aspose.threed/renderer) con profilo predefinito. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | Esegui un post‑processing sul target di rendering specificato |
| [getAssetDirectories()](#getAssetDirectories--) | Directory che memorizzano risorse esterne |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Ottiene se abilitare le ombre. |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | Ottiene il renderer di entità di fallback quando l'entità non ha un renderer speciale definito. |
| [getFrustum()](#getFrustum--) | Ottiene il frustum che veniva usato per fornire la matrice di visualizzazione. |
| [getMaterial()](#getMaterial--) | Ottiene il materiale che veniva usato per fornire le informazioni sui materiali utilizzate dagli shader. |
| [getNode()](#getNode--) | Ottiene l'istanza [getNode](../../com.aspose.threed/renderer\#getNode) usata per fornire la matrice di trasformazione del mondo. |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | Ottiene un post-processore integrato supportato dal renderer. |
| [getPostProcessings()](#getPostProcessings--) | Catena di post-elaborazione attiva |
| [getPresetShaders()](#getPresetShaders--) | Ottiene il set di shader predefinito |
| [getRenderFactory()](#getRenderFactory--) | Ottiene la factory per creare oggetti relativi al rendering. |
| [getRenderStage()](#getRenderStage--) | Ottiene lo stadio di rendering corrente. |
| [getRenderTarget()](#getRenderTarget--) | Specifica il target di rendering su cui verranno eseguite le successive operazioni di rendering. |
| [getShader()](#getShader--) | Ottiene l'istanza dello shader usata per il rendering della geometria. |
| [getShaderSet()](#getShaderSet--) | Ottiene il set di shader usato per renderizzare la scena |
| [getVariables()](#getVariables--) | Accesso alle variabili interne usate per il rendering |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | Registra il renderer di entità per l'entità specificata |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | Renderizza il target specificato |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Imposta se abilitare le ombre. |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | Imposta il renderer di entità di fallback quando l'entità non ha un renderer speciale definito. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Imposta il frustum che veniva usato per fornire la matrice di visualizzazione. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Imposta il materiale che veniva usato per fornire le informazioni sui materiali utilizzate dagli shader. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Imposta l'istanza [getNode](../../com.aspose.threed/renderer\#getNode) usata per fornire la matrice di trasformazione del mondo. |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | Imposta il set di shader predefinito |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | Imposta l'istanza dello shader usata per il rendering della geometria. |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | Imposta il set di shader usato per renderizzare la scena |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


Cancella manualmente la cache. Aspose.3D memorizzerà nella cache alcuni oggetti come materiali/geometrie in tipi interni compatibili con la pipeline di rendering. Questo dovrebbe essere chiamato manualmente quando la scena subisce modifiche importanti.

### close() {#close--}
```
public void close()
```


Rilascia il [Renderer](../../com.aspose.threed/renderer) e tutte le risorse correlate

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


Crea un nuovo [Renderer](../../com.aspose.threed/renderer) con profilo predefinito.

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


Esegui un post‑processing sul target di rendering specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Directory che memorizzano risorse esterne

**Returns:**
java.util.ArrayList<java.lang.String> - Directory che memorizzano risorse esterne
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


Ottiene se abilitare le ombre.

**Returns:**
boolean - se abilitare le ombre.
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


Ottiene il renderer di entità di fallback quando l'entità non ha un renderer speciale definito.

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Ottiene il frustum che veniva usato per fornire la matrice di visualizzazione.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


Ottiene il materiale che veniva usato per fornire le informazioni sui materiali utilizzate dagli shader.

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


Ottiene l'istanza [getNode](../../com.aspose.threed/renderer\#getNode) usata per fornire la matrice di trasformazione del mondo.

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


Ottiene un post-processore integrato supportato dal renderer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


Catena di post-elaborazione attiva

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - Catena di post-elaborazione attiva
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


Ottiene il set di shader predefinito

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


Ottiene la factory per creare oggetti relativi al rendering.

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


Ottiene lo stadio di rendering corrente.

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Specifica il target di rendering su cui verranno eseguite le successive operazioni di rendering.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


Ottiene l'istanza dello shader usata per il rendering della geometria.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


Ottiene il set di shader usato per renderizzare la scena

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


Accesso alle variabili interne usate per il rendering

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


Registra il renderer di entità per l'entità specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


Renderizza il target specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Imposta se abilitare le ombre.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


Imposta il renderer di entità di fallback quando l'entità non ha un renderer speciale definito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | Nuovo valore |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Imposta il frustum che veniva usato per fornire la matrice di visualizzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Nuovo valore |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


Imposta il materiale che veniva usato per fornire le informazioni sui materiali utilizzate dagli shader.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | Nuovo valore |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Imposta l'istanza [getNode](../../com.aspose.threed/renderer\#getNode) usata per fornire la matrice di trasformazione del mondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuovo valore |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


Imposta il set di shader predefinito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | Nuovo valore |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


Imposta l'istanza dello shader usata per il rendering della geometria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nuovo valore |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


Imposta il set di shader usato per renderizzare la scena

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | Nuovo valore |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

