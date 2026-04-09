---
title: ICommandList
second_title: Aspose.3D for Java API リファレンス
description: GPU に送信されてレンダリングされるコマンドのシーケンスをエンコードします。
type: docs
weight: 240
url: /ja/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

GPU に送信されてレンダリングされるコマンドのシーケンスをエンコードします。
## Methods

| Method | 説明 |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | ディスクリプタセットを現在のパイプラインにバインドする |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | レンダリング用にインデックスバッファをバインドする |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | レンダリング用にパイプラインインスタンスをバインドする |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | レンダリング用に頂点バッファをバインドする |
| [draw()](#draw--) | インデックスバッファなしで描画する |
| [draw(int start, int count)](#draw-int-int-) | インデックスバッファなしで描画する |
| [drawIndex()](#drawIndex--) | コマンドリストにインデックス付き描画を発行する |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | コマンドリストにインデックス付き描画を発行する |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | 定数をパイプラインにプッシュする |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | 定数をパイプラインにプッシュする |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


ディスクリプタセットを現在のパイプラインにバインドする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


レンダリング用にインデックスバッファをバインドする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


レンダリング用にパイプラインインスタンスをバインドする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


レンダリング用に頂点バッファをバインドする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


インデックスバッファなしで描画する

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


インデックスバッファなしで描画する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 開始 | int |  |
| カウント | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


コマンドリストにインデックス付き描画を発行する

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


コマンドリストにインデックス付き描画を発行する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 開始 | int | 描画する最初のインデックス |
| カウント | int | 描画するインデックスの数 |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


定数をパイプラインにプッシュする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ステージ | int | どのシェーダーステージが定数データを消費するか |
| データ | byte[] | シェーダーに送信されるデータ |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


定数をパイプラインにプッシュする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ステージ | int | どのシェーダーステージが定数データを消費するか |
| データ | byte[] | シェーダーに送信されるデータ |
| サイズ | int | パイプラインに書き込むバイト数 |

