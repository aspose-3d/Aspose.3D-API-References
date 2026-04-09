---
title: TextureData.MapPixels
second_title: Aspose.3D for .NET API 参考手册
description: TextureData 方法。 为读写映射所有像素
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
| mapMode | 像素映射模式 | 映射模式 |

### 另请参见

* class [PixelMapping](../../pixelmapping/)
* enum [PixelMapMode](../../pixelmapmode/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)

---

## MapPixels(PixelMapMode, PixelFormat) {#mappixels_1}

以给定像素格式映射所有像素以进行读/写

```csharp
public PixelMapping MapPixels(PixelMapMode mapMode, PixelFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mapMode | 像素映射模式 | 映射模式 |
| 格式 | 像素格式 | 像素格式 |

### 另请参见

* class [PixelMapping](../../pixelmapping/)
* enum [PixelMapMode](../../pixelmapmode/)
* enum [PixelFormat](../../pixelformat/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)

---

## MapPixels(Rect, PixelMapMode, PixelFormat) {#mappixels_2}

映射由矩形指定的像素，以给定像素格式进行读取/写入

```csharp
public PixelMapping MapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rect | 要访问的像素区域 |
| mapMode | 像素映射模式 | 映射模式 |
| 格式 | 像素格式 | 像素格式 |

### 返回值

返回映射对象，使用完毕后应释放。

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


