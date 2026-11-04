---
title: "Scene.Render"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Scene. Рендерит сцену во внешний файл с точки зрения указанной камеры. Размер вывода по умолчанию 1024x768, а формат вывода — png"
type: docs
weight: 150
url: /ru/net/aspose.threed/scene/render/
---
## Render(Camera, string) {#render_2}

Рендерит сцену во внешний файл с точки зрения заданной камеры. Размер вывода по умолчанию — 1024x768, а формат вывода — png.

```csharp
public void Render(Camera camera, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| камера | Камера | С какой точки зрения камеры рендерить сцену |
| fileName | String | Имя выходного файла |

### См. также

* class [Camera](../../../aspose.threed.entities/camera/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string) {#render_3}

Рендерит сцену во внешний файл с точки зрения заданной камеры.

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| камера | Камера | С какой точки зрения камеры рендерить сцену |
| fileName | String | Имя выходного файла |
| размер | Vector2 | Размер окончательного отрисованного изображения |
| формат | String | Формат изображения выходного файла |

### См. также

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string, ImageRenderOptions) {#render_4}

Рендерит сцену во внешний файл с точки зрения заданной камеры.

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format, 
    ImageRenderOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| камера | Камера | С какой точки зрения камеры рендерить сцену |
| fileName | String | Имя выходного файла |
| размер | Vector2 | Размер окончательного отрисованного изображения |
| формат | String | Формат изображения выходного файла |
| options | ImageRenderOptions | Опция для настройки некоторых внутренних параметров. |

### См. также

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData) {#render}

Рендерит сцену в bitmap с точки зрения заданной камеры.

```csharp
public void Render(Camera camera, TextureData bitmap)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| камера | Камера | С какой точки зрения камеры рендерить сцену |
| bitmap | TextureData | Цель отрисованного результата |

### См. также

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData, ImageRenderOptions) {#render_1}

Рендерит сцену в bitmap с точки зрения заданной камеры.

```csharp
public void Render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| камера | Камера | С какой точки зрения камеры рендерить сцену |
| bitmap | TextureData | Цель отрисованного результата |
| options | ImageRenderOptions | Опция для настройки некоторых внутренних параметров. |

### См. также

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


