---
title: IRenderTarget
second_title: Aspose.3D for Java API Reference
description: L'interfaccia base del render target
type: docs
weight: 249
url: /it/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

L'interfaccia base del render target
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | Crea una viewport nella prospettiva della telecamera specificata. |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | Crea una viewport con posizione/dimensione nella prospettiva della telecamera specificata. |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | Crea una viewport con colore di sfondo specificato e posizione/dimensione nella prospettiva della telecamera specificata. |
| [getSize()](#getSize--) | Ottiene la dimensione del render target. |
| [getViewports()](#getViewports--) | Ottiene tutte le viewport associate a questo render target. |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | Imposta la dimensione del render target. |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


Crea una viewport nella prospettiva della telecamera specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | La telecamera |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


Crea una viewport con posizione/dimensione nella prospettiva della telecamera specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | La telecamera |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Posizione e dimensione della viewport |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


Crea una viewport con colore di sfondo specificato e posizione/dimensione nella prospettiva della telecamera specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | La telecamera |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | Lo sfondo della viewport |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Posizione e dimensione della viewport |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


Ottiene la dimensione del render target.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


Ottiene tutte le viewport associate a questo render target.

**Returns:**
java.util.List<com.aspose.threed.Viewport> - tutte le viewport associate a questo render target.
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


Imposta la dimensione del render target.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuovo valore |

