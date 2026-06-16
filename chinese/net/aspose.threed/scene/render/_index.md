---
title: "Scene.Render"
second_title: "Aspose.3D for .NET API 参考"
description: "Scene 方法。从给定摄像机视角将场景渲染为外部文件。默认输出尺寸为 1024x768，输出格式为 png"
type: docs
weight: 150
url: /zh/net/aspose.threed/scene/render/
---
## Render(Camera, string) {#render_2}

从给定相机的视角将场景渲染为外部文件。默认输出尺寸为 1024x768，输出格式为 png。

```csharp
public void Render(Camera camera, string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 摄像机 | 摄像机 | 从哪个摄像机的视角渲染场景 |
| fileName | 字符串 | 输出文件的文件名 |

### 另请参见

* class [Camera](../../../aspose.threed.entities/camera/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string) {#render_3}

从给定相机的视角将场景渲染为外部文件。

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 摄像机 | 摄像机 | 从哪个摄像机的视角渲染场景 |
| fileName | 字符串 | 输出文件的文件名 |
| 尺寸 | Vector2 | 最终渲染图像的尺寸 |
| 格式 | 字符串 | 输出文件的图像格式 |

### 另请参见

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string, ImageRenderOptions) {#render_4}

从给定相机的视角将场景渲染为外部文件。

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format, 
    ImageRenderOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 摄像机 | 摄像机 | 从哪个摄像机的视角渲染场景 |
| fileName | 字符串 | 输出文件的文件名 |
| 尺寸 | Vector2 | 最终渲染图像的尺寸 |
| 格式 | 字符串 | 输出文件的图像格式 |
| 选项 | ImageRenderOptions | 用于自定义某些内部设置的选项。 |

### 另请参见

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData) {#render}

从给定相机的视角将场景渲染为位图。

```csharp
public void Render(Camera camera, TextureData bitmap)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 摄像机 | 摄像机 | 从哪个摄像机的视角渲染场景 |
| 位图 | TextureData | 渲染结果的目标 |

### 另请参见

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData, ImageRenderOptions) {#render_1}

从给定相机的视角将场景渲染为位图。

```csharp
public void Render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 摄像机 | 摄像机 | 从哪个摄像机的视角渲染场景 |
| 位图 | TextureData | 渲染结果的目标 |
| 选项 | ImageRenderOptions | 用于自定义某些内部设置的选项。 |

### 另请参见

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


