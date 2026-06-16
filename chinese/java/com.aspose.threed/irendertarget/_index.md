---
title: "IRenderTarget"
second_title: "Aspose.3D for Java API 参考"
description: "渲染目标的基础接口"
type: docs
weight: 249
url: /zh/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

渲染目标的基础接口
## 方法

| 方法 | 描述 |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | 在指定的相机视角中创建视口。 |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | 在指定的相机视角中创建具有位置/大小的视口。 |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | 在指定的相机视角中创建具有指定背景颜色和位置/大小的视口。 |
| [getSize()](#getSize--) | 获取渲染目标的大小。 |
| [getViewports()](#getViewports--) | 获取与此渲染目标关联的所有视口。 |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | 设置渲染目标的大小。 |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


在指定的相机视角中创建视口。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 相机 |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


在指定的相机视角中创建具有位置/大小的视口。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 相机 |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | 视口的位置和大小 |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


在指定的相机视角中创建具有指定背景颜色和位置/大小的视口。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 相机 |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | 视口的背景 |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | 视口的位置和大小 |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


获取渲染目标的大小。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


获取与此渲染目标关联的所有视口。

**Returns:**
java.util.List<com.aspose.threed.Viewport> - 与此渲染目标关联的所有视口。
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


设置渲染目标的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新值 |

