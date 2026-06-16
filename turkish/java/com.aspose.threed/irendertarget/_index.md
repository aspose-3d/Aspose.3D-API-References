---
title: "IRenderTarget"
second_title: "Aspose.3D for Java API Referansı"
description: "Render hedefinin temel arayüzü"
type: docs
weight: 249
url: /tr/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

Render hedefinin temel arayüzü
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | Belirtilen kamera perspektifinde bir görüntü alanı oluştur. |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | Belirtilen kamera perspektifinde konum/ölçü ile bir görüntü alanı oluştur. |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | Belirtilen kamera perspektifinde konum/ölçü ve belirtilen arka plan rengi ile bir görüntü alanı oluştur. |
| [getSize()](#getSize--) | Render hedefinin boyutunu alır. |
| [getViewports()](#getViewports--) | Bu render hedefiyle ilişkili tüm görüntü alanlarını alır. |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | Render hedefinin boyutunu ayarlar. |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


Belirtilen kamera perspektifinde bir görüntü alanı oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Kamera |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


Belirtilen kamera perspektifinde konum/ölçü ile bir görüntü alanı oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Kamera |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Görüntü alanının konumu ve boyutu |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


Belirtilen kamera perspektifinde konum/ölçü ve belirtilen arka plan rengi ile bir görüntü alanı oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Kamera |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | Görüntü alanının arka planı |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Görüntü alanının konumu ve boyutu |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


Render hedefinin boyutunu alır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


Bu render hedefiyle ilişkili tüm görüntü alanlarını alır.

**Returns:**
java.util.List<com.aspose.threed.Viewport> - bu render hedefiyle ilişkili tüm görüntü alanları.
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


Render hedefinin boyutunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

