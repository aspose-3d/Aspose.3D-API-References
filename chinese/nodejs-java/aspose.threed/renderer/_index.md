---
title: "渲染器"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/renderer/
---
## Renderer class

关于渲染器的上下文。  @hideconstructor


## 方法

### getShaderSet{#getShaderSet}

| 名称 | 描述 |
| --- | --- |
| getShaderSet() | 获取或设置用于渲染场景的着色器集合 |

 **Result:**



---


### setShaderSet{#setShaderSet}

| 名称 | 描述 |
| --- | --- |
| setShaderSet(value) | 获取或设置用于渲染场景的着色器集合 |

 **Result:**



---


### getVariables{#getVariables}

| 名称 | 描述 |
| --- | --- |
| getVariables() | 访问用于渲染的内部变量 |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| 名称 | 描述 |
| --- | --- |
| getPresetShaders() | 获取或设置预设着色器集合。属性的值是 PresetShaders 整数常量。 |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| 名称 | 描述 |
| --- | --- |
| setPresetShaders(value) | 获取或设置预设着色器集合。属性的值是 PresetShaders 整数常量。 |

 **Result:**



---


### getRenderFactory{#getRenderFactory}

| 名称 | 描述 |
| --- | --- |
| getRenderFactory() | 获取用于构建渲染相关对象的工厂。 |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| 名称 | 描述 |
| --- | --- |
| getAssetDirectories() | 存放外部资源的目录 |

 **Result:**



---


### getPostProcessings{#getPostProcessings}

| 名称 | 描述 |
| --- | --- |
| getPostProcessings() | 活动的后处理链 |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| 名称 | 描述 |
| --- | --- |
| getEnableShadows() | 获取或设置是否启用阴影。 |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| 名称 | 描述 |
| --- | --- |
| setEnableShadows(value) | 获取或设置是否启用阴影。 |

 **Result:**



---


### getRenderTarget{#getRenderTarget}

| 名称 | 描述 |
| --- | --- |
| getRenderTarget() | 指定后续渲染操作将执行的渲染目标。 |

 **Result:**



---


### getNode{#getNode}

| 名称 | 描述 |
| --- | --- |
| getNode() | 获取或设置用于提供世界变换矩阵的 Node 实例。 |

 **Result:**



---


### setNode{#setNode}

| 名称 | 描述 |
| --- | --- |
| setNode(value) | 获取或设置用于提供世界变换矩阵的 Node 实例。 |

 **Result:**



---


### getFrustum{#getFrustum}

| 名称 | 描述 |
| --- | --- |
| getFrustum() | 获取或设置用于提供视图矩阵的视锥体。 |

 **Result:**



---


### setFrustum{#setFrustum}

| 名称 | 描述 |
| --- | --- |
| setFrustum(value) | 获取或设置用于提供视图矩阵的视锥体。 |

 **Result:**



---


### getRenderStage{#getRenderStage}

| 名称 | 描述 |
| --- | --- |
| getRenderStage() | 获取当前渲染阶段。属性的值是 RenderStage 整数常量。 |

 **Result:**



---


### getMaterial{#getMaterial}

| 名称 | 描述 |
| --- | --- |
| getMaterial() | 获取或设置用于提供着色器使用的材质信息的材质。 |

 **Result:**



---


### setMaterial{#setMaterial}

| 名称 | 描述 |
| --- | --- |
| setMaterial(value) | 获取或设置用于提供着色器使用的材质信息的材质。 |

 **Result:**



---


### getShader{#getShader}

| 名称 | 描述 |
| --- | --- |
| getShader() | 获取或设置用于渲染几何体的着色器实例。 |

 **Result:**



---


### setShader{#setShader}

| 名称 | 描述 |
| --- | --- |
| setShader(value) | 获取或设置用于渲染几何体的着色器实例。 |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| 名称 | 描述 |
| --- | --- |
| getFallbackEntityRenderer() | 获取或设置当实体未定义特殊渲染器时的回退实体渲染器。 |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| 名称 | 描述 |
| --- | --- |
| setFallbackEntityRenderer(value) | 获取或设置当实体未定义特殊渲染器时的回退实体渲染器。 |

 **Result:**



---


### clearCache{#clearCache}

| 名称 | 描述 |
| --- | --- |
| clearCache() | 手动清除缓存。Aspose.3D 会将一些对象（如材质/几何体）缓存到与渲染管线兼容的内部类型中。当场景发生重大更改时应手动调用此方法。 |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| 名称 | 描述 |
| --- | --- |
| getPostProcessing(name) | 获取渲染器支持的内置后处理器。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| nam | 字符串 | null |

 **Result:**
后处理


---


### execute{#execute}

| 名称 | 描述 |
| --- | --- |
| execute(postProcessing, result) | 在指定的渲染目标上执行后处理。 |

 **Result:**
后处理


---


### createRenderer{#createRenderer}

| 名称 | 描述 |
| --- | --- |
| createRenderer() | 创建一个具有默认配置文件的新 Renderer。 |

 **Result:**
渲染器


---


### registerEntityRenderer{#registerEntityRenderer}

| 名称 | 描述 |
| --- | --- |
| registerEntityRenderer(renderer) | 为指定实体注册 entity renderer |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rendere | EntityRenderer | null |

 **Result:**
渲染器


---


### render{#render}

| 名称 | 描述 |
| --- | --- |
| render(renderTarget) | 渲染指定的目标 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
渲染器


---



