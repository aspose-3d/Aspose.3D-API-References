---
title: IRenderTarget
second_title: Referensi API Aspose.3D untuk Java
description: Antarmuka dasar target render.
type: docs
weight: 249
url: /id/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

Antarmuka dasar target render.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | Buat viewport dalam perspektif kamera yang ditentukan. |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | Buat viewport dengan posisi/ukuran dalam perspektif kamera yang ditentukan. |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | Buat viewport dengan warna latar belakang yang ditentukan serta posisi/ukuran dalam perspektif kamera yang ditentukan. |
| [getSize()](#getSize--) | Mendapatkan ukuran target render. |
| [getViewports()](#getViewports--) | Mendapatkan semua viewport yang terkait dengan target render ini. |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | Mengatur ukuran target render. |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


Buat viewport dalam perspektif kamera yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Kamera |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


Buat viewport dengan posisi/ukuran dalam perspektif kamera yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Kamera |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Posisi dan ukuran viewport |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


Buat viewport dengan warna latar belakang yang ditentukan serta posisi/ukuran dalam perspektif kamera yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Kamera |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | Latar belakang viewport |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Posisi dan ukuran viewport |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


Mendapatkan ukuran target render.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


Mendapatkan semua viewport yang terkait dengan target render ini.

**Returns:**
java.util.List<com.aspose.threed.Viewport> - semua viewport yang terkait dengan target render ini.
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


Mengatur ukuran target render.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

