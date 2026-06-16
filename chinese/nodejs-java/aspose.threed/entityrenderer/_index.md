---
title: "EntityRenderer"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

子类化此类以实现不同类型实体的渲染。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(key, features) | EntityRenderer 的构造函数 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| key | 字符串 | 实体渲染器的键 |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(key) | EntityRenderer 的构造函数 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| key | 字符串 | 实体渲染器的键 |

 **Result:**



---


### initialize{#initialize}

| 名称 | 描述 |
| --- | --- |
| initialize(renderer) | 初始化实体渲染器 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rendere | 渲染器 | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| 名称 | 描述 |
| --- | --- |
| resetSceneCache() | 场景已更改或被移除，需要在此处释放场景级别的渲染资源 |

 **Result:**



---


### frameBegin{#frameBegin}

| 名称 | 描述 |
| --- | --- |
| frameBegin(renderer, renderQueue) | 开始渲染帧 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 渲染器 | 渲染器 | 当前渲染器 |
| renderQueue | IRenderQueue | 渲染队列 |

 **Result:**



---


### frameEnd{#frameEnd}

| 名称 | 描述 |
| --- | --- |
| frameEnd(renderer, renderQueue) | 结束渲染帧 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 渲染器 | 渲染器 | 当前渲染器 |
| renderQueue | IRenderQueue | 渲染队列 |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| 名称 | 描述 |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | 为指定的节点/实体对准备渲染命令。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 渲染器 | 渲染器 | 当前渲染器实例 |
| 队列 | IRenderQueue | 用于管理渲染任务的渲染队列 |
| 节点 | 节点 | 当前节点 |
| 实体 | 实体 | 需要渲染的实体 |

 **Result:**



---


### renderEntity{#renderEntity}

| 名称 | 描述 |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | 每个推送到 com.aspose.threed.IRenderQueue 的渲染任务都会有相应的 RenderEntity 调用来执行具体的渲染工作。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 渲染器 | 渲染器 | 渲染器 |
| commandList | ICommandList | 用于记录渲染命令的 commandList |
| 节点 | 节点 | 传递给将要渲染的实体的 PrepareRenderQueue 的相同节点 |
| renderableResource | 对象 | 在 PrepareRenderQueue 期间传递给 IRenderQueue 的自定义对象 |
| subEntity | 数字 | 传递给 IRenderQueue 的子实体的索引 |

 **Result:**



---


### dispose{#dispose}

| 名称 | 描述 |
| --- | --- |
| dispose() | 实体渲染器正在被释放，请释放共享资源。 |

 **Result:**



---



