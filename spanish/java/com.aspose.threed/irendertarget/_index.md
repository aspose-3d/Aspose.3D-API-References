---
title: IRenderTarget
second_title: Referencia de API de Aspose.3D para Java
description: La interfaz base del objetivo de renderizado
type: docs
weight: 249
url: /es/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

La interfaz base del objetivo de renderizado
## Métodos

| Método | Descripción |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | Crear una ventana de visualización en la perspectiva de cámara especificada. |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | Crear una ventana de visualización con posición/tamaño en la perspectiva de cámara especificada. |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | Crear una ventana de visualización con el color de fondo especificado y posición/tamaño en la perspectiva de cámara especificada. |
| [getSize()](#getSize--) | Obtiene el tamaño del objetivo de renderizado. |
| [getViewports()](#getViewports--) | Obtiene todas las ventanas de visualización asociadas a este objetivo de renderizado. |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | Establece el tamaño del objetivo de renderizado. |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


Crear una ventana de visualización en la perspectiva de cámara especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | La cámara |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


Crear una ventana de visualización con posición/tamaño en la perspectiva de cámara especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | La cámara |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Posición y tamaño de la ventana de visualización |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


Crear una ventana de visualización con el color de fondo especificado y posición/tamaño en la perspectiva de cámara especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | La cámara |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | El fondo de la ventana de visualización |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Posición y tamaño de la ventana de visualización |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


Obtiene el tamaño del objetivo de renderizado.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


Obtiene todas las ventanas de visualización asociadas a este objetivo de renderizado.

**Returns:**
java.util.List<com.aspose.threed.Viewport> - todas las ventanas de visualización asociadas a este objetivo de renderizado.
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


Establece el tamaño del objetivo de renderizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuevo valor |

