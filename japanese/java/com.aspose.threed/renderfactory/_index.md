---
title: RenderFactory
second_title: Aspose.3D for Java API リファレンス
description: RenderFactoryはレンダリングパイプラインで表されるすべてのリソースを作成します。
type: docs
weight: 148
url: /ja/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

RenderFactoryはレンダリングパイプラインで表されるすべてのリソースを作成します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | 1 つのキューブテクスチャを含むレンダーターゲットを作成します |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | 指定されたシェーダープログラム用のディスクリプタセットを作成します。 |
| [createIndexBuffer()](#createIndexBuffer--) | ポリゴンの面情報を格納するための [IIndexBuffer](../../com.aspose.threed/iindexbuffer) インスタンスを作成します。 |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | 事前設定されたシェーダー/レンダー状態/頂点宣言と描画操作を備えた、事前構成されたグラフィックスパイプラインを作成します。 |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | テクスチャにレンダリングする 1 つのターゲットを含むレンダーターゲットを作成します |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | テクスチャにレンダリングするレンダーターゲットを作成します |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | ネイティブウィンドウにレンダリングするレンダーターゲットを作成します。 |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | [ShaderProgram](../../com.aspose.threed/shaderprogram) オブジェクトを作成します |
| [createTextureUnit()](#createTextureUnit--) | シェーダーからアクセス可能な 2D テクスチャユニットを作成します。 |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | シェーダーからアクセス可能なテクスチャユニットを作成します。 |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | 事前に割り当てられたサイズで GPU 側に新しいユニフォームバッファを作成します。 |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | ポリゴンの頂点情報を格納するための [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) インスタンスを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderFactory() {#RenderFactory--}
```
public RenderFactory()
```


### createCubeRenderTexture(RenderParameters parameters, int width, int height) {#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createCubeRenderTexture(RenderParameters parameters, int width, int height)
```


1 つのキューブテクスチャを含むレンダーターゲットを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | レンダーテクスチャを作成するためのレンダー パラメータ |
| 幅 | int | レンダーテクスチャの幅 |
| 高さ | int | レンダーテクスチャの高さ |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


指定されたシェーダープログラム用のディスクリプタセットを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | シェーダープログラム |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


ポリゴンの面情報を格納するための [IIndexBuffer](../../com.aspose.threed/iindexbuffer) インスタンスを作成します。

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


事前設定されたシェーダー/レンダー状態/頂点宣言と描画操作を備えた、事前構成されたグラフィックスパイプラインを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | レンダリングで使用されるシェーダー |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | レンダリングで使用されるレンダー状態 |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | 入力頂点データの頂点宣言 |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | 描画操作 |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


テクスチャにレンダリングする 1 つのターゲットを含むレンダーターゲットを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | レンダーテクスチャを作成するためのレンダー パラメータ |
| 幅 | int | レンダーテクスチャの幅 |
| 高さ | int | レンダーテクスチャの高さ |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


テクスチャにレンダリングするレンダーターゲットを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | レンダーテクスチャを作成するためのレンダー パラメータ |
| ターゲット | int | カラー出力ターゲットの数 |
| 幅 | int | レンダーテクスチャの幅 |
| 高さ | int | レンダーテクスチャの高さ |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


ネイティブウィンドウにレンダリングするレンダーターゲットを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | レンダーウィンドウを作成するためのレンダーパラメータ |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | レンダー対象ウィンドウのハンドル |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


[ShaderProgram](../../com.aspose.threed/shaderprogram) オブジェクトを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | シェーダーのソースコード |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


シェーダーからアクセス可能な 2D テクスチャユニットを作成します。

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


シェーダーからアクセス可能なテクスチャユニットを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | テクスチャのタイプ |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


事前に割り当てられたサイズで GPU 側に新しいユニフォームバッファを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| サイズ | int | ユニフォームバッファのサイズ |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


ポリゴンの頂点情報を格納するための [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) インスタンスを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

