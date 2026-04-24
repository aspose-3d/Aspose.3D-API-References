---
title: IRenderTarget
second_title: Aspose.3D for Java API リファレンス
description: レンダーターゲットの基本インターフェイス
type: docs
weight: 249
url: /ja/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

レンダーターゲットの基本インターフェイス
## Methods

| Method | 説明 |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | 指定されたカメラ視点でビューポートを作成します。 |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | 指定されたカメラ視点で位置/サイズを指定してビューポートを作成します。 |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | 指定された背景色と位置/サイズで、指定されたカメラ視点のビューポートを作成します。 |
| [getSize()](#getSize--) | レンダーターゲットのサイズを取得します。 |
| [getViewports()](#getViewports--) | このレンダーターゲットに関連付けられたすべてのビューポートを取得します。 |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | レンダーターゲットのサイズを設定します。 |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


指定されたカメラ視点でビューポートを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | カメラ |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


指定されたカメラ視点で位置/サイズを指定してビューポートを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | カメラ |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | ビューポートの位置とサイズ |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


指定された背景色と位置/サイズで、指定されたカメラ視点のビューポートを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | カメラ |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | ビューポートの背景 |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | ビューポートの位置とサイズ |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


レンダーターゲットのサイズを取得します。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


このレンダーターゲットに関連付けられたすべてのビューポートを取得します。

**Returns:**
java.util.List<com.aspose.threed.Viewport> - このレンダーターゲットに関連付けられたすべてのビューポート。
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


レンダーターゲットのサイズを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

