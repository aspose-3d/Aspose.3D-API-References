---
title: "Renderer"
second_title: "Aspose.3D for Java API 参考"
description: "关于渲染器的上下文。"
type: docs
weight: 152
url: /zh/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

关于渲染器的上下文。
## 方法

| 方法 | 描述 |
| --- | --- |
| [clearCache()](#clearCache--) | 手动清除缓存。 |
| [close()](#close--) | 释放 [Renderer](../../com.aspose.threed/renderer) 并释放所有相关资源 |
| [createRenderer()](#createRenderer--) | 创建一个使用默认配置文件的新 [Renderer](../../com.aspose.threed/renderer)。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | 在指定的渲染目标上执行后处理 |
| [getAssetDirectories()](#getAssetDirectories--) | 存储外部资源的目录 |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | 获取是否启用阴影。 |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | 获取在实体未定义特殊渲染器时的回退实体渲染器。 |
| [getFrustum()](#getFrustum--) | 获取用于提供视图矩阵的视锥体。 |
| [getMaterial()](#getMaterial--) | 获取用于向着色器提供材质信息的材质。 |
| [getNode()](#getNode--) | 获取用于提供世界变换矩阵的 [getNode](../../com.aspose.threed/renderer\#getNode) 实例。 |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | 获取渲染器支持的内置后处理器。 |
| [getPostProcessings()](#getPostProcessings--) | 激活的后处理链 |
| [getPresetShaders()](#getPresetShaders--) | 获取预设着色器集合 |
| [getRenderFactory()](#getRenderFactory--) | 获取用于构建渲染相关对象的工厂。 |
| [getRenderStage()](#getRenderStage--) | 获取当前渲染阶段。 |
| [getRenderTarget()](#getRenderTarget--) | 指定后续渲染操作将执行的渲染目标。 |
| [getShader()](#getShader--) | 获取用于渲染几何体的着色器实例。 |
| [getShaderSet()](#getShaderSet--) | 获取用于渲染场景的着色器集合。 |
| [getVariables()](#getVariables--) | 访问用于渲染的内部变量 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | 为指定实体注册实体渲染器 |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | 渲染指定的目标 |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | 设置是否启用阴影。 |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | 设置在实体未定义特殊渲染器时的回退实体渲染器。 |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | 设置用于提供视图矩阵的视锥体。 |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | 设置用于向着色器提供材质信息的材质。 |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | 设置用于提供世界变换矩阵的 [getNode](../../com.aspose.threed/renderer\#getNode) 实例。 |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | 设置预设着色器集合 |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | 设置用于渲染几何体的着色器实例。 |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | 设置用于渲染场景的着色器集合。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


手动清除缓存。Aspose.3D 会将材质/几何体等对象缓存到与渲染管线兼容的内部类型中。当场景出现重大更改时应手动调用此方法。

### close() {#close--}
```
public void close()
```


释放 [Renderer](../../com.aspose.threed/renderer) 并释放所有相关资源

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


创建一个使用默认配置文件的新 [Renderer](../../com.aspose.threed/renderer)。

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


在指定的渲染目标上执行后处理

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


存储外部资源的目录

**Returns:**
java.util.ArrayList<java.lang.String> - 存储外部资源的目录
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


获取是否启用阴影。

**Returns:**
boolean - 是否启用阴影。
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


获取在实体未定义特殊渲染器时的回退实体渲染器。

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


获取用于提供视图矩阵的视锥体。

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


获取用于向着色器提供材质信息的材质。

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


获取用于提供世界变换矩阵的 [getNode](../../com.aspose.threed/renderer\#getNode) 实例。

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


获取渲染器支持的内置后处理器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


激活的后处理链

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - 活动的后处理链
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


获取预设着色器集合

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


获取用于构建渲染相关对象的工厂。

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


获取当前渲染阶段。

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


指定后续渲染操作将执行的渲染目标。

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


获取用于渲染几何体的着色器实例。

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


获取用于渲染场景的着色器集合。

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


访问用于渲染的内部变量

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


为指定实体注册实体渲染器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


渲染指定的目标

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


设置是否启用阴影。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


设置在实体未定义特殊渲染器时的回退实体渲染器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | 新值 |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


设置用于提供视图矩阵的视锥体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | 新值 |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


设置用于向着色器提供材质信息的材质。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | 新值 |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


设置用于提供世界变换矩阵的 [getNode](../../com.aspose.threed/renderer\#getNode) 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新值 |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


设置预设着色器集合

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | 新值 |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


设置用于渲染几何体的着色器实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 新值 |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


设置用于渲染场景的着色器集合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | 新值 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

