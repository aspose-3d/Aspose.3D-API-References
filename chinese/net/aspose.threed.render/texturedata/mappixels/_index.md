---
title: "TextureData.MapPixels"
second_title: "Aspose.3D for .NET API 参考"
description: "TextureData 方法. 映射所有像素以进行读/写"
type: docs
weight: 100
url: /zh/net/aspose.threed.render/texturedata/mappixels/
---
## MapPixels(PixelMapMode) {#mappixels}

映射所有像素以进行读/写

```csharp
public PixelMapping MapPixels(PixelMapMode mapMode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mapMode | PixelMapMode | 映射模式 |

### 另请参见

* class [PixelMapping](../../pixelmapping/)
* enum [PixelMapMode](../../pixelmapmode/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)

---

## MapPixels(PixelMapMode, PixelFormat) {#mappixels_1}

在给定像素格式下映射所有像素以进行读/写

```csharp
public PixelMapping MapPixels(PixelMapMode mapMode, PixelFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mapMode | PixelMapMode | 映射模式 |
| 格式 | PixelFormat | 像素格式 |

### 另请参见

* class [PixelMapping](../../pixelmapping/)
* enum [PixelMapMode](../../pixelmapmode/)
* enum [PixelFormat](../../pixelformat/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)

---

## MapPixels(Rect, PixelMapMode, PixelFormat) {#mappixels_2}

在给定像素格式下映射由矩形指定的像素以进行读取/写入

```csharp
public PixelMapping MapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | 矩形 | 要访问的像素区域 |
| mapMode | PixelMapMode | 映射模式 |
| 格式 | PixelFormat | 像素格式 |

### 返回值

返回一个映射对象，使用完毕后应释放。

### 异常

| 异常 | 条件 |
| --- | --- |
| NotSupportedException |  |

### 另请参见

* class [PixelMapping](../../pixelmapping/)
* struct [Rect](../../../aspose.threed.utilities/rect/)
* enum [PixelMapMode](../../pixelmapmode/)
* enum [PixelFormat](../../pixelformat/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)


