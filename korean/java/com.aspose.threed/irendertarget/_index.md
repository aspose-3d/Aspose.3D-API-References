---
title: IRenderTarget
second_title: Aspose.3D for Java API 레퍼런스
description: 렌더 타깃의 기본 인터페이스
type: docs
weight: 249
url: /ko/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

렌더 타깃의 기본 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | 지정된 카메라 시점에서 뷰포트를 생성합니다. |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | 지정된 카메라 시점에서 위치/크기로 뷰포트를 생성합니다. |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | 지정된 배경색과 위치/크기로 지정된 카메라 시점에서 뷰포트를 생성합니다. |
| [getSize()](#getSize--) | 렌더 타겟의 크기를 가져옵니다. |
| [getViewports()](#getViewports--) | 이 렌더 타겟과 연결된 모든 뷰포트를 가져옵니다. |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | 렌더 타겟의 크기를 설정합니다. |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


지정된 카메라 시점에서 뷰포트를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 카메라 |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


지정된 카메라 시점에서 위치/크기로 뷰포트를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 카메라 |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | 뷰포트의 위치와 크기 |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


지정된 배경색과 위치/크기로 지정된 카메라 시점에서 뷰포트를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 카메라 |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | 뷰포트의 배경 |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | 뷰포트의 위치와 크기 |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


렌더 타겟의 크기를 가져옵니다.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


이 렌더 타겟과 연결된 모든 뷰포트를 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.Viewport> - 이 렌더 타겟과 연결된 모든 뷰포트.
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


렌더 타겟의 크기를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 새 값 |

