---
title: Renderer
second_title: Справочник API Aspose.3D для Java
description: Контекст, относящийся к рендереру.
type: docs
weight: 152
url: /ru/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

Контекст, относящийся к рендереру.
## Методы

| Метод | Описание |
| --- | --- |
| [clearCache()](#clearCache--) | Очистите кэш вручную. |
| [close()](#close--) | Освободите [Renderer](../../com.aspose.threed/renderer) и все связанные ресурсы |
| [createRenderer()](#createRenderer--) | Создаёт новый [Renderer](../../com.aspose.threed/renderer) с профилем по умолчанию. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | Выполнить постобработку указанной цели рендеринга |
| [getAssetDirectories()](#getAssetDirectories--) | Каталоги, в которых хранятся внешние ресурсы. |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Получает, включены ли тени. |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | Получает резервный рендерер сущности, когда у сущности не определён специальный рендерер. |
| [getFrustum()](#getFrustum--) | Получает фрустум, который использовался для предоставления матрицы просмотра. |
| [getMaterial()](#getMaterial--) | Получает материал, который использовался для предоставления информации о материале, используемой шейдерами. |
| [getNode()](#getNode--) | Получает экземпляр [getNode](../../com.aspose.threed/renderer\#getNode), используемый для предоставления матрицы мирового преобразования. |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | Получает встроенный пост‑процессор, поддерживаемый рендерером. |
| [getPostProcessings()](#getPostProcessings--) | Активная цепочка пост‑обработки |
| [getPresetShaders()](#getPresetShaders--) | Получает предустановленный набор шейдеров |
| [getRenderFactory()](#getRenderFactory--) | Получает фабрику для создания объектов, связанных с рендерингом. |
| [getRenderStage()](#getRenderStage--) | Получает текущий этап рендеринга. |
| [getRenderTarget()](#getRenderTarget--) | Укажите целевой объект рендеринга, на котором будут выполнены последующие операции рендеринга. |
| [getShader()](#getShader--) | Получает экземпляр шейдера, используемый для рендеринга геометрии. |
| [getShaderSet()](#getShaderSet--) | Получает набор шейдеров, который использовался для рендеринга сцены |
| [getVariables()](#getVariables--) | Доступ к внутренним переменным, используемым для рендеринга |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | Зарегистрировать рендерер сущности для указанной сущности |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | Выполнить рендеринг указанного целевого объекта |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Устанавливает, включать ли тени. |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | Устанавливает резервный рендерер сущности, когда у сущности не определён специальный рендерер. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Устанавливает фрустум, который использовался для предоставления матрицы просмотра. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Устанавливает материал, который использовался для предоставления информации о материале, используемой шейдерами. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Устанавливает экземпляр [getNode](../../com.aspose.threed/renderer\#getNode), используемый для предоставления матрицы мирового преобразования. |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | Устанавливает предустановленный набор шейдеров |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | Устанавливает экземпляр шейдера, используемый для рендеринга геометрии. |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | Устанавливает набор шейдеров, который использовался для рендеринга сцены |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


Вручную очистить кэш. Aspose.3D кэширует некоторые объекты, такие как материалы/геометрии, во внутренние типы, совместимые с конвейером рендеринга. Это следует вызывать вручную, когда в сцене происходят значительные изменения.

### close() {#close--}
```
public void close()
```


Освободите [Renderer](../../com.aspose.threed/renderer) и все связанные ресурсы

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


Создаёт новый [Renderer](../../com.aspose.threed/renderer) с профилем по умолчанию.

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


Выполнить постобработку указанной цели рендеринга

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Каталоги, в которых хранятся внешние ресурсы.

**Returns:**
java.util.ArrayList<java.lang.String> - Каталоги, в которых хранятся внешние ресурсы
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


Получает, включены ли тени.

**Returns:**
boolean - включать тени или нет.
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


Получает резервный рендерер сущности, когда у сущности не определён специальный рендерер.

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Получает фрустум, который использовался для предоставления матрицы просмотра.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


Получает материал, который использовался для предоставления информации о материале, используемой шейдерами.

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


Получает экземпляр [getNode](../../com.aspose.threed/renderer\#getNode), используемый для предоставления матрицы мирового преобразования.

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


Получает встроенный пост‑процессор, поддерживаемый рендерером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


Активная цепочка пост‑обработки

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - Активная цепочка постобработки
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


Получает предустановленный набор шейдеров

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


Получает фабрику для создания объектов, связанных с рендерингом.

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


Получает текущий этап рендеринга.

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Укажите целевой объект рендеринга, на котором будут выполнены последующие операции рендеринга.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


Получает экземпляр шейдера, используемый для рендеринга геометрии.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


Получает набор шейдеров, который использовался для рендеринга сцены

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


Доступ к внутренним переменным, используемым для рендеринга

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


Зарегистрировать рендерер сущности для указанной сущности

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


Выполнить рендеринг указанного целевого объекта

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Устанавливает, включать ли тени.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


Устанавливает резервный рендерер сущности, когда у сущности не определён специальный рендерер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | Новое значение |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Устанавливает фрустум, который использовался для предоставления матрицы просмотра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Новое значение |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


Устанавливает материал, который использовался для предоставления информации о материале, используемой шейдерами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | Новое значение |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Устанавливает экземпляр [getNode](../../com.aspose.threed/renderer\#getNode), используемый для предоставления матрицы мирового преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Новое значение |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


Устанавливает предустановленный набор шейдеров

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | Новое значение |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


Устанавливает экземпляр шейдера, используемый для рендеринга геометрии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Новое значение |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


Устанавливает набор шейдеров, который использовался для рендеринга сцены

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | Новое значение |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

