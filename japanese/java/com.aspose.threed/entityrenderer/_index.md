---
title: "EntityRenderer"
second_title: "Aspose.3D for Java API リファレンス"
description: "これをサブクラス化して、さまざまな種類のエンティティのレンダリングを実装します。"
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
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | [EntityRenderer](../../com.aspose.threed/entityrenderer) のコンストラクタ |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | [EntityRenderer](../../com.aspose.threed/entityrenderer) のコンストラクタ |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [dispose()](#dispose--) | エンティティレンダラが破棄されようとしており、共有リソースを解放します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | フレームのレンダリングを開始する |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | フレームのレンダリングを終了する |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | エンティティレンダラを初期化する |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | 指定されたノード/エンティティのペアのレンダリングコマンドを準備する。 |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | 各レンダリングタスクが[IRenderQueue](../../com.aspose.threed/irenderqueue)にプッシュされると、具体的なレンダリングジョブを実行するための対応する RenderEntity 呼び出しが行われます。 |
| [resetSceneCache()](#resetSceneCache--) | シーンが変更または削除されたため、この場合シーンレベルのレンダリングリソースを破棄する必要があります。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


[EntityRenderer](../../com.aspose.threed/entityrenderer) のコンストラクタ

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | エンティティレンダラーのキー |
| 機能 | バイト | エンティティレンダラーの追加機能 |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


[EntityRenderer](../../com.aspose.threed/entityrenderer) のコンストラクタ

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | エンティティレンダラーのキー |

### dispose() {#dispose--}
```
public void dispose()
```


エンティティレンダラが破棄されようとしており、共有リソースを解放します。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


フレームのレンダリングを開始する

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 現在のレンダラー |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | レンダーキュー |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


フレームのレンダリングを終了する

**Parameters:**
| パラメーター | 型 | 説明 |
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


エンティティレンダラを初期化する

**Parameters:**
| パラメーター | 型 | 説明 |
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


指定されたノード/エンティティのペアのレンダリングコマンドを準備する。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 現在のレンダラーインスタンス |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | レンダータスクを管理するために使用されるレンダーキュー |
| node | [Node](../../com.aspose.threed/node) | 現在のノード |
| entity | [Entity](../../com.aspose.threed/entity) | レンダリングが必要なエンティティ |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


各レンダリングタスクが[IRenderQueue](../../com.aspose.threed/irenderqueue)にプッシュされると、具体的なレンダリングジョブを実行するための対応する RenderEntity 呼び出しが行われます。

**Parameters:**
| パラメーター | 型 | 説明 |
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


シーンが変更または削除されたため、この場合シーンレベルのレンダリングリソースを破棄する必要があります。

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

