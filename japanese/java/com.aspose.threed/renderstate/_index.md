---
title: "RenderState"
second_title: "Aspose.3D for Java API リファレンス"
description: "パイプライン構築用のレンダー状態。レンダー状態に加えた変更は、作成されたパイプラインインスタンスに影響しません。"
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
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RenderState()](#RenderState--) | [RenderState](../../com.aspose.threed/renderstate) のコンストラクタ |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [close()](#close--) | [RenderState](../../com.aspose.threed/renderstate) を破棄し、すべての内部リソースを解放します。 |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | レンダリング状態を別のインスタンスと比較する |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。 |
| [getBlend()](#getBlend--) | フラグメントブレンディングを有効または無効にする。 |
| [getBlendColor()](#getBlendColor--) | [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) で使用されるブレンドカラーを取得します |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | カリング面を有効または無効にする |
| [getCullFaceMode()](#getCullFaceMode--) | カリングされる面を取得します。 |
| [getDepthFunction()](#getDepthFunction--) | 深度テストで使用される比較関数を取得します |
| [getDepthMask()](#getDepthMask--) | 深度書き込みを有効または無効にする。 |
| [getDepthTest()](#getDepthTest--) | 深度テストを有効または無効にする。 |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | 色のブレンド方法を取得します。 |
| [getFrontFace()](#getFrontFace--) | 表面が前面になる順序を取得します。 |
| [getPolygonMode()](#getPolygonMode--) | ポリゴンのレンダーモードを取得します。 |
| [getScissorTest()](#getScissorTest--) | シザーテストを有効または無効にする |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | 色のブレンド方法を取得します。 |
| [getStencilBackFace()](#getStencilBackFace--) | 背面のステンシル状態を取得します。 |
| [getStencilFrontFace()](#getStencilFrontFace--) | 前面のステンシル状態を取得します。 |
| [getStencilMask()](#getStencilMask--) | テスト完了時に参照値と保存されたステンシル値の両方と AND されるマスクを取得します。 |
| [getStencilReference()](#getStencilReference--) | ステンシルテストの参照値を取得します。 |
| [getStencilTest()](#getStencilTest--) | ステンシルテストを有効または無効にする。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | フラグメントブレンディングを有効または無効にする。 |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) で使用されるブレンドカラーを設定します |
| [setCullFace(boolean value)](#setCullFace-boolean-) | カリング面を有効または無効にする |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | カリングされる面を設定します。 |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | 深度テストで使用される比較関数を設定します |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | 深度書き込みを有効または無効にする。 |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | 深度テストを有効または無効にする。 |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | 色のブレンド方法を設定します。 |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | 表面が前面になる順序を設定します。 |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | ポリゴンのレンダーモードを設定します。 |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | シザーテストを有効または無効にする |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | 色のブレンド方法を設定します。 |
| [setStencilMask(int value)](#setStencilMask-int-) | テストが完了したときに、参照値と保存されたステンシル値の両方とAND演算されるマスクを設定します。 |
| [setStencilReference(int value)](#setStencilReference-int-) | ステンシルテストの参照値を設定します。 |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | ステンシルテストを有効または無効にする。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


[RenderState](../../com.aspose.threed/renderstate) のコンストラクタ

### close() {#close--}
```
public void close()
```


[RenderState](../../com.aspose.threed/renderstate) を破棄し、すべての内部リソースを解放します。

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


レンダリング状態を別のインスタンスと比較する

**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


フラグメントブレンディングを有効または無効にする。

**Returns:**
boolean - フラグメントブレンドを有効または無効にします。
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


[BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) で使用されるブレンドカラーを取得します

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


カリング面を有効または無効にする

**Returns:**
boolean - カリング面を有効または無効にします
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


カリングされる面を取得します。

**Returns:**
int - カリングされる面を指定します。
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


深度テストで使用される比較関数を取得します

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


深度書き込みを有効または無効にする。

**Returns:**
boolean - 深度書き込みを有効または無効にします。
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


深度テストを有効または無効にする。

**Returns:**
boolean - 深度テストを有効または無効にします。
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


色のブレンド方法を取得します。

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


表面が前面になる順序を取得します。

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


ポリゴンのレンダーモードを取得します。

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


シザーテストを有効または無効にする

**Returns:**
boolean - シザーテストを有効または無効にします
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


色のブレンド方法を取得します。

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


背面のステンシル状態を取得します。

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


前面のステンシル状態を取得します。

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


テスト完了時に参照値と保存されたステンシル値の両方と AND されるマスクを取得します。

**Returns:**
int - テストが完了したときに、参照値と保存されたステンシル値の両方とAND演算されるマスクです。
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


ステンシルテストの参照値を取得します。

**Returns:**
int - ステンシルテストの参照値です。
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


ステンシルテストを有効または無効にする。

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


フラグメントブレンディングを有効または無効にする。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


[BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) で使用されるブレンドカラーを設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | 新しい値 |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


カリング面を有効または無効にする

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


カリングされる面を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


深度テストで使用される比較関数を設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | 新しい値 |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


深度書き込みを有効または無効にする。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


深度テストを有効または無効にする。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


色のブレンド方法を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | 新しい値 |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


表面が前面になる順序を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | 新しい値 |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


ポリゴンのレンダーモードを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | 新しい値 |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


シザーテストを有効または無効にする

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


色のブレンド方法を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | 新しい値 |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


テストが完了したときに、参照値と保存されたステンシル値の両方とAND演算されるマスクを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


ステンシルテストの参照値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


ステンシルテストを有効または無効にする。

**Parameters:**
| パラメーター | 型 | 説明 |
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

