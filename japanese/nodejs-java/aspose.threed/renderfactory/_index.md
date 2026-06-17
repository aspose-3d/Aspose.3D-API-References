---
title: "RenderFactory"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory はレンダリングパイプラインで表現されるすべてのリソースを作成します。  @hideconstructor


## メソッド

### createRenderTexture{#createRenderTexture}

| 名前 | 説明 |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | テクスチャにレンダリングするレンダーターゲットを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| パラメータ | RenderParameters | レンダー テクスチャを作成するためのパラメータ |
| ターゲット | 数 | カラー出力ターゲットの数 |
| 幅 | 数 | レンダー テクスチャの幅 |
| height | 数 | レンダー テクスチャの高さ |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| 名前 | 説明 |
| --- | --- |
| createRenderTexture(parameters, width, height) | テクスチャにレンダリングする1つのターゲットを含むレンダーターゲットを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| パラメータ | RenderParameters | レンダー テクスチャを作成するためのパラメータ |
| 幅 | 数 | レンダー テクスチャの幅 |
| height | 数 | レンダー テクスチャの高さ |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| 名前 | 説明 |
| --- | --- |
| createDescriptorSet(shader) | 指定されたシェーダープログラム用のディスクリプタセットを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| シェーダー | ShaderProgram | シェーダープログラム |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| 名前 | 説明 |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | 1つのキューブテクスチャを含むレンダーターゲットを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| パラメータ | RenderParameters | レンダー テクスチャを作成するためのパラメータ |
| 幅 | 数 | レンダー テクスチャの幅 |
| height | 数 | レンダー テクスチャの高さ |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| 名前 | 説明 |
| --- | --- |
| createRenderWindow(parameters, handle) | ネイティブウィンドウにレンダリングするレンダーターゲットを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| パラメータ | RenderParameters | レンダーウィンドウを作成するためのパラメータ |
| ハンドル | WindowHandle | レンダリングするウィンドウのハンドル |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| 名前 | 説明 |
| --- | --- |
| createVertexBuffer(declaration) | ポリゴンの頂点情報を格納するための com.aspose.threed.IVertexBuffer インスタンスを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 宣言 | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| 名前 | 説明 |
| --- | --- |
| createIndexBuffer() | ポリゴンの面情報を格納するための com.aspose.threed.IIndexBuffer インスタンスを作成します。 |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| 名前 | 説明 |
| --- | --- |
| createTextureUnit(textureType) | シェーダーからアクセス可能なテクスチャユニットを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| 名前 | 説明 |
| --- | --- |
| createTextureUnit() | シェーダーからアクセス可能な 2D テクスチャユニットを作成します。 |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| 名前 | 説明 |
| --- | --- |
| createShaderProgram(shaderSource) | ShaderProgram オブジェクトを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| shaderSource | シェーダーソース | シェーダーのソースコード |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| 名前 | 説明 |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | 事前設定されたシェーダー、レンダー状態、頂点宣言、描画操作を備えたグラフィックスパイプラインを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| シェーダー | ShaderProgram | レンダリングで使用されるシェーダー |
| renderState | RenderState | レンダリングで使用されるレンダー状態 |
| vertexDeclaration | VertexDeclaration | 入力頂点データの頂点宣言 |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| 名前 | 説明 |
| --- | --- |
| createUniformBuffer(size) | GPU側で事前に割り当てられたサイズで新しいユニフォームバッファを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| サイズ | 数 | ユニフォームバッファのサイズ |

 **Result:**
IBuffer


---



