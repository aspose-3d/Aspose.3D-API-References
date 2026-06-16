---
title: "IRenderTarget"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "الواجهة الأساسية لهدف التصيير"
type: docs
weight: 249
url: /ar/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

الواجهة الأساسية لهدف التصيير
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | إنشاء نافذة عرض في منظور الكاميرا المحدد. |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | إنشاء نافذة عرض مع الموضع/الحجم في منظور الكاميرا المحدد. |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | إنشاء نافذة عرض مع لون خلفية محدد والموضع/الحجم في منظور الكاميرا المحدد. |
| [getSize()](#getSize--) | يحصل على حجم هدف العرض. |
| [getViewports()](#getViewports--) | يحصل على جميع نوافذ العرض المرتبطة بهذا هدف العرض. |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | يضبط حجم هدف العرض. |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


إنشاء نافذة عرض في منظور الكاميرا المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | الكاميرا |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


إنشاء نافذة عرض مع الموضع/الحجم في منظور الكاميرا المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | الكاميرا |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | الموضع والحجم للنافذة العرض |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


إنشاء نافذة عرض مع لون خلفية محدد والموضع/الحجم في منظور الكاميرا المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | الكاميرا |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | خلفية نافذة العرض |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | الموضع والحجم للنافذة العرض |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


يحصل على حجم هدف العرض.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


يحصل على جميع نوافذ العرض المرتبطة بهذا هدف العرض.

**Returns:**
java.util.List<com.aspose.threed.Viewport> - جميع نوافذ العرض المرتبطة بهذا هدف العرض.
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


يضبط حجم هدف العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | القيمة الجديدة |

