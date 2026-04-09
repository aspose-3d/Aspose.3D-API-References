---
title: IRenderTarget
second_title: Aspose.3D for Java API-referens
description: Basgränssnittet för renderingsmål
type: docs
weight: 249
url: /sv/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

Basgränssnittet för renderingsmål
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | Skapa en viewport i angivet kameraperspektiv. |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | Skapa en viewport med position/storlek i angivet kameraperspektiv. |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | Skapa en viewport med angiven bakgrundsfärg samt position/storlek i angivet kameraperspektiv. |
| [getSize()](#getSize--) | Hämtar storleken på render-målet. |
| [getViewports()](#getViewports--) | Hämtar alla viewports som är associerade med detta render-mål. |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | Ställer in storleken på render-målet. |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


Skapa en viewport i angivet kameraperspektiv.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Kameran |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


Skapa en viewport med position/storlek i angivet kameraperspektiv.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Kameran |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Position och storlek för viewporten |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


Skapa en viewport med angiven bakgrundsfärg samt position/storlek i angivet kameraperspektiv.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Kameran |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | Bakgrunden för viewporten |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Position och storlek för viewporten |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


Hämtar storleken på render-målet.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


Hämtar alla viewports som är associerade med detta render-mål.

**Returns:**
java.util.List<com.aspose.threed.Viewport> - alla viewports som är associerade med detta render-mål.
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


Ställer in storleken på render-målet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nytt värde |

