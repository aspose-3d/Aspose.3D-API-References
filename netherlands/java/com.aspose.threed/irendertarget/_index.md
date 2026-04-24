---
title: IRenderTarget
second_title: Aspose.3D for Java API-referentie
description: De basisinterface van render target
type: docs
weight: 249
url: /nl/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

De basisinterface van render target
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | Maak een viewport in de opgegeven cameraperspectief. |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | Maak een viewport met positie/grootte in de opgegeven cameraperspectief. |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | Maak een viewport met opgegeven achtergrondkleur en positie/grootte in de opgegeven cameraperspectief. |
| [getSize()](#getSize--) | Haalt de grootte van het renderdoel op. |
| [getViewports()](#getViewports--) | Haalt alle viewports op die geassocieerd zijn met dit renderdoel. |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | Stelt de grootte van het renderdoel in. |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


Maak een viewport in de opgegeven cameraperspectief.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | De camera |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


Maak een viewport met positie/grootte in de opgegeven cameraperspectief.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | De camera |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Positie en grootte van de viewport |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


Maak een viewport met opgegeven achtergrondkleur en positie/grootte in de opgegeven cameraperspectief.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | De camera |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | De achtergrond van de viewport |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Positie en grootte van de viewport |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


Haalt de grootte van het renderdoel op.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


Haalt alle viewports op die geassocieerd zijn met dit renderdoel.

**Returns:**
java.util.List<com.aspose.threed.Viewport> - alle viewports die geassocieerd zijn met dit renderdoel.
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


Stelt de grootte van het renderdoel in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nieuwe waarde |

