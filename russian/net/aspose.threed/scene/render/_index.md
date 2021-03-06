---
title: Render
second_title: Справочник по Aspose.3D для .NET API
description: Рендеринг сцены во внешний файл с точки зрения данной камеры. Выходной размер по умолчанию  1024x768 а выходной формат  png
type: docs
weight: 150
url: /ru/net/aspose.threed/scene/render/
---
## Render(Camera, string) {#render_2}

Рендеринг сцены во внешний файл с точки зрения данной камеры. Выходной размер по умолчанию — 1024x768, а выходной формат — png

```csharp
public void Render(Camera camera, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | Camera | С точки зрения какой камеры выполнять рендеринг сцена |
| fileName | String | Имя выходного файла |

### Смотрите также

* class [Camera](../../../aspose.threed.entities/camera)
* class [Scene](../../scene)
* пространство имен [Aspose.ThreeD](../../scene)
* сборка [Aspose.3D](../../../)

---

## Render(Camera, string, Size, ImageFormat) {#render_3}

Рендеринг сцены во внешний файл с точки зрения данной камеры.

```csharp
public void Render(Camera camera, string fileName, Size size, ImageFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | Camera | С точки зрения какой камеры рендерить сцену |
| fileName | String | Имя выходного файла |
| size | Size | Размер конечного изображения |
| format | ImageFormat | формат изображения выходного файла |

### Смотрите также

* class [Camera](../../../aspose.threed.entities/camera)
* class [Scene](../../scene)
* пространство имен [Aspose.ThreeD](../../scene)
* сборка [Aspose.3D](../../../)

---

## Render(Camera, string, Size, ImageFormat, ImageRenderOptions) {#render_4}

Рендеринг сцены во внешний файл с точки зрения данной камеры.

```csharp
public void Render(Camera camera, string fileName, Size size, ImageFormat format, 
    ImageRenderOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | Camera | С точки зрения какой камеры рендерить сцену |
| fileName | String | Имя выходного файла |
| size | Size | Размер конечного изображения |
| format | ImageFormat | формат изображения выходного файла |
| options | ImageRenderOptions | Возможность настройки некоторых внутренних параметров. |

### Смотрите также

* class [Camera](../../../aspose.threed.entities/camera)
* class [ImageRenderOptions](../../imagerenderoptions)
* class [Scene](../../scene)
* пространство имен [Aspose.ThreeD](../../scene)
* сборка [Aspose.3D](../../../)

---

## Render(Camera, Bitmap) {#render}

Визуализация сцены в растровое изображение с точки зрения данной камеры.

```csharp
public void Render(Camera camera, Bitmap bitmap)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | Camera | С точки зрения какой камеры рендерить сцену |
| bitmap | Bitmap | Цель визуализированного результата |

### Смотрите также

* class [Camera](../../../aspose.threed.entities/camera)
* class [Scene](../../scene)
* пространство имен [Aspose.ThreeD](../../scene)
* сборка [Aspose.3D](../../../)

---

## Render(Camera, Bitmap, ImageRenderOptions) {#render_1}

Визуализация сцены в растровое изображение с точки зрения данной камеры.

```csharp
public void Render(Camera camera, Bitmap bitmap, ImageRenderOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| camera | Camera | С точки зрения какой камеры рендерить сцену |
| bitmap | Bitmap | Цель визуализированного результата |
| options | ImageRenderOptions | Возможность настройки некоторых внутренних параметров. |

### Смотрите также

* class [Camera](../../../aspose.threed.entities/camera)
* class [ImageRenderOptions](../../imagerenderoptions)
* class [Scene](../../scene)
* пространство имен [Aspose.ThreeD](../../scene)
* сборка [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
