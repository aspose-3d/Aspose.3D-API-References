---
title: IRenderTarget
second_title: Aspose.3D for Java API Reference
description: रेंडर टार्गेट का बेस इंटरफ़ेस
type: docs
weight: 249
url: /hi/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

रेंडर टार्गेट का बेस इंटरफ़ेस
## Methods

| Method | विवरण |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | निर्दिष्ट कैमरा परिप्रेक्ष्य में एक व्यूपोर्ट बनाएं। |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | निर्दिष्ट कैमरा परिप्रेक्ष्य में स्थिति/आकार के साथ एक व्यूपोर्ट बनाएं। |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | निर्दिष्ट कैमरा परिप्रेक्ष्य में निर्दिष्ट पृष्ठभूमि रंग और स्थिति/आकार के साथ एक व्यूपोर्ट बनाएं। |
| [getSize()](#getSize--) | रेंडर लक्ष्य का आकार प्राप्त करता है। |
| [getViewports()](#getViewports--) | इस रेंडर लक्ष्य से जुड़े सभी व्यूपोर्ट प्राप्त करता है। |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | रेंडर लक्ष्य का आकार निर्धारित करता है। |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


निर्दिष्ट कैमरा परिप्रेक्ष्य में एक व्यूपोर्ट बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | कैमरा |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


निर्दिष्ट कैमरा परिप्रेक्ष्य में स्थिति/आकार के साथ एक व्यूपोर्ट बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | कैमरा |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | व्यूपोर्ट की स्थिति और आकार |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


निर्दिष्ट कैमरा परिप्रेक्ष्य में निर्दिष्ट पृष्ठभूमि रंग और स्थिति/आकार के साथ एक व्यूपोर्ट बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | कैमरा |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | व्यूपोर्ट की पृष्ठभूमि |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | व्यूपोर्ट की स्थिति और आकार |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


रेंडर लक्ष्य का आकार प्राप्त करता है।

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


इस रेंडर लक्ष्य से जुड़े सभी व्यूपोर्ट प्राप्त करता है।

**Returns:**
java.util.List<com.aspose.threed.Viewport> - इस रेंडर लक्ष्य से जुड़े सभी व्यूपोर्ट।
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


रेंडर लक्ष्य का आकार निर्धारित करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | नया मान |

