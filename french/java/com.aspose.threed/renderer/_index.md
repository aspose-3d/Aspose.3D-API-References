---
title: "Renderer"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le contexte concernant le moteur de rendu."
type: docs
weight: 152
url: /fr/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

Le contexte concernant le moteur de rendu.
## Méthodes

| Méthode | Description |
| --- | --- |
| [clearCache()](#clearCache--) | Effacez manuellement le cache. |
| [close()](#close--) | Libérez le [Renderer](../../com.aspose.threed/renderer) et toutes les ressources associées |
| [createRenderer()](#createRenderer--) | Crée un nouveau [Renderer](../../com.aspose.threed/renderer) avec le profil par défaut. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | Exécutez un post-traitement sur la cible de rendu spécifiée |
| [getAssetDirectories()](#getAssetDirectories--) | Répertoires qui stockent les ressources externes |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Obtient si les ombres sont activées. |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | Obtient le rendu d'entité de secours lorsque l'entité n'a aucun rendu spécial défini. |
| [getFrustum()](#getFrustum--) | Obtient le frustum qui était utilisé pour fournir la matrice de vue. |
| [getMaterial()](#getMaterial--) | Obtient le matériau qui était utilisé pour fournir les informations de matériau utilisées par les shaders. |
| [getNode()](#getNode--) | Obtient l'instance [getNode](../../com.aspose.threed/renderer\\#getNode) utilisée pour fournir la matrice de transformation du monde. |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | Obtient un post-processeur intégré pris en charge par le renderer. |
| [getPostProcessings()](#getPostProcessings--) | Chaîne de post-traitement active |
| [getPresetShaders()](#getPresetShaders--) | Obtient l'ensemble de shaders prédéfini |
| [getRenderFactory()](#getRenderFactory--) | Obtient la fabrique permettant de créer les objets liés au rendu. |
| [getRenderStage()](#getRenderStage--) | Obtient l'étape de rendu actuelle. |
| [getRenderTarget()](#getRenderTarget--) | Spécifiez la cible de rendu sur laquelle les opérations de rendu suivantes seront effectuées. |
| [getShader()](#getShader--) | Obtient l'instance du shader utilisée pour le rendu de la géométrie. |
| [getShaderSet()](#getShaderSet--) | Obtient l'ensemble de shaders utilisé pour rendre la scène |
| [getVariables()](#getVariables--) | Accès aux variables internes utilisées pour le rendu |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | Enregistrez le rendu d'entité pour l'entité spécifiée |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | Rendre la cible spécifiée |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Définit si les ombres doivent être activées. |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | Définit le rendu d'entité de secours lorsque l'entité n'a aucun rendu spécial défini. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Définit le frustum qui était utilisé pour fournir la matrice de vue. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Définit le matériau qui était utilisé pour fournir les informations de matériau utilisées par les shaders. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Définit l'instance [getNode](../../com.aspose.threed/renderer\\#getNode) utilisée pour fournir la matrice de transformation du monde. |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | Définit l'ensemble de shaders prédéfini |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | Définit l'instance du shader utilisée pour le rendu de la géométrie. |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | Définit l'ensemble de shaders utilisé pour rendre la scène |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


Effacez manuellement le cache. Aspose.3D met en cache certains objets comme les matériaux/géométries dans des types internes compatibles avec le pipeline de rendu. Cela doit être appelé manuellement lorsque la scène subit des changements majeurs.

### close() {#close--}
```
public void close()
```


Libérez le [Renderer](../../com.aspose.threed/renderer) et toutes les ressources associées

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


Crée un nouveau [Renderer](../../com.aspose.threed/renderer) avec le profil par défaut.

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


Exécutez un post-traitement sur la cible de rendu spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Répertoires qui stockent les ressources externes

**Returns:**
java.util.ArrayList<java.lang.String> - Répertoires qui stockent des ressources externes
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


Obtient si les ombres sont activées.

**Returns:**
boolean - indique si les ombres doivent être activées.
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


Obtient le rendu d'entité de secours lorsque l'entité n'a aucun rendu spécial défini.

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Obtient le frustum qui était utilisé pour fournir la matrice de vue.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


Obtient le matériau qui était utilisé pour fournir les informations de matériau utilisées par les shaders.

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


Obtient l'instance [getNode](../../com.aspose.threed/renderer\\#getNode) utilisée pour fournir la matrice de transformation du monde.

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


Obtient un post-processeur intégré pris en charge par le renderer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


Chaîne de post-traitement active

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - Chaîne de post-traitement active
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


Obtient l'ensemble de shaders prédéfini

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


Obtient la fabrique permettant de créer les objets liés au rendu.

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


Obtient l'étape de rendu actuelle.

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Spécifiez la cible de rendu sur laquelle les opérations de rendu suivantes seront effectuées.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


Obtient l'instance du shader utilisée pour le rendu de la géométrie.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


Obtient l'ensemble de shaders utilisé pour rendre la scène

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


Accès aux variables internes utilisées pour le rendu

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


Enregistrez le rendu d'entité pour l'entité spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


Rendre la cible spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Définit si les ombres doivent être activées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


Définit le rendu d'entité de secours lorsque l'entité n'a aucun rendu spécial défini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | Nouvelle valeur |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Définit le frustum qui était utilisé pour fournir la matrice de vue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Nouvelle valeur |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


Définit le matériau qui était utilisé pour fournir les informations de matériau utilisées par les shaders.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | Nouvelle valeur |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Définit l'instance [getNode](../../com.aspose.threed/renderer\\#getNode) utilisée pour fournir la matrice de transformation du monde.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nouvelle valeur |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


Définit l'ensemble de shaders prédéfini

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | Nouvelle valeur |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


Définit l'instance du shader utilisée pour le rendu de la géométrie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nouvelle valeur |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


Définit l'ensemble de shaders utilisé pour rendre la scène

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | Nouvelle valeur |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

