---
title: Renderer
second_title: Aspose.3D for Java API リファレンス
description: レンダラーに関するコンテキストです。
type: docs
weight: 152
url: /ja/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

レンダラーに関するコンテキストです。
## Methods

| Method | 説明 |
| --- | --- |
| [clearCache()](#clearCache--) | キャッシュを手動でクリアします。 |
| [close()](#close--) | [Renderer](../../com.aspose.threed/renderer) を破棄し、関連するすべてのリソースを解放します |
| [createRenderer()](#createRenderer--) | デフォルトプロファイルで新しい [Renderer](../../com.aspose.threed/renderer) を作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | 指定されたレンダーターゲットでポストプロセッシングを実行します |
| [getAssetDirectories()](#getAssetDirectories--) | 外部アセットが保存されているディレクトリ |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | シャドウを有効にするかどうかを取得します。 |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | エンティティに特別なレンダラーが定義されていない場合のフォールバックエンティティレンダラーを取得します。 |
| [getFrustum()](#getFrustum--) | ビュー行列を提供するために使用されるフラスタムを取得します。 |
| [getMaterial()](#getMaterial--) | シェーダーで使用されるマテリアル情報を提供するために使用されるマテリアルを取得します。 |
| [getNode()](#getNode--) | ワールド変換行列を提供するために使用される [getNode](../../com.aspose.threed/renderer\#getNode) インスタンスを取得します。 |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | レンダラーがサポートする組み込みのポストプロセッサを取得します。 |
| [getPostProcessings()](#getPostProcessings--) | アクティブなポストプロセッシングチェーン |
| [getPresetShaders()](#getPresetShaders--) | プリセットシェーダーセットを取得します |
| [getRenderFactory()](#getRenderFactory--) | レンダー関連オブジェクトを構築するファクトリを取得します。 |
| [getRenderStage()](#getRenderStage--) | 現在のレンダーステージを取得します。 |
| [getRenderTarget()](#getRenderTarget--) | 以下のレンダー操作が実行されるレンダーターゲットを指定します。 |
| [getShader()](#getShader--) | ジオメトリのレンダリングに使用されるシェーダーインスタンスを取得します。 |
| [getShaderSet()](#getShaderSet--) | シーンのレンダリングに使用されるシェーダーセットを取得します |
| [getVariables()](#getVariables--) | レンダリングに使用される内部変数へアクセスします |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | 指定されたエンティティのエンティティレンダラーを登録します |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | 指定されたターゲットをレンダリングします |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | シャドウを有効にするかどうかを設定します。 |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | エンティティに特別なレンダラーが定義されていない場合のフォールバックエンティティレンダラーを設定します。 |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | ビュー行列を提供するために使用されるフラスタムを設定します。 |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | シェーダーで使用されるマテリアル情報を提供するために使用されるマテリアルを設定します。 |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | ワールド変換行列を提供するために使用される [getNode](../../com.aspose.threed/renderer\#getNode) インスタンスを設定します。 |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | プリセットシェーダーセットを設定します |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | ジオメトリのレンダリングに使用されるシェーダーインスタンスを設定します。 |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | シーンのレンダリングに使用されるシェーダーセットを設定します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


キャッシュを手動でクリアします。Aspose.3D はマテリアルやジオメトリなどのオブジェクトをレンダーパイプラインと互換性のある内部タイプにキャッシュします。シーンに大きな変更がある場合は手動で呼び出す必要があります。

### close() {#close--}
```
public void close()
```


[Renderer](../../com.aspose.threed/renderer) を破棄し、関連するすべてのリソースを解放します

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


デフォルトプロファイルで新しい [Renderer](../../com.aspose.threed/renderer) を作成します。

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
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
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


指定されたレンダーターゲットでポストプロセッシングを実行します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


外部アセットが保存されているディレクトリ

**Returns:**
java.util.ArrayList<java.lang.String> - 外部アセットが格納されているディレクトリ
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


シャドウを有効にするかどうかを取得します。

**Returns:**
boolean - 影を有効にするかどうか。
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


エンティティに特別なレンダラーが定義されていない場合のフォールバックエンティティレンダラーを取得します。

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


ビュー行列を提供するために使用されるフラスタムを取得します。

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


シェーダーで使用されるマテリアル情報を提供するために使用されるマテリアルを取得します。

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


ワールド変換行列を提供するために使用される [getNode](../../com.aspose.threed/renderer\#getNode) インスタンスを取得します。

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


レンダラーがサポートする組み込みのポストプロセッサを取得します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


アクティブなポストプロセッシングチェーン

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - アクティブなポストプロセッシングチェーン
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


プリセットシェーダーセットを取得します

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


レンダー関連オブジェクトを構築するファクトリを取得します。

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


現在のレンダーステージを取得します。

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


以下のレンダー操作が実行されるレンダーターゲットを指定します。

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


ジオメトリのレンダリングに使用されるシェーダーインスタンスを取得します。

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


シーンのレンダリングに使用されるシェーダーセットを取得します

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


レンダリングに使用される内部変数へアクセスします

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


指定されたエンティティのエンティティレンダラーを登録します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


指定されたターゲットをレンダリングします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


シャドウを有効にするかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


エンティティに特別なレンダラーが定義されていない場合のフォールバックエンティティレンダラーを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | 新しい値 |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


ビュー行列を提供するために使用されるフラスタムを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | 新しい値 |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


シェーダーで使用されるマテリアル情報を提供するために使用されるマテリアルを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | 新しい値 |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


ワールド変換行列を提供するために使用される [getNode](../../com.aspose.threed/renderer\#getNode) インスタンスを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新しい値 |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


プリセットシェーダーセットを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | 新しい値 |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


ジオメトリのレンダリングに使用されるシェーダーインスタンスを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 新しい値 |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


シーンのレンダリングに使用されるシェーダーセットを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | 新しい値 |

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

