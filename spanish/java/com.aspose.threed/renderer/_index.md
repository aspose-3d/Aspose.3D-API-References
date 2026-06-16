---
title: Renderer
second_title: Referencia de API de Aspose.3D para Java
description: El contexto del renderizador.
type: docs
weight: 152
url: /es/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

El contexto del renderizador.
## Métodos

| Método | Descripción |
| --- | --- |
| [clearCache()](#clearCache--) | Borre la caché manualmente. |
| [close()](#close--) | Deseche el [Renderer](../../com.aspose.threed/renderer) y todos los recursos relacionados. |
| [createRenderer()](#createRenderer--) | Crea un nuevo [Renderer](../../com.aspose.threed/renderer) con el perfil predeterminado. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | Ejecute un postprocesamiento en el objetivo de renderizado especificado |
| [getAssetDirectories()](#getAssetDirectories--) | Directorios que almacenan recursos externos. |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Obtiene si se deben habilitar las sombras. |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | Obtiene el renderizador de entidad de reserva cuando la entidad no tiene un renderizador especial definido. |
| [getFrustum()](#getFrustum--) | Obtiene el frustum que se utilizó para proporcionar la matriz de vista. |
| [getMaterial()](#getMaterial--) | Obtiene el material que se utilizó para proporcionar la información del material usada por los shaders. |
| [getNode()](#getNode--) | Obtiene la instancia de [getNode](../../com.aspose.threed/renderer\#getNode) utilizada para proporcionar la matriz de transformación del mundo. |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | Obtiene un postprocesador incorporado que es compatible con el renderizador. |
| [getPostProcessings()](#getPostProcessings--) | Cadena de postprocesamiento activa |
| [getPresetShaders()](#getPresetShaders--) | Obtiene el conjunto de shaders preestablecido |
| [getRenderFactory()](#getRenderFactory--) | Obtiene la fábrica para crear objetos relacionados con el renderizado. |
| [getRenderStage()](#getRenderStage--) | Obtiene la etapa de renderizado actual. |
| [getRenderTarget()](#getRenderTarget--) | Especifique el objetivo de renderizado en el que se realizarán las siguientes operaciones de renderizado. |
| [getShader()](#getShader--) | Obtiene la instancia del shader utilizada para renderizar la geometría. |
| [getShaderSet()](#getShaderSet--) | Obtiene el conjunto de shaders que se utilizó para renderizar la escena |
| [getVariables()](#getVariables--) | Acceso a las variables internas utilizadas para el renderizado |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | Registre el renderizador de entidad para la entidad especificada |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | Renderiza el objetivo especificado |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Establece si se habilitan las sombras. |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | Establece el renderizador de entidad de reserva cuando la entidad no tiene un renderizador especial definido. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Establece el frustum que se utilizó para proporcionar la matriz de vista. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Establece el material que se utilizó para proporcionar la información del material usada por los shaders. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Establece la instancia de [getNode](../../com.aspose.threed/renderer\#getNode) utilizada para proporcionar la matriz de transformación del mundo. |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | Establece el conjunto de shaders preestablecido |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | Establece la instancia del shader utilizada para renderizar la geometría. |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | Establece el conjunto de shaders que se utilizó para renderizar la escena |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


Borre manualmente la caché. Aspose.3D almacenará en caché algunos objetos como materiales/geometrías en tipos internos compatibles con la canalización de renderizado. Esto debe llamarse manualmente cuando la escena tenga cambios importantes.

### close() {#close--}
```
public void close()
```


Deseche el [Renderer](../../com.aspose.threed/renderer) y todos los recursos relacionados.

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


Crea un nuevo [Renderer](../../com.aspose.threed/renderer) con el perfil predeterminado.

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


Ejecute un postprocesamiento en el objetivo de renderizado especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Directorios que almacenan recursos externos.

**Returns:**
java.util.ArrayList<java.lang.String> - Directorios que almacenan activos externos
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


Obtiene si se deben habilitar las sombras.

**Returns:**
boolean - si se habilitan sombras.
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


Obtiene el renderizador de entidad de reserva cuando la entidad no tiene un renderizador especial definido.

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Obtiene el frustum que se utilizó para proporcionar la matriz de vista.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


Obtiene el material que se utilizó para proporcionar la información del material usada por los shaders.

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


Obtiene la instancia de [getNode](../../com.aspose.threed/renderer\#getNode) utilizada para proporcionar la matriz de transformación del mundo.

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


Obtiene un postprocesador incorporado que es compatible con el renderizador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


Cadena de postprocesamiento activa

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - Cadena de post-procesamiento activa
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


Obtiene el conjunto de shaders preestablecido

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


Obtiene la fábrica para crear objetos relacionados con el renderizado.

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


Obtiene la etapa de renderizado actual.

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Especifique el objetivo de renderizado en el que se realizarán las siguientes operaciones de renderizado.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


Obtiene la instancia del shader utilizada para renderizar la geometría.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


Obtiene el conjunto de shaders que se utilizó para renderizar la escena

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


Acceso a las variables internas utilizadas para el renderizado

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


Registre el renderizador de entidad para la entidad especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


Renderiza el objetivo especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Establece si se habilitan las sombras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


Establece el renderizador de entidad de reserva cuando la entidad no tiene un renderizador especial definido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | Nuevo valor |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Establece el frustum que se utilizó para proporcionar la matriz de vista.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Nuevo valor |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


Establece el material que se utilizó para proporcionar la información del material usada por los shaders.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | Nuevo valor |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Establece la instancia de [getNode](../../com.aspose.threed/renderer\#getNode) utilizada para proporcionar la matriz de transformación del mundo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuevo valor |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


Establece el conjunto de shaders preestablecido

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | Nuevo valor |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


Establece la instancia del shader utilizada para renderizar la geometría.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nuevo valor |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


Establece el conjunto de shaders que se utilizó para renderizar la escena

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | Nuevo valor |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

