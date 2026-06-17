---
title: "EntityRenderer"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

これをサブクラス化して、さまざまな種類のエンティティのレンダリングを実装します。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(key, features) | EntityRenderer のコンストラクタ |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| key | 文字列 | エンティティレンダラのキー |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(key) | EntityRenderer のコンストラクタ |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| key | 文字列 | エンティティレンダラのキー |

 **Result:**



---


### initialize{#initialize}

| 名前 | 説明 |
| --- | --- |
| initialize(renderer) | エンティティレンダラを初期化します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| rendere | レンダラー | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| 名前 | 説明 |
| --- | --- |
| resetSceneCache() | シーンが変更または削除されたため、シーンレベルのレンダーリソースをここで破棄する必要があります。 |

 **Result:**



---


### frameBegin{#frameBegin}

| 名前 | 説明 |
| --- | --- |
| frameBegin(renderer, renderQueue) | フレームのレンダリングを開始する |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| レンダラー | レンダラー | 現在のレンダラー |
| レンダーキュー | IRenderQueue | レンダーキュー |

 **Result:**



---


### frameEnd{#frameEnd}

| 名前 | 説明 |
| --- | --- |
| frameEnd(renderer, renderQueue) | フレームのレンダリングを終了する |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| レンダラー | レンダラー | 現在のレンダラー |
| レンダーキュー | IRenderQueue | レンダーキュー |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| 名前 | 説明 |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | 指定されたノード/エンティティのペアに対してレンダリングコマンドを準備します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| レンダラー | レンダラー | 現在のレンダラーインスタンス |
| キュー | IRenderQueue | レンダータスクを管理するために使用されるレンダーキュー |
| ノード | ノード | 現在のノード |
| エンティティ | エンティティ | レンダリングが必要なエンティティ |

 **Result:**



---


### renderEntity{#renderEntity}

| 名前 | 説明 |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | com.aspose.threed.IRenderQueue にプッシュされた各レンダータスクは、具体的なレンダリングジョブを実行するために対応する RenderEntity 呼び出しを持ちます。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| レンダラー | レンダラー | レンダラー |
| commandList | ICommandList | レンダリングコマンドを記録するために使用される commandList |
| ノード | ノード | レンダリングされるエンティティの PrepareRenderQueue に渡された同じノード |
| renderableResource | オブジェクト | PrepareRenderQueue 中に IRenderQueue に渡されたカスタムオブジェクト |
| subEntity | 数 | IRenderQueue に渡されたサブエンティティのインデックス |

 **Result:**



---


### dispose{#dispose}

| 名前 | 説明 |
| --- | --- |
| dispose() | エンティティレンダラーが破棄されます。共有リソースを解放してください。 |

 **Result:**



---



