---
title: "レンダラー"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/renderer/
---
## Renderer class

レンダラーに関するコンテキスト。  @hideconstructor


## メソッド

### getShaderSet{#getShaderSet}

| 名前 | 説明 |
| --- | --- |
| getShaderSet() | シーンのレンダリングに使用されるシェーダーセットを取得または設定します。 |

 **Result:**



---


### setShaderSet{#setShaderSet}

| 名前 | 説明 |
| --- | --- |
| setShaderSet(value) | シーンのレンダリングに使用されるシェーダーセットを取得または設定します。 |

 **Result:**



---


### getVariables{#getVariables}

| 名前 | 説明 |
| --- | --- |
| getVariables() | レンダリングに使用される内部変数へのアクセス |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| 名前 | 説明 |
| --- | --- |
| getPresetShaders() | プリセットシェーダーセットを取得または設定します。プロパティの値は PresetShaders の整数定数です。 |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| 名前 | 説明 |
| --- | --- |
| setPresetShaders(value) | プリセットシェーダーセットを取得または設定します。プロパティの値は PresetShaders の整数定数です。 |

 **Result:**



---


### getRenderFactory{#getRenderFactory}

| 名前 | 説明 |
| --- | --- |
| getRenderFactory() | レンダー関連オブジェクトを構築するファクトリを取得します。 |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| 名前 | 説明 |
| --- | --- |
| getAssetDirectories() | 外部アセットが格納されているディレクトリ |

 **Result:**



---


### getPostProcessings{#getPostProcessings}

| 名前 | 説明 |
| --- | --- |
| getPostProcessings() | アクティブなポストプロセッシングチェーン |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| 名前 | 説明 |
| --- | --- |
| getEnableShadows() | シャドウを有効にするかどうかを取得または設定します。 |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| 名前 | 説明 |
| --- | --- |
| setEnableShadows(value) | シャドウを有効にするかどうかを取得または設定します。 |

 **Result:**



---


### getRenderTarget{#getRenderTarget}

| 名前 | 説明 |
| --- | --- |
| getRenderTarget() | 以下のレンダー操作が実行されるレンダーターゲットを指定します。 |

 **Result:**



---


### getNode{#getNode}

| 名前 | 説明 |
| --- | --- |
| getNode() | ワールド変換行列を提供するために使用される Node インスタンスを取得または設定します。 |

 **Result:**



---


### setNode{#setNode}

| 名前 | 説明 |
| --- | --- |
| setNode(value) | ワールド変換行列を提供するために使用される Node インスタンスを取得または設定します。 |

 **Result:**



---


### getFrustum{#getFrustum}

| 名前 | 説明 |
| --- | --- |
| getFrustum() | ビュー行列を提供するために使用される視錐台を取得または設定します。 |

 **Result:**



---


### setFrustum{#setFrustum}

| 名前 | 説明 |
| --- | --- |
| setFrustum(value) | ビュー行列を提供するために使用される視錐台を取得または設定します。 |

 **Result:**



---


### getRenderStage{#getRenderStage}

| 名前 | 説明 |
| --- | --- |
| getRenderStage() | 現在のレンダーステージを取得します。プロパティの値は RenderStage の整数定数です。 |

 **Result:**



---


### getMaterial{#getMaterial}

| 名前 | 説明 |
| --- | --- |
| getMaterial() | シェーダーで使用されるマテリアル情報を提供するために使用されるマテリアルを取得または設定します。 |

 **Result:**



---


### setMaterial{#setMaterial}

| 名前 | 説明 |
| --- | --- |
| setMaterial(value) | シェーダーで使用されるマテリアル情報を提供するために使用されるマテリアルを取得または設定します。 |

 **Result:**



---


### getShader{#getShader}

| 名前 | 説明 |
| --- | --- |
| getShader() | ジオメトリのレンダリングに使用されるシェーダーインスタンスを取得または設定します。 |

 **Result:**



---


### setShader{#setShader}

| 名前 | 説明 |
| --- | --- |
| setShader(value) | ジオメトリのレンダリングに使用されるシェーダーインスタンスを取得または設定します。 |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| 名前 | 説明 |
| --- | --- |
| getFallbackEntityRenderer() | エンティティに特別なレンダラーが定義されていない場合のフォールバックエンティティレンダラーを取得または設定します。 |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| 名前 | 説明 |
| --- | --- |
| setFallbackEntityRenderer(value) | エンティティに特別なレンダラーが定義されていない場合のフォールバックエンティティレンダラーを取得または設定します。 |

 **Result:**



---


### clearCache{#clearCache}

| 名前 | 説明 |
| --- | --- |
| clearCache() | キャッシュを手動でクリアします。Aspose.3D はマテリアルやジオメトリなどのオブジェクトをレンダーパイプラインと互換性のある内部タイプにキャッシュします。シーンに大幅な変更があった場合は手動で呼び出す必要があります。 |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| 名前 | 説明 |
| --- | --- |
| getPostProcessing(name) | レンダラーがサポートする組み込みのポストプロセッサを取得します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | null |

 **Result:**
ポストプロセッシング


---


### execute{#execute}

| 名前 | 説明 |
| --- | --- |
| execute(postProcessing, result) | 指定されたレンダーターゲットでポストプロセッシングを実行します。 |

 **Result:**
ポストプロセッシング


---


### createRenderer{#createRenderer}

| 名前 | 説明 |
| --- | --- |
| createRenderer() | デフォルトプロファイルで新しい Renderer を作成します。 |

 **Result:**
レンダラー


---


### registerEntityRenderer{#registerEntityRenderer}

| 名前 | 説明 |
| --- | --- |
| registerEntityRenderer(renderer) | 指定されたエンティティのエンティティレンダラーを登録します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| rendere | EntityRenderer | null |

 **Result:**
レンダラー


---


### render{#render}

| 名前 | 説明 |
| --- | --- |
| render(renderTarget) | 指定されたターゲットをレンダーします |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
レンダラー


---



