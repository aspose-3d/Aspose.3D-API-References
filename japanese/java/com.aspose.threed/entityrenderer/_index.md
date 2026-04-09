---
title: EntityRenderer
second_title: Aspose.3D for Java API リファレンス
description: これをサブクラス化して、さまざまな種類のエンティティのレンダリングを実装します。
type: docs
weight: 53
url: /ja/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

これをサブクラス化して、さまざまな種類のエンティティのレンダリングを実装します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | Constructor of [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | Constructor of [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## Methods

| Method | 説明 |
| --- | --- |
| [dispose()](#dispose--) | The entity renderer is being disposed, release shared resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Begin rendering a frame |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Ends rendering a frame |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | Initialize the entity renderer |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | Prepare rendering commands for specified node/entity pair. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | Each render task pushed to the [IRenderQueue](../../com.aspose.threed/irenderqueue) will have a corresponding RenderEntity call to perform the concrete rendering job. |
| [resetSceneCache()](#resetSceneCache--) | The scene has changed or removed, need to dispose scene-level render resources in this |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


Constructor of [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| キー | java.lang.String | エンティティレンダラーのキー |
| 機能 | バイト | エンティティレンダラーの追加機能 |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


Constructor of [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| キー | java.lang.String | エンティティレンダラーのキー |

### dispose() {#dispose--}
```
public void dispose()
```


The entity renderer is being disposed, release shared resources.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


Begin rendering a frame

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 現在のレンダラー |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | レンダーキュー |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Ends rendering a frame

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 現在のレンダラー |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | レンダーキュー |

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


Initialize the entity renderer

**Parameters:**
| Parameter | Type | 説明 |
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


Prepare rendering commands for specified node/entity pair.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 現在のレンダラーインスタンス |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | レンダータスクを管理するために使用されるレンダーキュー |
| node | [Node](../../com.aspose.threed/node) | 現在のノード |
| entity | [Entity](../../com.aspose.threed/entity) | レンダリングが必要なエンティティ |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


Each render task pushed to the [IRenderQueue](../../com.aspose.threed/irenderqueue) will have a corresponding RenderEntity call to perform the concrete rendering job.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | レンダラー |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | レンダリングコマンドを記録するために使用される commandList |
| node | [Node](../../com.aspose.threed/node) | レンダリングされるエンティティの PrepareRenderQueue に渡されたのと同じノード |
| renderableResource | java.lang.Object | PrepareRenderQueue 中に IRenderQueue に渡されたカスタムオブジェクト |
| subEntity | int | IRenderQueue に渡されたサブエンティティのインデックス |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


The scene has changed or removed, need to dispose scene-level render resources in this

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

