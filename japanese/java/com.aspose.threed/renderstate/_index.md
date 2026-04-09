---
title: RenderState
second_title: Aspose.3D for Java API リファレンス
description: パイプライン構築用のレンダー状態。レンダー状態に加えた変更は、作成されたパイプラインインスタンスに影響しません。
type: docs
weight: 151
url: /ja/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

パイプライン構築のためのレンダー状態です。レンダー状態に加えた変更は、作成されたパイプラインインスタンスに影響しません。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [RenderState()](#RenderState--) | Constructor of [RenderState](../../com.aspose.threed/renderstate) |
## Methods

| Method | 説明 |
| --- | --- |
| [close()](#close--) | Dispose the [RenderState](../../com.aspose.threed/renderstate) and release all internal resources. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Compare the render state with another instance |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。 |
| [getBlend()](#getBlend--) | Enable or disable the fragment blending. |
| [getBlendColor()](#getBlendColor--) | Gets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Enable or disable cull face |
| [getCullFaceMode()](#getCullFaceMode--) | Gets which face will be culled. |
| [getDepthFunction()](#getDepthFunction--) | Gets the compare function used in depth test |
| [getDepthMask()](#getDepthMask--) | Enable or disable the depth writing. |
| [getDepthTest()](#getDepthTest--) | Enable or disable the depth test. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Gets how the color is blended. |
| [getFrontFace()](#getFrontFace--) | Gets which order is front face. |
| [getPolygonMode()](#getPolygonMode--) | Gets the polygon's render mode. |
| [getScissorTest()](#getScissorTest--) | Enable or disable scissor test |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Gets how the color is blended. |
| [getStencilBackFace()](#getStencilBackFace--) | Gets the stencil state for back face. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Gets the stencil state for front face. |
| [getStencilMask()](#getStencilMask--) | Gets the mask that is ANDed with the both reference and stored stencil value when test is done. |
| [getStencilReference()](#getStencilReference--) | Gets the reference value for the stencil test. |
| [getStencilTest()](#getStencilTest--) | Enable or disable the stencil test. |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Enable or disable the fragment blending. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Sets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Enable or disable cull face |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Sets which face will be culled. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Sets the compare function used in depth test |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Enable or disable the depth writing. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Enable or disable the depth test. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Sets how the color is blended. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Sets which order is front face. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | ポリゴンのレンダーモードを設定します。 |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Enable or disable scissor test |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Sets how the color is blended. |
| [setStencilMask(int value)](#setStencilMask-int-) | テストが完了したときに、参照値と保存されたステンシル値の両方とAND演算されるマスクを設定します。 |
| [setStencilReference(int value)](#setStencilReference-int-) | ステンシルテストの参照値を設定します。 |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Enable or disable the stencil test. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


Constructor of [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


Dispose the [RenderState](../../com.aspose.threed/renderstate) and release all internal resources.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Compare the render state with another instance

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | 比較用の別のレンダー状態 |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


Enable or disable the fragment blending.

**Returns:**
boolean - フラグメントブレンドを有効または無効にします。
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Gets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCullFace() {#getCullFace--}
```
public boolean getCullFace()
```


Enable or disable cull face

**Returns:**
boolean - カリング面を有効または無効にします
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Gets which face will be culled.

**Returns:**
int - カリングされる面を指定します。
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Gets the compare function used in depth test

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Enable or disable the depth writing.

**Returns:**
boolean - 深度書き込みを有効または無効にします。
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Enable or disable the depth test.

**Returns:**
boolean - 深度テストを有効または無効にします。
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Gets how the color is blended.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Gets which order is front face.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Gets the polygon's render mode.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Enable or disable scissor test

**Returns:**
boolean - シザーテストを有効または無効にします
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Gets how the color is blended.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Gets the stencil state for back face.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Gets the stencil state for front face.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Gets the mask that is ANDed with the both reference and stored stencil value when test is done.

**Returns:**
int - テストが完了したときに、参照値と保存されたステンシル値の両方とAND演算されるマスクです。
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Gets the reference value for the stencil test.

**Returns:**
int - ステンシルテストの参照値です。
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Enable or disable the stencil test.

**Returns:**
boolean - ステンシルテストを有効または無効にします。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

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




### setBlend(boolean value) {#setBlend-boolean-}
```
public void setBlend(boolean value)
```


Enable or disable the fragment blending.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Sets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | 新しい値 |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Enable or disable cull face

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Sets which face will be culled.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Sets the compare function used in depth test

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | 新しい値 |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Enable or disable the depth writing.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Enable or disable the depth test.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Sets how the color is blended.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | 新しい値 |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Sets which order is front face.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | 新しい値 |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


ポリゴンのレンダーモードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | 新しい値 |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


Enable or disable scissor test

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Sets how the color is blended.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | 新しい値 |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


テストが完了したときに、参照値と保存されたステンシル値の両方とAND演算されるマスクを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


ステンシルテストの参照値を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


Enable or disable the stencil test.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

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

