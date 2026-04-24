---
title: Viewport
second_title: Aspose.3D for Java API リファレンス
description: A はシーンのレンダリングのために少なくとも1つのビューポートを含みます。
type: docs
weight: 229
url: /ja/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

A [IRenderTarget](../../com.aspose.threed/irendertarget) はシーンのレンダリングのために少なくとも1つのビューポートを含みます。
## Methods

| Method | 説明 |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | レンダーターゲット内のビューポートの領域を取得します。 |
| [getBackgroundColor()](#getBackgroundColor--) | ビューポートの背景色を取得します。 |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | 深度バッファビットが設定された状態でビューポートをクリアする際に使用される深度値を取得します。 |
| [getEnabled()](#getEnabled--) | このビューポートを有効または無効にします。 |
| [getFrustum()](#getFrustum--) | この [Viewport](../../com.aspose.threed/viewport) のカメラを取得します。 |
| [getRenderTarget()](#getRenderTarget--) | このビューポートを作成したレンダーターゲットを取得します。 |
| [getZOrder()](#getZOrder--) | ビュー ポートの Z オーダーを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | レンダー ターゲット内のビュー ポートの領域を設定します。 |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | ビュー ポートの背景色を設定します。 |
| [setDepthClear(float value)](#setDepthClear-float-) | 深度バッファ ビットが設定された状態でビュー ポートをクリアする際に使用される深度値を設定します。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | このビューポートを有効または無効にします。 |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | この [Viewport](../../com.aspose.threed/viewport) のカメラを設定します |
| [setZOrder(int value)](#setZOrder-int-) | ビュー ポートの Z オーダーを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clone() {#clone--}
```
public Viewport clone()
```




**Returns:**
[Viewport](../../com.aspose.threed/viewport)
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
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


レンダーターゲット内のビューポートの領域を取得します。

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


ビューポートの背景色を取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the background color of the viewport.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepthClear() {#getDepthClear--}
```
public float getDepthClear()
```


深度バッファビットが設定された状態でビューポートをクリアする際に使用される深度値を取得します。

**Returns:**
float - 深度バッファ ビットが設定された状態でビュー ポートをクリアする際に使用される深度値。
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


このビューポートを有効または無効にします。

**Returns:**
boolean - このビュー ポートを有効または無効にします。
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


この [Viewport](../../com.aspose.threed/viewport) のカメラを取得します。

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


このビューポートを作成したレンダーターゲットを取得します。

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


ビュー ポートの Z オーダーを取得します。

**Returns:**
int - ビュー ポートの Z オーダー。
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




### setArea(RelativeRectangle value) {#setArea-com.aspose.threed.RelativeRectangle-}
```
public void setArea(RelativeRectangle value)
```


レンダー ターゲット内のビュー ポートの領域を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | 新しい値 |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


ビュー ポートの背景色を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


深度バッファ ビットが設定された状態でビュー ポートをクリアする際に使用される深度値を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


このビューポートを有効または無効にします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


この [Viewport](../../com.aspose.threed/viewport) のカメラを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | 新しい値 |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


ビュー ポートの Z オーダーを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

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

