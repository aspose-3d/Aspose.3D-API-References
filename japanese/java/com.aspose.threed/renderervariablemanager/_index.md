---
title: RendererVariableManager
second_title: Aspose.3D for Java API リファレンス
description: このクラスはレンダリングで使用される変数を管理します。
type: docs
weight: 154
url: /ja/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

このクラスはレンダリングで使用される変数を管理します。
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | ワールド座標系におけるカメラの位置 |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | シャドウマッピングの深度バイアス、デフォルト値は 0.001 |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | ライト空間変換用マトリックス |
| [getMatrixProjection()](#getMatrixProjection--) | 投影変換用マトリックス |
| [getMatrixView()](#getMatrixView--) | ビュー変換用マトリックス |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | ビューおよび投影変換用マトリックス。 |
| [getMatrixWorld()](#getMatrixWorld--) | ワールド変換用マトリックス |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | オブジェクト空間からワールド空間への法線変換用マトリックス。 |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | ワールドビューと投影変換のための行列 |
| [getShadowCaster()](#getShadowCaster--) | ワールド座標系におけるシャドウキャスターの位置 |
| [getShadowmap()](#getShadowmap--) | シャドウマッピングに使用される深度テクスチャ |
| [getViewportSize()](#getViewportSize--) | ピクセル単位で測定されたビューポートのサイズ |
| [getWorldAmbient()](#getWorldAmbient--) | ビューポートで定義された環境光カラー。 |
| [getWorldTime()](#getWorldTime--) | 秒単位の時間 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | ワールド座標系におけるカメラの位置 |
| [setDepthBias(float value)](#setDepthBias-float-) | シャドウマッピングの深度バイアス、デフォルト値は 0.001 |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | ライト空間変換用マトリックス |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | 投影変換用マトリックス |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | ビュー変換用マトリックス |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | ワールド座標系におけるシャドウキャスターの位置 |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | シャドウマッピングに使用される深度テクスチャ |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | ピクセル単位で測定されたビューポートのサイズ |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | ビューポートで定義された環境光カラー。 |
| [setWorldTime(float value)](#setWorldTime-float-) | 秒単位の時間 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


ワールド座標系におけるカメラの位置

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Camera's position in world coordinate system
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepthBias() {#getDepthBias--}
```
public float getDepthBias()
```


シャドウマッピングの深度バイアス、デフォルト値は 0.001

**Returns:**
float - シャドウマッピングの深度バイアス、デフォルト値は 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


ライト空間変換用マトリックス

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


投影変換用マトリックス

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


ビュー変換用マトリックス

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


ビューおよび投影変換用マトリックス。

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


ワールド変換用マトリックス

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


オブジェクト空間からワールド空間への法線変換用マトリックス。

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


ワールドビューと投影変換のための行列

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


ワールド座標系におけるシャドウキャスターの位置

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


シャドウマッピングに使用される深度テクスチャ

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


ピクセル単位で測定されたビューポートのサイズ

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


ビューポートで定義された環境光カラー。

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


秒単位の時間

**Returns:**
float - 秒単位の時間
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




### setCameraPosition(FVector3 value) {#setCameraPosition-com.aspose.threed.FVector3-}
```
public void setCameraPosition(FVector3 value)
```


ワールド座標系におけるカメラの位置

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | 新しい値 |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


シャドウマッピングの深度バイアス、デフォルト値は 0.001

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


ライト空間変換用マトリックス

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | 新しい値 |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


投影変換用マトリックス

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | 新しい値 |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


ビュー変換用マトリックス

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | 新しい値 |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


ワールド座標系におけるシャドウキャスターの位置

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | 新しい値 |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


シャドウマッピングに使用される深度テクスチャ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | 新しい値 |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


ピクセル単位で測定されたビューポートのサイズ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | 新しい値 |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


ビューポートで定義された環境光カラー。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | 新しい値 |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


秒単位の時間

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

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

