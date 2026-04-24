---
title: IRenderTarget
second_title: Справочник API Aspose.3D для Java
description: Базовый интерфейс цели рендеринга
type: docs
weight: 249
url: /ru/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

Базовый интерфейс цели рендеринга
## Методы

| Метод | Описание |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | Создать область просмотра в заданной перспективе камеры. |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | Создать область просмотра с позицией/размером в заданной перспективе камеры. |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | Создать область просмотра с указанным цветом фона и позицией/размером в заданной перспективе камеры. |
| [getSize()](#getSize--) | Получает размер render target. |
| [getViewports()](#getViewports--) | Получает все области просмотра, связанные с этим render target. |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | Устанавливает размер render target. |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


Создать область просмотра в заданной перспективе камеры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Камера |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


Создать область просмотра с позицией/размером в заданной перспективе камеры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Камера |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Позиция и размер области просмотра |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


Создать область просмотра с указанным цветом фона и позицией/размером в заданной перспективе камеры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Камера |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | Фон области просмотра |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Позиция и размер области просмотра |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


Получает размер render target.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


Получает все области просмотра, связанные с этим render target.

**Returns:**
java.util.List<com.aspose.threed.Viewport> — все области просмотра, связанные с этим render target.
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


Устанавливает размер render target.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Новое значение |

