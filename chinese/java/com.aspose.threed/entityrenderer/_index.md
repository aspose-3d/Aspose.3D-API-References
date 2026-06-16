---
title: "EntityRenderer"
second_title: "Aspose.3D for Java API 参考"
description: "子类化此类以实现对不同类型实体的渲染。"
type: docs
weight: 53
url: /zh/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

子类化此类以实现对不同类型实体的渲染。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | [EntityRenderer](../../com.aspose.threed/entityrenderer) 的构造函数 |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | [EntityRenderer](../../com.aspose.threed/entityrenderer) 的构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [dispose()](#dispose--) | 实体渲染器正在释放，释放共享资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | 开始渲染帧 |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | 结束渲染帧 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | 初始化实体渲染器 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | 为指定的节点/实体对准备渲染命令。 |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | 推送到 [IRenderQueue](../../com.aspose.threed/irenderqueue) 的每个渲染任务都将有相应的 RenderEntity 调用来执行具体的渲染工作。 |
| [resetSceneCache()](#resetSceneCache--) | 场景已更改或移除，需要在此处释放场景级别的渲染资源 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


[EntityRenderer](../../com.aspose.threed/entityrenderer) 的构造函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 实体渲染器的键 |
| 特性 | 字节 | 实体渲染器的额外特性 |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


[EntityRenderer](../../com.aspose.threed/entityrenderer) 的构造函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 实体渲染器的键 |

### dispose() {#dispose--}
```
public void dispose()
```


实体渲染器正在释放，释放共享资源。

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
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


开始渲染帧

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 当前渲染器 |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | 渲染队列 |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


结束渲染帧

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 当前渲染器 |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | 渲染队列 |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initialize(Renderer renderer) {#initialize-com.aspose.threed.Renderer-}
```
public void initialize(Renderer renderer)
```


初始化实体渲染器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity) {#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-}
```
public void prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)
```


为指定的节点/实体对准备渲染命令。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 当前渲染器实例 |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | 用于管理渲染任务的渲染队列 |
| node | [Node](../../com.aspose.threed/node) | 当前节点 |
| entity | [Entity](../../com.aspose.threed/entity) | 需要渲染的实体 |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


推送到 [IRenderQueue](../../com.aspose.threed/irenderqueue) 的每个渲染任务都将有相应的 RenderEntity 调用来执行具体的渲染工作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 渲染器 |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | 用于记录渲染指令的 commandList |
| node | [Node](../../com.aspose.threed/node) | 传递给即将渲染的实体的 PrepareRenderQueue 的相同节点 |
| renderableResource | java.lang.Object | 在 PrepareRenderQueue 期间传递给 IRenderQueue 的自定义对象 |
| subEntity | int | 传递给 IRenderQueue 的子实体的索引 |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


场景已更改或移除，需要在此处释放场景级别的渲染资源

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

